# Intune Weekly - Edition 10
_Covering June 23 - 29, 2026_

MAA breaks automation, BitLocker hits HP devices, and Intune Suite lands in E3/E5 tenants.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-30/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**Mert Ozsoy** _(@mertozsoy)_ - _IntuneWin32AppUninstall_
A PowerShell GUI tool that scans the Windows Registry for MSI-installed applications and automatically generates Microsoft Intune-compatible Detection and Remediation scripts, so admins can build clean Win32 app uninstall logic without hand-writing the detection rules. [Read more](https://github.com/mertozsoy/IntuneWin32AppUninstall)

## On the radar this week

- **[Multi Admin Approval Breaking Graph API Automation](https://patchmypc.com/blog/intune-multi-admin-approval-the-x-msft-approval-justification-error/)** _(Blog - Intune)_ - Any service principal or runbook making Intune or Entra Graph write calls will fail with an approval error this week unless you explicitly exclude the app registration - audit and fix before production breaks.
- **[BitLocker Recovery Loops on HP EliteDesk After KB5094126](https://www.reddit.com/r/Intune/comments/1uelb1x/bitlocker_prompt_issue_post_june_2026_monthly/)** _(Reddit)_ - The June Secure Boot certificate update is forcing BitLocker recovery prompts on HP EliteDesk 800 G6 devices - hold broad patch deployment and prioritise BIOS 2.26 updates on affected models now.
- **[Intune Suite Live in E3/E5 Tenants - Remote Help July 1](https://www.reddit.com/r/Intune/comments/1uf9zpz/intune_suite_is_live_in_our_tenant_go_check_yours/)** _(Reddit)_ - Intune Suite capabilities including Remote Help are already activating in some tenants ahead of the July 1 cutover, so admins should configure and communicate the change to help desk teams this week.
- **[Legacy Apple MDM Update Policies Retiring - Migrate to DDM](https://techcommunity.microsoft.com/t5/intune-customer-success/microsoft-intune-and-apple-platform-updates-what-to-expect-after/ba-p/4531058)** _(Blog - Customer Success)_ - Legacy MDM software update workloads will be removed from the Intune UI when macOS/iOS 27 ships, and the beta cycle is open now - waiting until GA will leave you without update control.
- **[New Wipe UI Causing Accidental Single Wipes](https://www.reddit.com/r/Intune/comments/1ugdtbj/wipe_command_in_new_intune_ui/)** _(Reddit)_ - The redesigned device page's radio-button wipe flow has already caused multiple admins to issue Single Wipe (enrollment preserved) when intending a full wipe - brief your team before anyone runs a wipe command this week.

---

## In this edition

**Landing in your tenant soon**

- [Intune Suite Add-ons Rolling Into M365 E3/E5 Tenants - Remote Help Arrives July 1](https://www.reddit.com/r/Intune/comments/1uf9zpz/intune_suite_is_live_in_our_tenant_go_check_yours/)
- [macOS and iOS/iPadOS Minimum Version Bump Tied to Fall OS 27 Release](https://mc.merill.net/message/MC1403402)
- [Windows Security Baseline 25H2 Updated: New IE11 COM Automation Block Setting](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)

**On the horizon**

- [EPM Expanding to System-Level Network Configuration and Time Sync](https://patchmypc.com/blog/intune-epm-system-settings-network-and-time-sync-elevation/)
- [Controlled Configuration for Defender Antivirus: Intune Becomes Single Source of Truth](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Device Control Policy Support Extended to Defender for Endpoint Security Settings Management](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Custom Compliance Settings Coming to macOS](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Client-Driven Compliance Evaluation for Windows to Reduce Reporting Lag](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Agentic Identity for the Policy Configuration Agent](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Scope Tags Support for EPM Reports](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Intune Planning for Apple OS 27 - Legacy MDM Update Policies Being Retired](https://techcommunity.microsoft.com/t5/intune-customer-success/microsoft-intune-and-apple-platform-updates-what-to-expect-after/ba-p/4531058)
- [Windows Server 2022 Hotpatch Support Extended to October 2027](https://learn.microsoft.com/en-us/lifecycle/products/windows-server-2022)
- [Point-in-Time Restore for Windows 11 Now Generally Available](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/point-in-time-restore-for-windows-11-is-now-generally-available/ba-p/4508101)

**Action required**

- [Multi Admin Approval Now Enforcing on Graph API Write Calls - Automation Will Break](https://patchmypc.com/blog/intune-multi-admin-approval-the-x-msft-approval-justification-error/)
- [Intune Data Warehouse Beta Connector Deprecation in Power BI](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Secure Boot Certificate Update (KB5094126) Triggering BitLocker Recovery on Some HP Devices](https://www.reddit.com/r/Intune/comments/1uelb1x/bitlocker_prompt_issue_post_june_2026_monthly/)

**What shipped**

- [Enterprise App Management Auto-Update and GCC High/DoD Support Now GA](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [macOS PKG Available Apps Now Auto-Update Without User Interaction](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Remote Help Now Supports RemoteApp Sessions in Azure Virtual Desktop](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Updated Security Baseline for Microsoft 365 Apps for Enterprise (v2512)](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [New Android Enterprise Settings Catalog Entries: AI Agent Function Blocking, Bluetooth Sharing Block, and More](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [WPA3-Personal Now Supported in iOS/iPadOS Wi-Fi Profiles](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Microsoft Tunnel Adds RHEL 9.7 Support](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [New Defender Antivirus Settings for Linux Server: Offline Intelligence Updates and Scheduled Scans](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Trustd Mobile Now Supported as an Intune MTD Partner](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Self-Service Onboarding for MDM Compliance Partners Now Available](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [ChatGPT Added as an Intune Protected App](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [macOS Privacy Preferences Policy Control (PPPC) Now Configurable via Settings Catalog](https://techcommunity.microsoft.com/t5/intune-customer-success/how-to-configure-macos-privacy-preferences-policy-control-pppc/ba-p/4530406)
- [Best Practices Published for Secure Boot Certificate Deployment](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/best-practices-for-deploying-secure-boot-certificate-updates/ba-p/4529884)

**From the field**

- [New Intune Device Page UI Makes Wipe Workflow Confusing - Admins Accidentally Running Single Wipe](https://www.reddit.com/r/Intune/comments/1ugdtbj/wipe_command_in_new_intune_ui/)
- [Platform Scripts Showing 0 Targeted Devices Despite Healthy IME and Entra Join](https://techcommunity.microsoft.com/t5/microsoft-intune/intune-platform-scripts-never-target-devices-0-targeted-devices/m-p/4531649#M23557)
- [Intune Suite First Impressions: Cloud PKI and EPM Praised, Enterprise App Catalog and Remote Help Draw Criticism](https://www.reddit.com/r/Intune/comments/1uhwf57/microsoft_just_announced_system_level_network/)
- [Enterprise App Catalog in Production: No Running Process Handling, Pricing vs. Patch My PC Debate](https://www.reddit.com/r/Intune/comments/1uix2ed/enterprise_app_catalog_first_look/)
- [WHfB Cloud Kerberos Trust Provisioning Failures on Hybrid-Joined Windows 11 24H2](https://www.reddit.com/r/sysadmin/comments/1ujihy0/errors_with_pin_login_and_windows_hello_for/)
- [M365 WebView2 Traffic Bypassing Delivery Optimization - Now in Microsoft Product Group Backlog](https://www.reddit.com/r/sysadmin/comments/1udm4ch/m365s_webview2_problem_is_now_sitting_in_the/)
- [Autopilot Devices Reverting to Previous Company's Branding After Reset](https://www.reddit.com/r/Intune/comments/1ug3ywr/device_reverting_to_previous_business_after_reset/)
- [Winget System Context Installs Failing Without Explicit Source Configuration](https://www.reddit.com/r/Intune/comments/1ueczb0/packaging_apps_using_winget/)
- [Token Theft in Higher Education: Conditional Access Options When Devices Cannot Be Managed](https://www.reddit.com/r/sysadmin/comments/1ug8q7y/how_do_yall_stop_token_theft_in_education/)
- [Curated aka.ms / cmd.ms Shortcut Reference for Intune, Entra, and Defender Admins](https://www.reddit.com/r/entra/comments/1uh5a5d/i_horde_akams_shortcuts/)
- ["Preparing Windows" Delays on First Login in Shared Healthcare Environments](https://www.reddit.com/r/sysadmin/comments/1ue8n8q/speed_up_preparing_windows_screen/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-30/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
