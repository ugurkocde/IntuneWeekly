# Intune Weekly - Edition 2
_Covering April 28 - May 4, 2026_

Hotpatch on by default, Secure Boot deadline looms, and Autopilot stalls hit production.

**[Download the full PDF →](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-05/intune-weekly.pdf)**

**[Subscribe on LinkedIn →](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)** to get the next edition every Tuesday

---

## On the radar this week

- **[Secure Boot Certs Expire June 2026 - Remediate Now](https://www.reddit.com/r/Intune/comments/1syunmi/secureboot_certificate_updates_realitycheck/)** _(Reddit)_ - Unremediated devices will silently stop receiving boot manager updates and may trigger BitLocker recovery prompts - the June deadline leaves little runway for large inventories.
- **[Hotpatch Flipped On Tenant-Wide - May Is First Affected Month](https://techcommunity.microsoft.com/blog/Windows-ITPro-blog/securing-devices-faster-with-hotpatch-updates-on-by-default/4500066/replies/4516455)** _(Microsoft - Message Center)_ - Microsoft silently enabled Hotpatch for all tenants in April, meaning newly enrolled devices will receive hotpatch instead of a full CU starting in May - admins must configure exclusion groups now for any devices that should not receive hotpatches.
- **[Autopilot Pre-Provisioning Stalling at App Install Phase](https://www.reddit.com/r/Intune/comments/1t3saxx/autopilot_pre_provisioning_stuck_at_app_installs/)** _(Reddit)_ - Multiple admins are hitting this in production today with no config changes on their end, and the only unblock requires a force-reboot - active issue to watch before scheduling any provisioning runs this week.
- **[Conditional Access Filter Now Hitting Windows Server RDP Sessions](https://techcommunity.microsoft.com/t5/microsoft-intune/policy-applied-allthough-it-shouldn-t/m-p/4516937#M23417)** _(Blog - Discussions)_ - A backend CA evaluation change is causing policies that should exclude company-owned devices to incorrectly apply to Windows Server 2025 RDP sessions, forcing unexpected 8-hour reauthentication - admins with device-filter CA policies should audit scope immediately.
- **[April 2026 Non-Security Preview: Dynamic App Removal + Secure Boot Side-Effect](https://support.microsoft.com/help/5083631)** _(Microsoft - Release Health)_ - This update delivers the new dynamic MSIX/APPX removal capability but also carries the KB5082052 Secure Boot cert prompt side-effect - admins should read the known issue before pushing to pilot rings.

---

## In this edition

**Landing in your tenant soon**
- [Hotpatch Enabled Tenant-Wide by Default - May Updates Are First Affected](https://techcommunity.microsoft.com/blog/Windows-ITPro-blog/securing-devices-faster-with-hotpatch-updates-on-by-default/4500066/replies/4516455)
- [April 2026 Windows Non-Security Preview Update Now Available](https://support.microsoft.com/help/5083631)

**On the horizon**
- [Dynamic App Removal for Managed Windows 11 Devices](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/dynamically-remove-apps-from-managed-windows-11-devices/ba-p/4516291)
- [Windows 365 for Agents Now in Public Preview](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/windows-365-for-agents-now-in-public-preview-run-ai-agents/ba-p/4513479)
- [User-Initiated Provisioning for Windows 365 Reserve Now in Public Preview](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/public-preview-user-initiated-provisioning-for-windows-365/ba-p/4512474)

**Action required**
- [Secure Boot Certificates Expire June 2026 - Intune-Managed Device Remediation Underway](https://www.reddit.com/r/Intune/comments/1syunmi/secureboot_certificate_updates_realitycheck/)

**What shipped**
- [April 2026 Intune Service Update - Higher-Frequency App Inventory, Linux SSO, Apple Enrollment Expansion](https://techcommunity.microsoft.com/t5/microsoft-intune-blog/what-s-new-in-microsoft-intune-april/ba-p/4493135)
- [New Windows Autopatch Overview Report Now Available for All Tenants](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/protect-your-estate-reassess-your-windows-update-policies/ba-p/4515228)
- [Multiple Features Drop Off In-Development List - Likely Shipped in April Service Update](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Microsoft Confirms Intune Policy Sync Is Far Faster Than the "8-Hour" Myth](https://techcommunity.microsoft.com/t5/intune-customer-success/speed-where-it-matters-how-microsoft-intune-helps-it-prioritize/ba-p/4515942)
- [Frontline Device Migration Guidance: Stakeholder Alignment Before Testing](https://techcommunity.microsoft.com/t5/intune-customer-success/migrating-frontline-mobile-devices-aligning-stakeholders-before/ba-p/4516511)

**From the field**
- [Conditional Access Filter Behavior Changing - Server Devices Now Getting Sign-In Policies They Shouldn't](https://techcommunity.microsoft.com/t5/microsoft-intune/policy-applied-allthough-it-shouldn-t/m-p/4516937#M23417)
- [Autopilot Pre-Provisioning Intermittently Stalling at App Install Phase](https://www.reddit.com/r/Intune/comments/1t3saxx/autopilot_pre_provisioning_stuck_at_app_installs/)
- [App Enforced Restrictions Not Enforcing on Chrome for BYOD macOS](https://techcommunity.microsoft.com/t5/microsoft-intune/app-enforced-restrictions-not-working-on-chrome/m-p/4516309#M23409)
- [Autopilot Profile Assignment Breaks When Moving from "All Devices" to Dynamic Group](https://www.reddit.com/r/Intune/comments/1t2f8mq/autopilot_profile_assignment_issues_after_moving/)
- [Hybrid Join Producing Double Entra Entries After Device Reset](https://www.reddit.com/r/Intune/comments/1szupgk/hybrid_join_and_intune_double_entity_problem/)
- [WinGet App Deployment via Intune Consistently Failing for Many Admins](https://www.reddit.com/r/Intune/comments/1t4asyd/does_anyone_have_a_system_using_winget_to_install/)
- [Community Tool: PIM Multi-Role Activation GUI for Intune Admins](https://www.reddit.com/r/Intune/comments/1t0eins/pim_multirole_activation/)
- [Community Tool: Central Intune Reporting Dashboard in Development - Feature Requests Wanted](https://www.reddit.com/r/Intune/comments/1t0cqyx/interest_in_dashboard_for_intune/)
- [Organisations Eyeing Mac Fleets as HP Laptop Prices Double - Intune Mac Management Considerations](https://www.reddit.com/r/sysadmin/comments/1t0157x/hp_laptop_pricing_is_so_out_of_control_management/)
- [Domain-to-Entra Migration Without Reformat - Community Shares Scalable Approaches](https://www.reddit.com/r/Intune/comments/1t13jim/is_there_a_way_to_connect_existing_domain_join/)

---

For the full story on every item, **[download the PDF](https://ugurkocde.github.io/IntuneWeekly/editions/2026-05-05/intune-weekly.pdf)**. The PDF includes the radar, the upcoming-changes timeline, and the full body of each section.

Never miss an edition - **[subscribe to Intune Weekly on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)**.
