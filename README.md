# Christian Reformed Church of Toowoomba

A static, mobile-first website for the Christian Reformed Church of Toowoomba (Glenvale, Queensland). It is plain HTML and CSS, with no build step and no paid services, so it can be published from the repository root on GitHub Pages.

Content is taken from the congregation’s public website, [toowoombacrc.com](https://toowoombacrc.com/), as checked on 20 October 2026. Photographs and the church logo were not copied. The hillside graphic is an original illustration.

## Pages

- `index.html` — mission, Sunday times, address
- `about.html` — welcome, beliefs, elders, deacons, policy links
- `ministries.html` — groups published on the church events pages
- `events.html` — calendar snapshot and special gatherings
- `sermons.html` — links to the sermon archive, YouTube, and recent titles
- `visit.html` — how to find the building, contact, giving, map

`sitemap.xml`, `robots.txt`, and Church JSON-LD on the home page assume the project-site URL `https://aneesh15here.github.io/toowoomba-crc/`. Change those if Pages is served from another host.

## GitHub Pages

GitHub Pages deploys from the `main` branch root. `.nojekyll` keeps Jekyll from rewriting the site.

## TODO

Facts that were missing, conflicting, or unsafe to guess:

1. **Pastor biography.** The contact page and sermon archive name Pastor / Rev. / Ps. Andrew de Vries. The people page biography is about “Pastor Andrew Nugteren” (Wellington from 2006, Toowoomba from May 2013, wife Lydia, eight children). That biography is not shown.
2. **Women’s Bible Study email.** The events page prints `admin@toowoomba.com`. The contact page uses `admin@toowoombacrc.com`.
3. **Men’s Bible Study rhythm.** The page says both “Every 2 Weeks” and “weekly”.
4. **GROW and the 5:00pm service.** GROW is described as a fortnightly Sunday afternoon gathering at 5:00pm (next listed date 15 November). The homepage also labels some Sunday evenings “GROW Service”, while Sunday worship is described as a weekly 5:00pm service. It is not clear whether GROW replaces that service.
5. **General meeting date.** Published as “Wednesday 12th November” to discuss the 2026 budget, with no year. 12 November 2026 is a Thursday.
6. **Street number.** The church site says 718 Boundary Street. The CRCA directory also prints “726 Boundary Street, 4350 Glenvale”.
7. **Not published:** office hours, a postal address distinct from the street address, and an age range for youth group.
8. **Audio sermons.** The audio-only page had no individual recording list in its main content on 20 October 2026.
9. **Calendar is a snapshot** of 20 October 2026 and will go stale.
10. **Alix.** The contact page names Executive Assistant Alix. The craft page names craft leader Alix Alexander. They are not explicitly identified as the same person.
11. **Images.** No church photographs or logo were copied. Replace the illustration if the church supplies images it is happy to publish.
12. **Canonical URL.** Sitemap, Open Graph, and JSON-LD use `https://aneesh15here.github.io/toowoomba-crc/`. Update them if the live Pages URL differs.
13. **Source typos left as published** on the beliefs page: “experiened”, “though the Protestant Reformation”, and “the some of the important things”.
