# Intune Weekly - Edition 4
_Covering May 12 - 18, 2026_

YellowKey BitLocker bypass, Hotpatch silently enabled, and Secure Boot certs expiring June 2026.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-19/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**[Simon Skotheimsvik](https://www.linkedin.com/in/simonskotheimsvik/)** - _1PhoneMirror_
A Windows-based screen-mirroring receiver built for Intune admins who need consistent, framed mobile screens for documentation and training. Supports iOS/macOS AirPlay (with optional PIN), Android wireless debugging via bundled adb/scrcpy, and experimental Miracast, with one-click screenshots or MP4/GIF recordings inside a device frame. Multiple devices stay paired and can be switched from a bottom bezel, with no app installs on the phones. [Read more](https://www.awesomeintune.com/tools/1phonemirror)

## On the radar this week

- **[YellowKey BitLocker Bypass - No Official Patch Yet](https://www.reddit.com/r/sysadmin/comments/1tgr205/yellowkey_mitigation/)** _(Microsoft - Learn)_ - Admins managing standalone Windows devices must evaluate disabling WinRE immediately as the only confirmed mitigation until Microsoft issues a fix; Entra-joined devices appear protected but should be verified.
- **[Hotpatch Silently Enabled Tenant-Wide from May 12](https://www.reddit.com/r/Intune/comments/1tc2v5b/hot_patch_on_by_default_now/)** _(Reddit)_ - Admins may be unaware devices are running hotpatch builds instead of the standard May CU, and those rolling out Secure Boot cert updates should expect additional unexpected reboots until the quarterly baseline CU applies.
- **[Intune Admin Center 'Access Denied' Outage on May 18](https://www.reddit.com/r/Intune/comments/1tgr0kv/anyone_else_getting_access_denied_in_intune/)** _(Reddit)_ - Multiple admins lost access to the Intune admin center despite holding valid admin roles, and the Azure status page incorrectly showed all healthy - admins should know to open a support ticket rather than rely on the status page during future incidents.
- **[Secure Boot Certificates Expiring June 2026 - Rollout Planning Urgent](https://techcommunity.microsoft.com/event/windowsevents/ask-microsoft-anything-secure-boot---may-2026/4513524)** _(Microsoft - Release Health)_ - With expiry less than 13 months away and hotpatch now delaying certificate delivery to quarterly CU cycles, admins should use the updated Autopatch Secure Boot Status report now to identify unready devices and sequence rollouts.
- **[Intune Data Warehouse Beta Power BI Connector Retiring](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)** _(Microsoft - In Development)_ - The gradual retirement began in late April 2026 and any Power BI reports built before November 2025 will lose data access if not migrated to connector v2 or the OData Feed connector immediately.

---

## In this edition

**Landing in your tenant soon**
- [Platform SSO with Registration During Automated Device Enrollment Now GA for macOS](https://techcommunity.microsoft.com/t5/intune-customer-success/new-platform-sso-with-registration-during-automated-device/ba-p/4519846)
- [Intune Data Warehouse Beta Connector in Power BI Retiring - Transition Now](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Hotpatch Now On by Default - Conflict with Secure Boot Cert Rollout](https://www.reddit.com/r/sysadmin/comments/1tdy52o/fyi_enabling_windows_hotpatch_while_update_secure/)
- [Enrollment Time Grouping for Apple ADE Policies Going GA](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Updated Secure Boot Status Report in Windows Autopatch Now Available](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/updated-secure-boot-status-report-in-windows-autopatch/ba-p/4517920)

**On the horizon**
- [Android Personally Owned Work Profile Devices Moving to Android Management API (AMAPI)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Controlled Configuration for Microsoft Defender Antivirus Settings Coming to Public Preview](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Strict Tunnel Mode for Microsoft Tunnel on Android (AMAPI Devices)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Multiple Managed Accounts for App Protection Policies Coming to iOS and Android](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Device Control Policy Support Extended to Defender for Endpoint Security Settings Management](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Scope Tags to be Enforced on EPM Reports](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [In-Place Renewal for Cloud PKI Issuing Certificate Authorities](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Custom Compliance Settings Coming to macOS](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Client-Driven Compliance Evaluation for Windows Devices Coming to Preview](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [New STIG Audit Security Baseline for GCC High Tenants](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [New 802.1x Wired Networks Profile for iOS/iPadOS](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Disable MAC Address Randomization Setting for macOS Wi-Fi Profiles](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Block Bluetooth Sharing Setting Added to Android Enterprise Settings Catalog](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Grant Enhanced Security Permissions to MTD App on Android Enterprise](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Silence Apps on Managed Home Screen During Authentication Prompts](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Agentic Identity for the Policy Configuration Agent Coming to Public Preview](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Admin Insights for Windows 365 Now in Public Preview](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/admin-insights-for-windows-365-stay-on-top-of-what-needs/ba-p/4517570)

**Action required**
- [Secure Boot Certificates Begin Expiring June 2026 - Plan Your Rollout Now](https://techcommunity.microsoft.com/event/windowsevents/ask-microsoft-anything-secure-boot---may-2026/4513524)
- [Intune Data Warehouse Beta Power BI Connector Retiring - Migrate Before Data Access Ends](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [YellowKey BitLocker Bypass - No Official Patch Yet, Evaluate Mitigations](https://www.reddit.com/r/sysadmin/comments/1tgr205/yellowkey_mitigation/)

**What shipped**
- [Multiple In-Development Features Removed from the List - Likely Shipped](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)

**From the field**
- [Widespread "Access Denied" Errors Hit Intune Admin Center - Unacknowledged on Status Page](https://www.reddit.com/r/Intune/comments/1tgr0kv/anyone_else_getting_access_denied_in_intune/)
- [Hotpatch Silently Enabled by Default - Many Admins Unaware](https://www.reddit.com/r/Intune/comments/1tc2v5b/hot_patch_on_by_default_now/)
- [YellowKey BitLocker Bypass: Field Testing Shows Entra-Joined Devices Appear Protected](https://www.reddit.com/r/sysadmin/comments/1td6g1n/yellowkey_working_irl/)
- [Autopatch Upgrading Devices from 23H2 to 25H2 Takes 40+ Minutes - Not a Bug](https://www.reddit.com/r/Intune/comments/1td7ebq/autopatch_hit_users_with_a_40min_update_from_24h2/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-19/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
