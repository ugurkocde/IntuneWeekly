# Intune Weekly - Edition 1
_Covering April 20 - 26, 2026_
Samsung Knox wipe trap, Secure Boot limbo, and Autopatch report breakage demand admin attention now.

## On the radar

- **[Samsung Knox OEMConfig Wipe Block Leaves Devices Unrecoverable](https://www.reddit.com/r/sysadmin/comments/1svi8te/warning_with_fully_managed_samsung_devices_and_intune/)** _(Reddit)_ - A KSP profile that blocks device reset causes Intune to report a successful wipe while the device never resets, with no recovery path — audit all KSP profiles before any production deployment.
- **[Secure Boot Certificate Rollout Stranding Devices in Observation](https://www.reddit.com/r/sysadmin/comments/1srp86f/im_incredibly_confused_by_microsofts_remediation/)** _(Reddit)_ - Fleets with devices approaching six years old risk being stuck with UEFICA2023Status 'Not started' as the update window tightens — validate certificate status now using community detection scripts.
- **[Autopatch Quality Updates Report Broken for Weeks](https://www.reddit.com/r/Intune/comments/1sso3r4/is_the_autopatch_management_status_report_just/)** _(Reddit)_ - Multiple admins confirm the managed-for-quality-updates count has shown zero for weeks despite devices receiving updates normally — check your report before assuming compliance coverage is accurate.
- **[Hotpatch 24H2: ARM64 Config Gap and Secure Boot Miss Risk](https://www.reddit.com/r/Intune/comments/1ss4gs9/opinions_of_hot_patch/)** _(Reddit)_ - ARM64 devices need a separate config profile that documentation doesn't surface clearly, and one fleet saw Secure Boot updates skipped while Hotpatch was active — validate both before broad rollout.
- **[AI Speed Is Making Patch Compliance a Security Baseline](https://techcommunity.microsoft.com/t5/intune-customer-success/as-vulnerability-discovery-moves-at-ai-speed-keeping-current-is/ba-p/4513766)** _(Tech Community)_ - Microsoft's Intune Customer Success team frames AI-accelerated exploitation as a reason to treat Autopatch and update compliance as a foundational security control, not an operational nicety.

## Landing in your tenant soon

**Secure Boot Certificate Update: Devices Stuck "Under Observation" May Need Manual Intervention**
r/SYSADMIN /// Microsoft's phased Secure Boot certificate rollout is leaving a significant number of devices in "Under observation" status with `UEFICA2023Status` set to "Not started," and Microsoft's own remediation scripts are returning inconsistent results compared to third-party tools like PatchMyPC. Admins with fleets approaching or exceeding six years old should validate certificate status now using community detection scripts before the update window tightens further.
[Read more](https://www.reddit.com/r/sysadmin/comments/1srp86f/im_incredibly_confused_by_microsofts_remediation/)

---

## On the horizon

**EPM Network Adapter Elevation: Microsoft Confirms Feature Is in the Works**
r/INTUNE /// A community member confirmed that Microsoft is actively developing a feature to allow EPM-driven elevation from Company Portal to change NIC settings, addressing a gap where adding users to the Network Operator group causes unintended UAC side effects. No release date has been shared yet.
[Read more](https://www.reddit.com/r/Intune/comments/1stzhef9/epm_for_network_adapter_change/)

---

## Action required

**Samsung Knox OEMConfig Wipe Block: Devices Can Become Permanently Unrecoverable** [Breaking Change]
r/SYSADMIN /// If you deploy a Knox Service Plugin OEMConfig profile that blocks device reset, Intune will report a wipe as successful and remove the device from management, but the phone never actually resets — KSP continues enforcing the policy at firmware level with no recovery path. Audit any KSP profiles that include wipe or reset restrictions before deploying to production, and avoid enabling this setting on test devices you may need to reflash.
[Read more](https://www.reddit.com/r/sysadmin/comments/1svi8te/warning_with_fully_managed_samsung_devices_and_intune/)

---

## What shipped

**"Unpacking Endpoint Management" Series Returns with Engineering Participation**
REDMOND /// Microsoft has relaunched the Unpacking Endpoint Management content series, featuring contributors from Intune, Security, and Customer Experience engineering teams covering practical endpoint management strategies. Admins looking for candid, scenario-driven guidance from product teams should bookmark the series.
[Read more](https://techcommunity.microsoft.com/t5/intune-customer-success/unpacking-endpoint-management-is-back-and-we-ve-got-a-lot-to/ba-p/4514599)

**Keeping Current Is Now a Security Imperative as AI Accelerates Vulnerability Exploitation**
REDMOND /// Microsoft's Intune Customer Success team published guidance noting that AI-driven tooling is compressing the window between CVE disclosure and active exploitation, making update compliance via Autopatch and related tooling more critical than ever. The post frames staying current on patches not as best practice but as a foundational security control.
[Read more](https://techcommunity.microsoft.com/t5/intune-customer-success/as-vulnerability-discovery-moves-at-ai-speed-keeping-current-is/ba-p/4513766)

**Windows Updates During Autopilot OOBE Now Supported via Enrollment Status Page**
r/INTUNE /// Microsoft has shipped the ability to trigger Windows Updates during OOBE through the Enrollment Status Page, but admins report updates only run during the User Enrollment phase rather than the Device Enrollment phase, meaning pre-provisioned deployments still require users to wait through update installation. Community workarounds include a PowerShell-based Win32 app assigned to device groups to front-run the update cycle.
[Read more](https://www.reddit.com/r/Intune/comments/1st15h8/windows_updates_during_oobe_autopilot/)

---

## From the field

**EPM Local Admin Removal: Start Small, Audit First, Communicate Early**
r/SYSADMIN /// Two separate threads this week — one covering a 140-user environment and one a 90% local admin fleet — converged on the same advice: run EPM in audit mode across pilot cohorts before removing rights, group elevation hits by publisher and path, and get leadership to send communications before users lose access. Silent rollouts are universally recommended against; the surprise is worse than the change.
[Read more](https://www.reddit.com/r/sysadmin/comments/1sucuh6/half_our_company_is_local_admin_security_team/)

**Autopatch "Managed for Quality Updates" Report Showing Zero for Weeks**
r/INTUNE /// Multiple admins report the Autopatch management status report has been stuck at zero devices managed for quality updates for weeks, while Feature Update and Driver Update counts display correctly. Devices are confirmed to be receiving updates normally; the report itself appears broken and Microsoft has not acknowledged the issue.
[Read more](https://www.reddit.com/r/Intune/comments/1sso3r4/is_the_autopatch_management_status_report_just/)

**Autopilot V2 Device Preparation: Enterprise-Scale Gaps Keep Large Orgs on V1**
r/INTUNE /// Admins at scale report that the absence of Group Tag support and dynamic group targeting in Autopilot Device Preparation (V2) makes it unsuitable for large enterprise naming, segmentation, and governance models. The consensus is that V2 is promising but V1 remains the only viable option until feature parity improves.
[Read more](https://techcommunity.microsoft.com/t5/microsoft-intune/autopilot-v1-vs-device-preparation-v2-great-direction-but-is-it/m-p/4514362#M23381)

**Hotpatch on 24H2: Generally Positive But Watch ARM64 Devices and Secure Boot Interactions**
r/INTUNE /// Admins who have been running Hotpatch since GA report it delivers on reduced reboots, but two gotchas have surfaced: ARM64 devices require a separate config profile that isn't obvious from the documentation, and one admin reported a large portion of their fleet missing Secure Boot updates when Hotpatch was active. Worth validating both before broad rollout.
[Read more](https://www.reddit.com/r/Intune/comments/1ss4gs9/opinions_of_hot_patch/)

**EntraMap: Open-Source Visual Relationship Mapper for Entra ID Tenants**
r/INTUNE /// A community developer has released EntraMap, a free open-source tool that generates a visual graph of users, groups, apps, Conditional Access policies, and devices in a tenant, including safe-to-delete indicators. The project is early-stage and some admins note concerns about the new domain and the lack of a fully offline mode for air-gapped environments.
[Read more](https://www.reddit.com/r/Intune/comments/1su9fdn/i_built_an_open_source_visual_map_for_microsoft/)

**Logic App for Apple Certificate and Token Expiry Monitoring in Intune**
r/INTUNE /// A community admin published a Logic App solution that monitors expiring APNs certificates and VPP tokens in Intune and posts alerts to Teams, available with full deployment instructions. Useful for environments where the built-in Microsoft expiry emails are missed or where a Teams-native alert is preferred.
[Read more](https://www.reddit.com/r/Intune/comments/1srypqx/logic_app_to_monitor_expiring_apple_certificates/)

**"Something Went Wrong" Device List Error Appeared and Resolved Without Microsoft Acknowledgement**
r/INTUNE /// Multiple admins hit a widespread "Unable to fetch any device" error in the Intune device list on 22 April; the issue resolved itself within hours but Microsoft support responded saying they could not reproduce it and saw no flags. No root cause or incident post was published.
[Read more](https://www.reddit.com/r/Intune/comments/1ssgr95/something_went_wrong_viewing_device_list_anyone/)

**macOS Platform SSO Requires ADE Enrollment — User-Driven Company Portal Enrollment Falls Short**
r/INTUNE /// Admins attempting to enable Entra ID login at the macOS lock screen via Platform SSO on devices not in Apple Business Manager are finding that user-driven Company Portal enrollment alone is insufficient; ADE (Automated Device Enrollment) via ABM is effectively required for full Platform SSO functionality. Devices added to ABM via Apple Configurator still require a wipe, leaving existing in-use fleets in a difficult position.
[Read more](https://www.reddit.com/r/Intune/comments/1sruk61/enroll_existing_macs_into_intune_enable_entra_id/)

**Intune App Assignment Targeting: Restricting Installs to Autopilot OOBE Only**
r/INTUNE /// Admins trying to scope app installs exclusively to new Autopilot enrollments (not existing devices) are using a requirements script that checks for the presence of `defaultuser0`, or alternatively maintaining a snapshot exclusion group of all current devices at a point in time. Neither approach is native Intune functionality, highlighting a long-standing gap in enrollment-phase targeting.
[Read more](https://www.reddit.com/r/Intune/comments/1ssnbb2/i_want_to_install_an_intune_app_only_during/)

**Dell Factory Reimaging to 24H2: Skip Dell OS Recovery, Use TechDirect Instead**
r/INTUNE /// Admins reimaging Dell fleets report that Dell's cloud OS recovery defaults to installing 25H2, not 24H2. The recommended workaround is to use the Dell TechDirect SHIR portal to select the target OS version, or order devices with the Dell Ready Image pre-applied to avoid the issue entirely.
[Read more](https://www.reddit.com/r/Intune/comments/1squrq4/autopilot_reset_dell_fleet/)

---
Read the full broadsheet PDF: [https://ugurkocde.github.io/IntuneWeekly/editions/2026-04-27/intune-weekly.pdf](https://ugurkocde.github.io/IntuneWeekly/editions/2026-04-27/intune-weekly.pdf)
Subscribe to the LinkedIn newsletter for the next edition every Tuesday: [Intune Weekly](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)
