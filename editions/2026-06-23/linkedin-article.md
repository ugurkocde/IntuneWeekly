# Intune Weekly - Edition 9
_Covering June 16 - 22, 2026_

Intune Suite rolls into E3/E5, IME breaks WDAC, and Win32 app delivery goes HTTPS-only.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-23/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## Community shoutout

**Nick Benton** _(@ennnbeee)_ - _IntuneOSCompliance_
A PowerShell tool that automatically updates operating-system-based compliance policies and app protection policies to track the latest supported Windows, Android, and Apple OS releases. Optionally posts a rich Microsoft Teams card to an Incoming Webhook with the results of each run, so admins stay current without hand-editing minimum OS versions. [Read more](https://github.com/ennnbeee/IntuneOSCompliance)

## On the radar this week

- **[IME Update Blocked by WDAC - Autopilot Enrollment Failures](https://www.reddit.com/r/Intune/comments/1u7ymim/psa_new_update_to_ime_is_bieng_blocked_by_wdac/)** _(Reddit)_ - A new runtime DLL in IME versions 1.99.101.0–1.101.103.0 is not covered by existing WDAC policies, actively breaking Autopilot provisioning across affected tenants with no official fix yet.
- **[Win32 App Delivery HTTPS-Only - MCC Nodes Must Be Updated](https://techcommunity.microsoft.com/t5/intune-customer-success/how-to-enable-https-support-for-microsoft-connected-cache-for/ba-p/4496173)** _(Microsoft - Learn)_ - As of June 16, unupdated Microsoft Connected Cache nodes silently fall back to direct internet download for all Win32 apps, negating bandwidth savings until nodes are patched.
- **[Advanced Intune Suite Features Rolling into M365 E3/E5 July 1](https://techcommunity.microsoft.com/t5/microsoft-intune-blog/microsoft-365-adds-advanced-microsoft-intune-solutions-at-scale/ba-p/4474272)** _(Microsoft - Message Center)_ - EPM, Remote Help, Cloud PKI, and EAM begin lighting up for eligible EMS E3/ME3/ME5 tenants now, but rollout is uneven - admins should validate which features are live and which are still blocked before July 1.
- **[M365 Apps Policy Config Removed from Intune Admin Center in June 2606](https://mc.merill.net/message/MC1330892)** _(Microsoft - Message Center)_ - The June 2606 service release removes the M365 Apps policy page from the Intune admin center entirely, redirecting to the Apps admin center - admins must migrate workflows and bookmarks before the release lands.
- **[CapabilityAccessManager.db-wal Ballooning to 70 GB on Windows Devices](https://www.reddit.com/r/sysadmin/comments/1u8n7f5/capability_access_manager_db_growing_out_of_control/)** _(Reddit)_ - A never-closed SQLite read transaction is causing this WAL file to grow until C: drives fill completely; safe-mode deletion is the only current remediation and no Microsoft fix is confirmed.

---

## In this edition

**Landing in your tenant soon**

- [Advanced Intune Suite Features Roll into Microsoft 365 E3/E5 Starting July 1](https://techcommunity.microsoft.com/t5/microsoft-intune-blog/microsoft-365-adds-advanced-microsoft-intune-solutions-at-scale/ba-p/4474272)
- [M365 Apps Policy Configuration Moving Out of Intune Admin Center](https://mc.merill.net/message/MC1330892)
- [Windows 11 26H2 Approaching - Begin Staged Rollout Planning Now](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/get-ready-for-windows-11-version-26h2/ba-p/4529367)
- [Updated Security Baseline for Microsoft 365 Apps for Enterprise (v2512) Coming](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)

**On the horizon**

- [Auto-Update for Enterprise App Management Applications](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Enterprise App Management Expanding to GCC High and DoD](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Mark Windows Devices Noncompliant When Prohibited AI Agents Are Detected](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Enforce Routes Support for iOS/iPadOS and macOS VPN Profiles](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [WPA3-Personal Support Coming to iOS/iPadOS Wi-Fi Profiles](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [New Android Enterprise Settings Catalog Additions](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Audit Mode for Microsoft Defender Antivirus on Linux](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Remote Help Support for RemoteApp in Azure Virtual Desktop](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Vulnerability Remediation Agent for Security Copilot Now in Public Preview](https://techcommunity.microsoft.com/t5/intune-customer-success/triage-vulnerabilities-with-the-vulnerability-remediation-agent/ba-p/4528646)

**Action required**

- [Intune Win32 App Delivery Now HTTPS-Only - Update Microsoft Connected Cache Nodes](https://techcommunity.microsoft.com/t5/intune-customer-success/how-to-enable-https-support-for-microsoft-connected-cache-for/ba-p/4496173)
- [Secure Boot Certificate Updates Required for Linux on Azure VMs](https://support.microsoft.com/topic/secure-boot-certificate-updates-for-linux-on-azure-virtual-machines-df51ba85-4e1e-4eda-b1d8-f0881970e997)
- [MDOP Reached End of Support April 14 - Migrate to Intune-Native Alternatives](https://techcommunity.microsoft.com/t5/intune-customer-success/mdop-is-out-of-support-what-to-do-next-with-microsoft-intune/ba-p/4526024)

**What shipped**

- [Platform SSO with Registration During ADE on macOS Now Generally Available](https://techcommunity.microsoft.com/t5/intune-customer-success/new-platform-sso-with-registration-during-automated-device/ba-p/4519846)
- [Large Wave of In-Development Features Shipped or Removed from Pipeline](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Microsoft 365 Packaging Update Begins Rolling Out - Suite Features in New Bundles](https://mc.merill.net/message/MC1304290)
- [Graph API: Exporting EAM Catalog Apps to CSV](https://techcommunity.microsoft.com/t5/intune-customer-success/exporting-all-microsoft-intune-enterprise-app-management-catalog/ba-p/4529579)
- [Platform SSO for Pre-macOS 26: Lessons Learned from Microsoft's Internal Deployment](https://techcommunity.microsoft.com/t5/intune-customer-success/deploying-platform-sso-for-pre-macos-26-with-microsoft-intune-lessons-learned/ba-p/4521368)
- [Enterprise App Management Security Architecture Deep-Dive Published](https://techcommunity.microsoft.com/t5/intune-customer-success/how-enterprise-app-management-secures-your-app-catalog-from/ba-p/4528361)

**From the field**

- [IME Update Blocked by WDAC During Autopilot - Enrollment Failures Reported](https://www.reddit.com/r/Intune/comments/1u7ymim/psa_new_update_to_ime_is_bieng_blocked_by_wdac/)
- [Graph API 500 Error on BIOS Password Hardware Details Endpoint](https://www.reddit.com/r/Intune/comments/1uczctm/graph_and_bios_passwords/)
- [Company Portal "Error Loading Apps" Outage Hits EU Region](https://www.reddit.com/r/Intune/comments/1u9w0yj/company_portal_issues/)
- [Windows Quality Update Report Showing False "Not Up to Date" for Deferred Devices](https://www.reddit.com/r/Intune/comments/1u8gff3/windows_quality_updates_report_looks_shocking_now/)
- [E3/E5 Intune Suite Feature Rollout Uneven - Some Features Still Blocked](https://www.reddit.com/r/Intune/comments/1u8937s/e3e5_intune_changes_started/)
- [Eligibility Confusion Around E3/E5 Intune Suite Inclusion - No Seat Minimum, EMS SKU Is the Key](https://www.reddit.com/r/Intune/comments/1u9yty4/microsoft_confirms_intune_suite_features_are/)
- [CapabilityAccessManager.db-wal Ballooning to 10–70 GB on Managed Windows Devices](https://www.reddit.com/r/sysadmin/comments/1u8n7f5/capability_access_manager_db_growing_out_of_control/)
- [Autopilot Enrollment Security Gap: Devices Can Bypass OOBE and Avoid MDM Enrollment](https://www.reddit.com/r/Intune/comments/1u81k6p/is_there_a_way_to_enforce_autopilotmdm_enrollment/)
- [Autopatch Quality Update Report Marks Deferred Devices as Non-Compliant](https://techcommunity.microsoft.com/t5/microsoft-intune/intune-autopatch-reports-expected-behavior/m-p/4529521#M23547)
- [Intune Reporting Lag and Compliance Gaps: How Admins Are Coping](https://www.reddit.com/r/Intune/comments/1uccp53/how_do_you_live_with_intunes_reporting_lag_and/)
- [Community Tool Roundup: Third-Party App Patching Alternatives to PMPC](https://www.reddit.com/r/Intune/comments/1uc9e6j/advice_needed_switching_from_pmpc/)
- [Deploying Claude Desktop App via Intune - Community-Sourced Methods](https://www.reddit.com/r/Intune/comments/1u96dss/claude_app_deployment_via_intune/)
- [Deploying HEIC/HEVC Extensions on Windows via Intune](https://www.reddit.com/r/Intune/comments/1ub3vgz/open_heic_images_on_windows/)
- [Secure Boot Cert Rollout: Handling Pre-Staged Laptops in Storage](https://www.reddit.com/r/Intune/comments/1u7hfyd/secure_boot_cert_concerns/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-06-23/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
