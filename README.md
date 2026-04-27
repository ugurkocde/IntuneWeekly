# Intune Weekly

The forward-looking briefing for Microsoft Intune admins. Every Tuesday.

This repository is the public archive. It holds the weekly PDF, a LinkedIn-formatted Markdown version, and a static landing page hosted via GitHub Pages.

- **Latest edition and archive:** [ugurkocde.github.io/IntuneWeekly](https://ugurkocde.github.io/IntuneWeekly/)
- **Subscribe on LinkedIn:** [Intune Weekly newsletter](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7454605096895746048)

## What makes this newsletter different

Most Intune newsletters look backwards: they summarise what already shipped. Intune Weekly leads with what is coming. Each edition starts with **On the radar** - 3 to 5 cross-source items admins should be aware of right now - then walks through:

1. **Landing in your tenant soon** - changes with effective or GA dates in the next 30 days
2. **On the horizon** - what is being developed and rolled out beyond 30 days
3. **Action required** - changes with hard deadlines admins must plan around
4. **What shipped** - features that went GA in the last 7 days
5. **From the field** - real-world issues from r/Intune and the wider community that Microsoft does not publicly acknowledge

## Sources

Microsoft 365 Roadmap, Message Center (via Merill Fernando's archive), In-Development docs, What's New / Microsoft Learn, Tech Community blog feeds, r/Intune, r/MicrosoftIntune, r/sysadmin. Each story is credited inline with a "Read more" link to the source.

## Repository structure

```
editions/YYYY-MM-DD/
    intune-weekly.pdf       Broadsheet PDF for download
    linkedin-article.md     LinkedIn-newsletter-ready Markdown
editions.json               Machine-readable index of all editions
index.html                  Landing page (timeline + archive)
```

The rendering pipeline lives in a separate private repository.

## License

The rendered editions are published for personal use by Intune admins. Source content is credited to its respective publishers (Microsoft, Tech Community authors, Reddit posters). The site code in this repo is MIT-licensed.
