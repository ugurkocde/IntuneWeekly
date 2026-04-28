# Intune Weekly - Edition 1
_Covering April 21 - 27, 2026_

Samsung Knox wipe-block locks devices permanently; Autopatch report shows zero devices for weeks.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-04-28/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**[Janic Verboon](https://www.linkedin.com/in/janic-verboon-04b11b114/)** - _EAM-AutoUpdater_
Built EAM-AutoUpdater, a free PowerShell automation that watches the Intune Enterprise App Catalog for new app versions, deploys them, and migrates assignments, scope tags, and Enrollment Status Page references from the previous version. Turns a recurring manual chore into an Azure Automation runbook. [Read more](https://github.com/JanicVerboon/EAM-AutoUpdater)

## On the radar this week

- **[Samsung Knox OEMConfig wipe-block bricks devices permanently](https://www.reddit.com/r/Intune/comments/1svibhk/warning_with_fully_managed_samsung_devices_and/)** _(Reddit)_ - Deploying a KSP profile that blocks device reset enforces at firmware level with no recovery path - do not push to production without a validated recovery procedure.
- **[Autopatch 'Managed for quality updates' report showing zero devices](https://www.reddit.com/r/Intune/comments/1sso3r4/is_the_autopatch_management_status_report_just/)** _(Reddit)_ - The report has been broken for weeks across multiple tenants, silently undermining compliance reporting - raise a support case now if affected.
- **[Microsoft Defender now assesses Secure Boot 2023 certificate readiness fleet-wide](https://aka.ms/secureboot-mde)** _(Microsoft - Release Health)_ - New Defender capability auto-categorizes devices as exposed, compliant, or not applicable with remediation guidance attached - useful directly against the 'Under observation' pain admins are reporting.
- **[AI-speed CVE exploitation raises the bar for patch currency](https://techcommunity.microsoft.com/t5/intune-customer-success/as-vulnerability-discovery-moves-at-ai-speed-keeping-current-is/ba-p/4513766)** _(Blog - Customer Success)_ - Microsoft's customer success team warns that AI-assisted exploit discovery collapses the safe response window, making proactive Autopatch ring configuration a baseline requirement now.

---

## In this edition

**Landing in your tenant soon**
- [New IT admin policy: Remove Microsoft Copilot app](https://learn.microsoft.com/en-us/windows/client-management/mdm/policy-csp-windowsai?source=docs#removemicrosoftcopilotapp)

**On the horizon**
- [Keeping current is the new patching strategy as AI accelerates vulnerability discovery](https://techcommunity.microsoft.com/t5/intune-customer-success/as-vulnerability-discovery-moves-at-ai-speed-keeping-current-is/ba-p/4513766)
- [Autopilot Device Preparation (v2) enterprise readiness still in question for large-scale deployments](https://techcommunity.microsoft.com/t5/microsoft-intune/autopilot-v1-vs-device-preparation-v2-great-direction-but-is-it/m-p/4514362#M23381)
- [EPM network adapter elevation support reportedly in development](https://www.reddit.com/r/Intune/comments/1stzhf9/epm_for_network_adapter_change/)
- ["Unpacking Endpoint Management" series returns with engineering and product team involvement](https://techcommunity.microsoft.com/t5/intune-customer-success/unpacking-endpoint-management-is-back-and-we-ve-got-a-lot-to/ba-p/4514599)
- [Ask Microsoft Anything: Secure Boot certificate updates (April 23 and May 18)](https://aka.ms/AMA/SecureBoot)

**Action required**
- [Samsung Knox OEMConfig wipe-block policy renders devices unrecoverable - test before broad deployment](https://www.reddit.com/r/sysadmin/comments/1sucuh6/half_our_company_is_local_admin_security_team/)

**What shipped**
- [Microsoft Defender now provides centralized Secure Boot 2023 certificate readiness assessment](https://aka.ms/secureboot-mde)

**From the field**
- [Local admin removal project: EPM audit-first approach and change management are the consensus best practice](https://www.reddit.com/r/sysadmin/comments/1sucuh6/half_our_company_is_local_admin_security_team/)
- [Secure Boot certificate update: "Under observation" status and UEFICA2023Status "Not started" on majority of fleet](https://www.reddit.com/r/sysadmin/comments/1srp86f/im_incredibly_confused_by_microsofts_remediation/)
- [Autopatch "Managed for quality updates" report showing zero devices for weeks](https://www.reddit.com/r/Intune/comments/1sso3r4/is_the_autopatch_management_status_report_just/)
- [Windows Updates not applying at Device ESP phase during Autopilot pre-provisioning](https://www.reddit.com/r/Intune/comments/1st15h8/windows_updates_during_oobe_autopilot/)
- [Hotpatch on 24H2: ARM64 devices silently excluded without an additional config profile](https://www.reddit.com/r/Intune/comments/1ss4gs9/opinions_of_hot_patch/)
- [Intune device list throwing "Unable to fetch any device" errors - transient but recurring](https://www.reddit.com/r/Intune/comments/1ssgr95/something_went_wrong_viewing_device_list_anyone/)
- [EntraMap: open-source visual relationship mapper for users, groups, apps, and Conditional Access](https://www.reddit.com/r/Intune/comments/1su9fdn/i_built_an_open_source_visual_map_for_microsoft/)
- [Logic App for proactive Apple certificate and token expiry alerting in Intune](https://www.reddit.com/r/Intune/comments/1srypqx/logic_app_to_monitor_expiring_apple_certificates/)
- [Platform SSO on macOS requires ADE/ABM enrollment - user-driven Company Portal enrollment is not sufficient](https://www.reddit.com/r/Intune/comments/1sruk61/enroll_existing_macs_into_intune_enable_entra_id/)
- [GAL contacts not surfacing in iOS native dialer - no clean Intune-native solution exists](https://www.reddit.com/r/microsoft365/comments/1svggs3/anyone_else_frustrated_that_corporate_contacts/)
- [Autopatch UpdateDeferredVersions registry value behaviour under active investigation by community](https://techcommunity.microsoft.com/t5/microsoft-intune/autopatch-microsoft-365-apps-update-rings/m-p/4513986#M23376)
- [Autopilot-only app deployment: defaultuser0 requirements script is the cleanest gate](https://www.reddit.com/r/Intune/comments/1ssnbb2/i_want_to_install_an_intune_app_only_during/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-04-28/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
