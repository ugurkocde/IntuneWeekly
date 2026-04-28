# Intune Weekly

The forward-looking briefing for Microsoft Intune admins. Every Tuesday.

<p align="center">
  <a href="https://ugurkocde.github.io/IntuneWeekly/">
    <img alt="Intune Weekly" src="https://github.com/user-attachments/assets/d5016197-0fb3-4075-9b08-4460a381bd1d" width="640">
  </a>
</p>

This repository is the public archive. It holds the weekly PDF, a LinkedIn-formatted Markdown version, and a static landing page hosted via GitHub Pages.

## Read the latest edition

- [Latest edition and full archive](https://ugurkocde.github.io/IntuneWeekly/) on GitHub Pages
- [Subscribe on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048) to get every issue in your feed

## What makes this newsletter different

Most Intune newsletters look backwards: they summarise what already shipped. Intune Weekly leads with what is coming. Each edition opens with **On the radar** - 3 to 5 cross-source items admins should be aware of right now - then walks through:

1. **Landing in your tenant soon** - changes with effective or GA dates in the next 30 days
2. **On the horizon** - what is being developed and rolled out beyond 30 days
3. **Action required** - changes with hard deadlines admins must plan around
4. **What shipped** - features that went GA in the last 7 days
5. **From the field** - real-world issues from r/Intune and the wider community that Microsoft does not publicly acknowledge

Every story carries triage tags so you can scan the issue in seconds: severity (`CRITICAL` / `ADVISORY` / `INFO`), scope (`SMB` / `ENT` / `MSP` / `ALL`), platform (`WIN` / `MAC` / `iOS` / `AND` / `CROSS`), and signal strength (`SINGLE` / `CONFIRMED` / `MS-ACK`) on community-sourced items.

## Sources

- Microsoft 365 Roadmap (Intune, Entra, Windows 365)
- Message Center via [Merill Fernando's archive](https://mc.merill.net)
- In-Development docs and What's New on Microsoft Learn
- Windows Release Health (Windows Message Center)
- Microsoft Graph API changelog
- Microsoft Tech Community (Intune Blog, Customer Success, Windows IT Pro, Discussions)
- Reddit: r/Intune, r/MicrosoftIntune, r/sysadmin, r/SCCM, r/entra, r/microsoft365

Every story is credited inline with a `Read more` link to the source.

## Repository structure

```
editions/YYYY-MM-DD/
    intune-weekly.pdf       Broadsheet PDF for download
    linkedin-article.md     LinkedIn-newsletter-ready Markdown
editions.json               Machine-readable index of all editions
index.html                  Landing page (timeline + archive)
```

The rendering pipeline lives in a separate private repository.

## About

Curated by [Ugur Koc](https://www.linkedin.com/in/ugurkocde/). New issue every Tuesday.

## License

The rendered editions are published for personal use by Intune admins. Source content is credited to its respective publishers (Microsoft, Tech Community authors, Reddit posters). The site code in this repo is MIT-licensed.
