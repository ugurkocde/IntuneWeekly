# Intune Weekly - Edition 5
_Covering May 19 - 25, 2026_

BitLocker loops return, passkeys bypassed by AiTM, and scripts reporting still broken.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-26/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## On the radar this week

- **[BitLocker Recovery Loop After May KB5089549](https://www.reddit.com/r/Intune/comments/1tik9fl/bitlocker_issues_with_kb5089549/)** _(Reddit)_ - Windows 11 devices are looping on the BitLocker recovery screen after every reboot post-patch - HP has a firmware workaround but admins need to act before wider deployment.
- **[Passkeys Not Blocking AiTM Session Token Theft](https://www.reddit.com/r/sysadmin/comments/1tklvyg/intuneazure_passkeys_now_compromised_in_addition/)** _(Reddit)_ - Confirmed compromises show phishing-resistant MFA alone doesn't stop session hijacking - admins should add token protection and Continuous Access Evaluation policies now.
- **[Remediation Script Reporting Still Stale Post-Outage](https://www.reddit.com/r/Intune/comments/1tkm0t4/monitoring_and_remediation_script_results_not/)** _(Reddit)_ - Console results are still showing May 16–17 timestamps days after recovery, so any compliance or operational decisions based on console data are unreliable until Microsoft closes the investigation.
- **[Low Telemetry Hides Devices from Secure Boot Report](https://www.reddit.com/r/Intune/comments/1tk9hg2/switched_telemetry_to_full_for_secure_boot_cert/)** _(Reddit)_ - Devices on 'Security' telemetry level are completely invisible to the Secure Boot certificate report, meaning admins may be miscounting compliance exposure ahead of the certificate rollout deadline.
- **[Remote Help & Advanced Analytics Rolling Into M365 Suites](https://mc.merill.net/message/MC1304290)** _(Microsoft - Message Center)_ - Starting mid-June, these premium add-on features begin landing automatically in M365/EMS SKUs - admins should review licensing now to avoid surprise capacity or configuration gaps.

---

## In this edition

**Landing in your tenant soon**

- [Remote Help and Intune Advanced Analytics Coming to M365 / EMS Suites in Mid-June](https://mc.merill.net/message/MC1304290)

**On the horizon**

- [Admin Insights for Windows 365 Now in Public Preview](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/admin-insights-for-windows-365-stay-on-top-of-what-needs/ba-p/4517570)

**Action required**

- [Remediation and Platform Scripts Reporting Broken - Multi-Tenant Outage Now Resolved](https://www.reddit.com/r/Intune/comments/1timxi3/platform_scripts_all_returning_404not_found_errors/)

**What shipped**

- [Updated Secure Boot Status Report Now Live in Windows Autopatch](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/updated-secure-boot-status-report-in-windows-autopatch/ba-p/4517920)
- [Batch of In-Development Features Removed - Likely Shipped or Cancelled](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)

**From the field**

- [BitLocker Recovery Loop Returns After May KB5089549 - Worse Than April's KB5083769](https://www.reddit.com/r/Intune/comments/1tik9fl/bitlocker_issues_with_kb5089549/)
- [Telemetry Level Affects Secure Boot Certificate Report Visibility](https://www.reddit.com/r/Intune/comments/1tk9hg2/switched_telemetry_to_full_for_secure_boot_cert/)
- [Passkeys Not Stopping Session Token Theft via AiTM Attacks](https://www.reddit.com/r/sysadmin/comments/1tklvyg/intuneazure_passkeys_now_compromised_in_addition/)
- [Remediation Script Console Reporting Still Delayed Days After Outage Recovery](https://www.reddit.com/r/Intune/comments/1tkm0t4/monitoring_and_remediation_script_results_not/)
- [Microsoft Store App Deployment Fails Reporting When Store Access Is Blocked by Policy](https://www.reddit.com/r/Intune/comments/1tnqa5o/intune_microsoft_store_app_deployment_fails/)
- [SCCM-to-Intune Migration Framework Automates Autopilot Import - 6.5 Hours to 30 Minutes](https://www.reddit.com/r/Intune/comments/1thurqe/built_a_framework_for_sccmtointune_migration_that/)
- [Driver Automation Tool v10 Seeking Community Feedback](https://www.reddit.com/r/Intune/comments/1tld2as/driver_automation_tool_feedback/)
- [94 Personal Devices Enrolled Despite BYOD Policy - Enforcement Gap Pattern](https://www.reddit.com/r/Intune/comments/1thjuwk/we_have_a_byod_policy_that_says_personal_devices/)
- [Windows Hello for Business Cloud Kerberos Trust Fails on Hybrid-Joined Devices](https://www.reddit.com/r/Intune/comments/1tis2jb/windows_hello_for_business/)
- [Dark Mode QR Code Bug: Enrollment Token QR Codes Won't Scan in Dark Mode](https://www.reddit.com/r/Intune/comments/1tklsr9/intune_admin_center_supported_dark_mode_all_this/)
- [LAPS for macOS Intermittently Failing - Username Case Sensitivity Is a Factor](https://www.reddit.com/r/Intune/comments/1tn4mc7/laps_for_macos_not_working/)
- [Dell BIOS/Firmware Management via Intune: DCU + Autopatch Approaches Compared](https://www.reddit.com/r/Intune/comments/1tio4ma/how_are_you_keeping_the_bios_up_to_date_for_your/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-26/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
