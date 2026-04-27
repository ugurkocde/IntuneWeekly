# Intune Weekly - Edition 1
_Covering April 20 - 26, 2026_

Samsung Knox wipe trap, Secure Boot limbo, and Autopatch report breakage demand admin attention now.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-04-27/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**[Janic Verboon](https://www.linkedin.com/in/janic-verboon-04b11b114/)** - _EAM-AutoUpdater_
Built EAM-AutoUpdater, a free PowerShell automation that watches the Intune Enterprise App Catalog for new app versions, deploys them, and migrates assignments, scope tags, and Enrollment Status Page references from the previous version. Turns a recurring manual chore into an Azure Automation runbook. [Read more](https://github.com/JanicVerboon/EAM-AutoUpdater)

## On the radar this week

- **[Samsung Knox OEMConfig Wipe Block Leaves Devices Unrecoverable](https://www.reddit.com/r/sysadmin/comments/1svi8te/warning_with_fully_managed_samsung_devices_and_intune/)** _(Reddit)_ - A KSP profile that blocks device reset causes Intune to report a successful wipe while the device never resets, with no recovery path - audit all KSP profiles before any production deployment.
- **[Secure Boot Certificate Rollout Stranding Devices in Observation](https://www.reddit.com/r/sysadmin/comments/1srp86f/im_incredibly_confused_by_microsofts_remediation/)** _(Reddit)_ - Fleets with devices approaching six years old risk being stuck with UEFICA2023Status 'Not started' as the update window tightens - validate certificate status now using community detection scripts.
- **[Autopatch Quality Updates Report Broken for Weeks](https://www.reddit.com/r/Intune/comments/1sso3r4/is_the_autopatch_management_status_report_just/)** _(Reddit)_ - Multiple admins confirm the managed-for-quality-updates count has shown zero for weeks despite devices receiving updates normally - check your report before assuming compliance coverage is accurate.
- **[Hotpatch 24H2: ARM64 Config Gap and Secure Boot Miss Risk](https://www.reddit.com/r/Intune/comments/1ss4gs9/opinions_of_hot_patch/)** _(Reddit)_ - ARM64 devices need a separate config profile that documentation doesn't surface clearly, and one fleet saw Secure Boot updates skipped while Hotpatch was active - validate both before broad rollout.
- **[AI Speed Is Making Patch Compliance a Security Baseline](https://techcommunity.microsoft.com/t5/intune-customer-success/as-vulnerability-discovery-moves-at-ai-speed-keeping-current-is/ba-p/4513766)** _(Tech Community)_ - Microsoft's Intune Customer Success team frames AI-accelerated exploitation as a reason to treat Autopatch and update compliance as a foundational security control, not an operational nicety.

---

## In this edition

**Landing in your tenant soon**
- [Secure Boot Certificate Update: Devices Stuck "Under Observation" May Need Manual Intervention](https://www.reddit.com/r/sysadmin/comments/1srp86f/im_incredibly_confused_by_microsofts_remediation/)

**On the horizon**
- [EPM Network Adapter Elevation: Microsoft Confirms Feature Is in the Works](https://www.reddit.com/r/Intune/comments/1stzhef9/epm_for_network_adapter_change/)

**Action required**
- [Samsung Knox OEMConfig Wipe Block: Devices Can Become Permanently Unrecoverable](https://www.reddit.com/r/sysadmin/comments/1svi8te/warning_with_fully_managed_samsung_devices_and_intune/)

**What shipped**
- ["Unpacking Endpoint Management" Series Returns with Engineering Participation](https://techcommunity.microsoft.com/t5/intune-customer-success/unpacking-endpoint-management-is-back-and-we-ve-got-a-lot-to/ba-p/4514599)
- [Keeping Current Is Now a Security Imperative as AI Accelerates Vulnerability Exploitation](https://techcommunity.microsoft.com/t5/intune-customer-success/as-vulnerability-discovery-moves-at-ai-speed-keeping-current-is/ba-p/4513766)
- [Windows Updates During Autopilot OOBE Now Supported via Enrollment Status Page](https://www.reddit.com/r/Intune/comments/1st15h8/windows_updates_during_oobe_autopilot/)

**From the field**
- [EPM Local Admin Removal: Start Small, Audit First, Communicate Early](https://www.reddit.com/r/sysadmin/comments/1sucuh6/half_our_company_is_local_admin_security_team/)
- [Autopatch "Managed for Quality Updates" Report Showing Zero for Weeks](https://www.reddit.com/r/Intune/comments/1sso3r4/is_the_autopatch_management_status_report_just/)
- [Autopilot V2 Device Preparation: Enterprise-Scale Gaps Keep Large Orgs on V1](https://techcommunity.microsoft.com/t5/microsoft-intune/autopilot-v1-vs-device-preparation-v2-great-direction-but-is-it/m-p/4514362#M23381)
- [Hotpatch on 24H2: Generally Positive But Watch ARM64 Devices and Secure Boot Interactions](https://www.reddit.com/r/Intune/comments/1ss4gs9/opinions_of_hot_patch/)
- [EntraMap: Open-Source Visual Relationship Mapper for Entra ID Tenants](https://www.reddit.com/r/Intune/comments/1su9fdn/i_built_an_open_source_visual_map_for_microsoft/)
- [Logic App for Apple Certificate and Token Expiry Monitoring in Intune](https://www.reddit.com/r/Intune/comments/1srypqx/logic_app_to_monitor_expiring_apple_certificates/)
- ["Something Went Wrong" Device List Error Appeared and Resolved Without Microsoft Acknowledgement](https://www.reddit.com/r/Intune/comments/1ssgr95/something_went_wrong_viewing_device_list_anyone/)
- [macOS Platform SSO Requires ADE Enrollment - User-Driven Company Portal Enrollment Falls Short](https://www.reddit.com/r/Intune/comments/1sruk61/enroll_existing_macs_into_intune_enable_entra_id/)
- [Intune App Assignment Targeting: Restricting Installs to Autopilot OOBE Only](https://www.reddit.com/r/Intune/comments/1ssnbb2/i_want_to_install_an_intune_app_only_during/)
- [Dell Factory Reimaging to 24H2: Skip Dell OS Recovery, Use TechDirect Instead](https://www.reddit.com/r/Intune/comments/1squrq4/autopilot_reset_dell_fleet/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-04-27/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
