# Intune Weekly - Edition 6
_Covering May 26 - June 1, 2026_

Service outages hit Autopatch & Proactive Remediation; critical defaults let users wipe corporate devices.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-02/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## On the radar this week

- **[Default Intune Settings Allow Users to Wipe Corporate Devices](https://www.reddit.com/r/Intune/comments/1tr2pg3/any_user_can_unenroll_their_device/)** _(Reddit)_ - Any enrolled user can unenroll and wipe their own corporate device via Company Portal by default - admins should hide remove/reset options in Tenant > Customization immediately.
- **[Autopatch Groups & Reporting Inaccessible - Multi-Region Outage](https://www.reddit.com/r/Intune/comments/1tr2ol2/autopatch_group_errors/)** _(Reddit)_ - Admins in UK, Europe, and US lost access to Autopatch groups and update reports; validate configurations are intact now that access appears restored.
- **[Proactive Remediation Reporting Delayed Up to 7 Days](https://www.reddit.com/r/Intune/comments/1tr3724/i_knew_it_service_degredation_reported_for/)** _(Reddit)_ - A confirmed service degradation means absence of remediation data should not be treated as success - do not make compliance or patching decisions based on reporting until resolved.
- **[mysignins.microsoft.com Down - New User MFA Registration Blocked](https://www.reddit.com/r/Intune/comments/1ttlmmk/mysigninsmicrosoftcom/)** _(Reddit)_ - New users cannot register Microsoft Authenticator via the self-service portal; workaround is to manually add authentication methods in the Entra admin center.
- **[M365 Apps Policy Blade Leaving Intune Admin Center in June 2026](https://mc.merill.net/message/MC1330892)** _(Microsoft - Message Center)_ - Admins must migrate policy creation and editing workflows to the Microsoft 365 Apps admin center before the June 2026 service release removes the current blade.

---

## In this edition

**Landing in your tenant soon**

- [M365 Apps Policy Configuration Moves Out of Intune Admin Center](https://mc.merill.net/message/MC1330892)

**On the horizon**

- [Entra Device Soft Delete Now in Preview - BitLocker Keys and LAPS Preserved for 30 Days](https://www.reddit.com/r/entra/comments/1tt73bo/the_wait_is_finally_over_for_accidental_device/)
- [Secure Boot Certificate Expiry Hits in June - AMA Scheduled June 4](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/windows-news-you-can-use-may-2026/ba-p/4516353)

**Action required**

- [Windows Autopatch Reporting and Groups Inaccessible Across Multiple Regions](https://www.reddit.com/r/Intune/comments/1tr2ol2/autopatch_group_errors/)
- [Proactive Remediation Reporting Delayed Up to 7 Days - Service Degradation Confirmed](https://www.reddit.com/r/Intune/comments/1tr3724/i_knew_it_service_degredation_reported_for/)
- [mysignins.microsoft.com Security Info Page Not Loading - New User MFA Setup Blocked](https://www.reddit.com/r/Intune/comments/1ttlmmk/mysigninsmicrosoftcom/)

**What shipped**

- [What's New in Microsoft Intune - May 2026](https://techcommunity.microsoft.com/t5/microsoft-intune-blog/what-s-new-in-microsoft-intune-may/ba-p/4491984)
- [Intune RBAC Roles Now Automatically Inherit Copilot in Intune Access](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Remote Help for Windows 5.2.1037.0 Released with Performance Improvements](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Windows Autopatch Hotpatch Now Default for Intune-Managed Devices; GCC Support Added](https://aka.ms/WindowsNewsYouCanUse/May2026)
- [May 2026 Windows 11 Non-Security Preview Update Now Available](https://support.microsoft.com/help/5089573)
- [ConfigMgr 2603 Update Now Available](https://www.reddit.com/r/SCCM/comments/1tr8t3j/cm_2603_update_available_no_new_adk/)
- [Unpacking Endpoint Management Video Series Returns](https://techcommunity.microsoft.com/t5/intune-customer-success/unpacking-endpoint-management-is-back-and-we-ve-got-a-lot-to/ba-p/4514599)

**From the field**

- [macOS WiFi Configuration Policies Returning InternalServerError via Graph - Inaccessible in Portal](https://techcommunity.microsoft.com/t5/microsoft-intune/broken-functionality-of-macoswificonfiguration-policies/m-p/4523591#M23507)
- [Company Portal (UWP) Showing Widespread Failure Rates Across Multiple Tenants](https://www.reddit.com/r/Intune/comments/1tpfjb7/company_portal_failing/)
- [Community Tool: Get-IntuneAssignments v1.0.15 Adds 7 New Policy Types](https://www.reddit.com/r/Intune/comments/1tt0dd3/new_release_alert_getintuneassignments_v1015_is/)
- [Community Tool: IME Changelog Automation - What Changed Inside the Intune Management Extension](https://www.reddit.com/r/Intune/comments/1tox16s/intune_management_extension_the_changelog/)
- [Community Tool: Foundry OSD Now Supports Zero-Touch Autopilot Hardware Hash Upload](https://www.reddit.com/r/Intune/comments/1tp3wke/zerotouch_autopilot_hardware_hash_upload_now/)
- [Default Intune Settings Allow End Users to Self-Unenroll and Wipe Their Own Corporate Devices](https://www.reddit.com/r/Intune/comments/1tr2pg3/any_user_can_unenroll_their_device/)
- [Edge "Sign in to sync your data" Splash Screen Persists Despite Intune Configuration Profile](https://techcommunity.microsoft.com/t5/microsoft-intune/edge-displays-a-splash-screen-saying-sign-in-to-sync-your-data/m-p/4523908#M23510)
- [Microsoft Store App (New) Deployment Fails Reporting When Store Is Blocked by Policy](https://www.reddit.com/r/Intune/comments/1tnqa5o/intune_microsoft_store_app_deployment_fails/)
- [macOS Platform SSO During ADE Failing 30–50% of the Time](https://www.reddit.com/r/Intune/comments/1tqz9zf/whats_new_in_microsoft_intune_may/)
- [Secure Boot Enablement May Break Windows Hello When BitLocker Is Active](https://www.reddit.com/r/Intune/comments/1ts9g5s/what_if_secureboot_is_disabled_can_certificates/)
- [On-Demand Script Execution in Intune: Remediation Scripts as the SCCM "Scripts" Replacement](https://www.reddit.com/r/Intune/comments/1ts6udr/intune_alternative_for_the_sccm_script_feature/)
- [Autopilot v2 Supports Manufacturer + Model + Serial Registration Without Hardware Hash](https://www.reddit.com/r/Intune/comments/1tsta6w/can_i_upload_windows_device_into_autopilot/)
- [WinGet Auto-Update vs. Enterprise App Management vs. Patch My PC - Community Verdict](https://www.reddit.com/r/Intune/comments/1tq3r9o/do_you_rely_on_winget_for_deploying_apps/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-02/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
