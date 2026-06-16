# Intune Weekly - Edition 8
_Covering June 9 - 15, 2026_

Kerberos RC4 deadline looms, KB5094126 breaks HP devices, and Intune Devices blade goes dark.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-16/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**Florian Salzmann & Jannik Reinhard** - _CMTrace.dev - log viewer in your browser_
A free, zero-install log viewer for ConfigMgr, SCCM, and Intune. Open massive client logs, color-code severity, and chase down error codes - all in the browser, with files processed 100% locally so nothing leaves your machine. [Read more](https://cmtrace.dev/)

## On the radar this week

- **[Kerberos RC4 Enforcement: 30-Day Remediation Deadline](https://support.microsoft.com/topic/1ebcda33-720a-4da8-93c1-b0496e1910dc)** _(Microsoft - Release Health)_ - July 2026 Windows security updates permanently remove Audit mode - any remaining RC4 dependencies will cause authentication failures the moment the update applies.
- **[KB5094126 Causing BSODs and Boot Failures on HP Devices](https://www.reddit.com/r/Intune/comments/1u5er12/updatenightmare/)** _(Reddit)_ - The June 2026 cumulative update is actively breaking HP ProBook/EliteBook fleets with boot failures, BitLocker recovery prompts, and EFI partition issues - admins should pause update rings for HP devices now.
- **[Intune Devices Blade Outage Across Multiple Regions](https://www.reddit.com/r/Intune/comments/1u7anmf/intune_devices_blade_down_uk/)** _(Reddit)_ - The Devices blade was confirmed unavailable on 16 June across UK, Austria, Netherlands, and Brazil - admins should monitor Service Health for an incident ID and verify console access is restored.
- **[Microsoft Tunnel v20260129.1 Stuck - Remediation Script Out](https://techcommunity.microsoft.com/t5/intune-customer-success/known-issue-upgrading-microsoft-tunnel-version-20260129-1/ba-p/4517935)** _(Blog - Customer Success)_ - Servers on this version are stalling mid-upgrade and need Microsoft's mstunnel-patch-2602 script or a full reinstall to restore tunnel functionality.
- **[Controlled Configuration for Defender Antivirus (Preview)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)** _(Microsoft - In Development)_ - This upcoming feature will override Group Policy, ConfigMgr, and local changes to Defender settings - co-managed environments need to review governance implications before it lands.

---

## In this edition

**Landing in your tenant soon**

- [Kerberos RC4 Enforcement Mode Arrives with July 2026 Windows Security Update](https://support.microsoft.com/topic/1ebcda33-720a-4da8-93c1-b0496e1910dc)
- [Enrollment Time Grouping for Apple ADE Policies Goes GA](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Intune Data Warehouse (Beta) Power BI Connector Retirement Begins](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Scope Tags Now Respected in EPM Reports](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Device Control Policy Support Extends to MDE Security Settings Management](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Maintenance Window for Windows Update for Business Now GA](https://www.reddit.com/r/Intune/comments/1u38h9w/maintenance_window_is_now_ga_for_windows_update/)

**On the horizon**

- [Android Personally Owned Work Profile Devices Migrate to Android Management API (AMAPI)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Controlled Configuration for Defender Antivirus Settings (Public Preview)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Strict Tunnel Mode for Microsoft Tunnel on Android Enterprise](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Multiple Managed Accounts for App Protection Policies (iOS and Android)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Client-Driven Compliance Evaluation for Windows Devices (Preview)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [In-Place Renewal for Cloud PKI Issuing Certification Authorities](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Agentic Identity for the Policy Configuration Agent (Public Preview)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Custom Compliance Settings Coming to macOS](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Grant Enhanced MTD Security Permissions on Android Enterprise](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Silence Apps on Managed Home Screen During Authentication Prompts (Android)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Block Bluetooth Sharing Setting Added to Android Enterprise Settings Catalog](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Disable MAC Address Randomization on macOS Wi-Fi Profiles](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [802.1x Wired Networks Profile Coming to iOS/iPadOS](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [STIG Audit Security Baseline for GCC High Tenants](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)

**Action required**

- [Microsoft Tunnel Servers on Version 20260129.1 Are Stuck - Remediation Script Available](https://techcommunity.microsoft.com/t5/intune-customer-success/known-issue-upgrading-microsoft-tunnel-version-20260129-1/ba-p/4517935)
- [Kerberos RC4 Enforcement Deadline: Remediate RC4 Dependencies Before July 2026 Update](https://support.microsoft.com/topic/1ebcda33-720a-4da8-93c1-b0496e1910dc)
- [Intune Devices Blade Outage Reported Across Multiple Regions](https://www.reddit.com/r/Intune/comments/1u7anmf/intune_devices_blade_down_uk/)

**What shipped**

- [June 2026 Windows Security Update (KB5094126) Now Available](https://support.microsoft.com/help/5094126)
- [Enterprise App Management: Security Architecture Deep-Dive Published](https://techcommunity.microsoft.com/t5/intune-customer-success/how-enterprise-app-management-secures-your-app-catalog-from/ba-p/4528361)

**From the field**

- [KB5094126 Causing Boot Failures, BSODs, BitLocker Recovery, and HP EFI Partition Issues](https://www.reddit.com/r/Intune/comments/1u5er12/updatenightmare/)
- [HP EFI Partition (100 MB) Causing Recurring Windows Update Failures](https://www.reddit.com/r/Intune/comments/1u5esc9/increase_size_of_efi_with_a_script/)
- [CanReset Value Randomly Flipping on Passwordless Cloud-Only Windows 11 Devices](https://techcommunity.microsoft.com/t5/microsoft-intune/canreset-value-flipping-on-cloud-only-devices/m-p/4527692#M23539)
- [Secure Boot CA 2023 Rollout: Confidence Level Confusion and What "Under Observation" Actually Means](https://www.reddit.com/r/Intune/comments/1u185pl/are_we_good_with_the_new_secure_boot_certificate/)
- [Secure Boot CA 2023 Expiry Behaviour for Offline and Non-SB Devices Clarified by Community](https://www.reddit.com/r/sysadmin/comments/1u69v44/secure_boot_ca_2023_update_deadline_approaching/)
- [Browser-Based CMTrace Log Viewer (cmtrace.dev) Built for Autopilot ESP Troubleshooting](https://www.reddit.com/r/Intune/comments/1u25c20/we_built_a_browserbased_cmtrace_because_we_needed/)
- [Browser-Based Registry-to-Remediation Script Generator](https://www.reddit.com/r/Intune/comments/1u1tdhs/easily_modify_registry_keys_with_intune/)
- [Edge Extension Inventory Script Sending Data to Azure Log Analytics](https://www.reddit.com/r/Intune/comments/1u298dr/built_a_simple_edge_extension_inventory_script/)
- [Windows App (Remote Desktop) Update Notification Requiring User Interaction - No Silent Update Option Found](https://techcommunity.microsoft.com/t5/microsoft-intune/windows-app-update-notification/m-p/4526926#M23536)
- [WDAC and Adobe Acrobat Update Compatibility Causing Consistent Failures](https://www.reddit.com/r/Intune/comments/1u39nsk/acrobat_and_wdachow/)
- [SCCM-to-Intune Migration: Real-World Gotchas from Admins Making the Switch](https://www.reddit.com/r/Intune/comments/1u6sp5f/just_spinning_up_our_intune_pilot_any_gotchas_or/)
- [Free Two-Part PowerShell Webinar Series for Intune/ConfigMgr Admins (June 23 and 30)](https://www.reddit.com/r/Intune/comments/1u2dj25/free_powershell_webinar_series_with_microsoft/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-16/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
