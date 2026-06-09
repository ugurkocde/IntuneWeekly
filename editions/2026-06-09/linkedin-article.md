# Intune Weekly - Edition 7
_Covering June 2 - 8, 2026_

WUfB driver bypass, ASR silent disables, and Scripts reliability meltdown dominate a turbulent week.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-09/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**Simon Hartmann Eriksen & Roy Klooster** - _PPPC Builder for macOS_
A lightweight web-based tool that generates macOS PPPC (.mobileconfig) profiles tailored for Microsoft Intune. Select an app (or upload its Info.plist), choose the required privacy permissions (Screen Recording, Full Disk Access, Camera, Microphone, Accessibility), and download a ready-to-deploy .mobileconfig for Intune. No Jamf dependency; simple, fast, Intune-focused. [Read more](https://github.com/Simsen/PPPC-Builder)

## On the radar this week

- **[WUfB Driver Policies Bypassed: 32 Drivers Force-Installed](https://www.reddit.com/r/Intune/comments/1tus7af/driver_updates_wufb/)** _(Reddit)_ - A Microsoft-acknowledged service incident (MO1332784) caused declined driver policies to be ignored across multiple tenants, so admins should audit driver inventory and declined states immediately.
- **[ASR Rules Silently Disabled by Baseline + Policy Conflict](https://www.reddit.com/r/Intune/comments/1txnfox/bug_found_in_attack_surface_reduction_through_intune/)** _(Reddit)_ - Conflicting ASR assignments between a Security Baseline and an Endpoint Security profile silently disable rules with no conflict alert, leaving endpoints potentially unprotected without any visible warning.
- **[Scripts & Remediations: Silent Failures and 8-Day Execution Gaps](https://www.reddit.com/r/sysadmin/comments/1tvks8e/intune_is_not_fit_for_purpose/)** _(Reddit)_ - A 900-upvote community thread documents widespread silent failures, missing logs, and multi-day execution delays in Scripts and Remediations, making any automation relying on these features unreliable right now.
- **[Secure Boot CA 2023: Manual Task Trigger Required for Update](https://www.reddit.com/r/Intune/comments/1tuqj8r/secure_boot_certificate_update_status_change/)** _(Reddit)_ - BIOS updates alone do not trigger the Secure Boot CA 2023 certificate update, and the scheduled task must be manually invoked, so admins relying on passive rollout may miss the update entirely before compliance deadlines.
- **[MDOP End of Support: Migrate MBAM and App-V to Intune](https://techcommunity.microsoft.com/t5/intune-customer-success/mdop-is-out-of-support-what-to-do-next-with-microsoft-intune/ba-p/4526024)** _(Blog - Customer Success)_ - MDOP passed end of extended support on April 14, 2026, meaning any remaining MBAM or App-V workloads are now unpatched security risks and migration to Intune equivalents should be treated as urgent.

---

## In this edition

**Landing in your tenant soon**

- [MDE iOS In-App OS Update Notifications Retiring Mid-July 2026](https://mc.merill.net/message/MC1381122)

**On the horizon**

- [MDOP End of Support: Migration Path to Intune](https://techcommunity.microsoft.com/t5/intune-customer-success/mdop-is-out-of-support-what-to-do-next-with-microsoft-intune/ba-p/4526024)
- [Windows 365 Developer-Focused Enhancements Announced at Build 2026](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/made-for-developers-and-agents-windows-365-at-build-2026/ba-p/4519041)
- [macOS ADE: No Supported Method to Enforce Minimum OS Version Before Platform SSO Registration](https://techcommunity.microsoft.com/t5/microsoft-intune/intune-macos-ade-support-for-minimum-macos-version-enforcement/m-p/4525688#M23530)

**Action required**

- [Secure Boot CA 2023 Certificate Update: Widespread Admin Confusion, Manual Trigger Available](https://www.reddit.com/r/Intune/comments/1tuqj8r/secure_boot_certificate_update_status_change/)

**From the field**

- [WUfB Driver Update Policies Bypassed: 32 Drivers Installed Across Multiple Tenants Simultaneously](https://www.reddit.com/r/Intune/comments/1tus7af/driver_updates_wufb/)
- [ASR Rules Silently Disabled When Security Baseline and Endpoint Security Profile Conflict](https://www.reddit.com/r/Intune/comments/1txnfox/bug_found_in_attack_surface_reduction_through_intune/)
- [Newly Created Entra Groups and App Deployments Not Reporting or Applying This Week](https://www.reddit.com/r/sysadmin/comments/1txls2t/intune_assistance_application_not_syncing_to_devices/)
- [Motherboard Replacement Breaks Entra/Intune Authentication Due to TPM/Hardware Hash Change](https://www.reddit.com/r/sysadmin/comments/1txp89w/motherboard_replaced_on_an_entraintune_joined/)
- [Scripts and Remediations: Inconsistent Execution, No Logs, and 8-Day Gaps Draw Community Fury](https://www.reddit.com/r/sysadmin/comments/1tvks8e/intune_is_not_fit_for_purpose/)
- [Intune App Inventory Graph API Returns 403 Despite GUI Access](https://techcommunity.microsoft.com/t5/microsoft-intune/intune-app-inventory-graph/m-p/4524828#M23524)
- [Autopilot v2 Device Rename Causes Unexpected OOBE Reboot Behaviour](https://www.reddit.com/r/Intune/comments/1tvjzpv/autopilot_v2_device_rename_and_reboot_and_oobe/)
- [Remote Help Rollout: Edge Cases in Mixed Build Environments, SKU Confusion Persists](https://www.reddit.com/r/Intune/comments/1txo76c/deploying_intune_remote_help_for_modern_endpoint/)
- [Third-Party App Patching Tool Comparison: Robopack vs. Patch My PC vs. WAU](https://www.reddit.com/r/Intune/comments/1twmj89/robopack_900_a_year_patch_my_pc_3500_no_brainer/)
- [Intune Naming Schemes: Community Tool nametune.vercel.app Gaining Traction](https://www.reddit.com/r/Intune/comments/1tydpgd/what_are_your_rookiemistakes_on_intune/)
- [Hybrid Joined Devices: Community Advises Against Managing via Both GPO and Intune Simultaneously](https://www.reddit.com/r/Intune/comments/1tyd3i7/intune_or_gpo_for_hybrid_joined_endpoints/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-09/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
