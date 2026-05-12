# Intune Weekly - Edition 3
_Covering May 5 - 11, 2026_

Tunnel servers stuck, BYOD blocked from Cloud PC, and Power BI connector retiring now.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-12/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**[Maurice Daly](https://www.linkedin.com/in/mauricedaly/)** - _Driver Automation Tool_
A PowerShell WPF desktop app that automates the full lifecycle of OEM driver and BIOS package management for ConfigMgr and Intune. It discovers vendor catalogs, downloads with resume-enabled curl, extracts, builds WIMs, and wraps packages as .intunewin for Win32 deployment. Multi-OEM support, BIOS update handling, hash verification, and configurable packaging (DISM/wimlib/7-Zip) collapse hours of manual driver work into a single signed workflow. [Read more](https://github.com/maurice-daly/DriverAutomationTool)

## On the radar this week

- **[Tunnel servers on v20260129.1 stuck - reinstall required](https://techcommunity.microsoft.com/t5/intune-customer-success/known-issue-upgrading-microsoft-tunnel-version-20260129-1/ba-p/4517935)** _(Blog - Customer Success)_ - Servers on the early-March Tunnel release are not functioning correctly and Microsoft has published a remediation script; admins must act now or deploy version 20260330.1 or later.
- **[Power BI Intune beta connector retiring - no grace period](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)** _(Microsoft - In Development)_ - The two-week retirement window is already rolling out and once complete all data access stops, so any reports built before November 2025 must be migrated to connector v2 or OData Feed immediately.
- **[BYOD devices blocked from Windows 365 Cloud PC via CA](https://techcommunity.microsoft.com/t5/microsoft-intune/byod-devices-can-t-launch-windows-365-pc-because-of-device/m-p/4518584#M23436)** _(Microsoft - Message Center)_ - The Windows 365 Client app cannot be individually excluded in Conditional Access compliance policies, causing BYOD devices to be blocked from Cloud PC with no clean workaround yet from Microsoft.
- **[Enhanced App Inventory Graph API returning forbidden errors](https://www.reddit.com/r/Intune/comments/1t63m0q/intune_enhanced_app_inventory/)** _(Reddit)_ - Multiple admins confirm the /deviceInventories endpoint is inaccessible via Graph Explorer and PowerShell with no official workaround, blocking automation built around the newly shipped feature.
- **[M365 suites gaining Intune Plan 2 and Remote Help mid-June](https://mc.merill.net/message/MC1304290)** _(Microsoft - Message Center)_ - Intune Remote Help, Advanced Analytics, and Plan 2 capabilities begin rolling into Microsoft 365, Office 365, and EMS suites from mid-June, requiring licensing and budget review before rollout completes August 1.

---

## In this edition

**Landing in your tenant soon**

- [Outlook for iOS/Android: Admins Can Allow Users to Override Default Compose Font](https://mc.merill.net/message/MC1303717)
- [Intune Data Warehouse Beta Connector Retiring in Power BI](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [M365 2026 Packaging Update Brings Intune Remote Help, Advanced Analytics, and Plan 2 Features to More Suites](https://mc.merill.net/message/MC1304290)

**On the horizon**

- [Android Enterprise Personally Owned Work Profile Migrating to Android Management API (AMAPI)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Controlled Configuration for Microsoft Defender Antivirus Settings (Public Preview)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Strict Tunnel Mode for Microsoft Tunnel on Android Enterprise (AMAPI)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Device Control Policy Support Extended to Defender for Endpoint Security Settings Management](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Multiple Managed Accounts for App Protection Policies (iOS/Android)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Enrollment Time Grouping for Apple ADE Policies Going GA](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Platform SSO Registration During macOS Automated Device Enrollment](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Custom Compliance Settings Coming to macOS](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Client-Driven Compliance Evaluation for Windows (Preview)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [In-Place Renewal for Cloud PKI Issuing CAs](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [STIG Audit Security Baseline for GCC High Tenants](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Scope Tags Support for Endpoint Privilege Management Reports](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Agentic Identity for the Intune Policy Configuration Agent (Public Preview)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Grant Enhanced MTD Security Permissions on Android Enterprise](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Silence Apps on Managed Home Screen During Authentication Prompts](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [New Wired Networks (802.1x) Profile for iOS/iPadOS](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Disable MAC Address Randomization on macOS Wi-Fi Profiles](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Block Bluetooth Sharing Setting Added to Android Enterprise Settings Catalog](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)

**Action required**

- [Microsoft Tunnel Servers on Version 20260129.1 Are Stuck - Reinstall or Run Patch Script](https://techcommunity.microsoft.com/t5/intune-customer-success/known-issue-upgrading-microsoft-tunnel-version-20260129-1/ba-p/4517935)
- [Intune Data Warehouse Beta Connector in Power BI: Migrate Before Retirement Completes](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [BYOD Devices Blocked from Windows 365 Cloud PC by Conditional Access - No Clean Exclusion Path](https://techcommunity.microsoft.com/t5/microsoft-intune/byod-devices-can-t-launch-windows-365-pc-because-of-device/m-p/4518584#M23436)

**What shipped**

- [New Intune Device Page Now in Public Preview](https://www.reddit.com/r/Intune/comments/1t99b0c/check_out_the_new_intune_device_view/)
- [Enhanced App Inventory with Faster Data Updates Now Available](https://zerotruststories.com/how-to-use-microsoft-intune-enhanced-app-inventory-for-advanced-insights/)
- [Support Tip Published: Resolving Device Noncompliance with MTD Partner Apps](https://techcommunity.microsoft.com/t5/intune-customer-success/support-tip-resolve-device-noncompliance-with-mobile-threat/ba-p/4491669)
- [Firewall and Proxy Configuration Guide for Windows Update Published](https://techcommunity.microsoft.com/blog/windows-itpro-blog/configuring-firewall-and-proxies-for-smooth-windows-updates/4517913)
- [Open Intune Baseline 3.8 Released](https://github.com/SkipToTheEndpoint/OpenIntuneBaseline/releases/tag/windows-v3.8)

**From the field**

- [Enhanced App Inventory Graph API Endpoint Returning Access Errors](https://www.reddit.com/r/Intune/comments/1t63m0q/intune_enhanced_app_inventory/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-12/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
