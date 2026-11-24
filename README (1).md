# PHX Founders: Season 1 Release Plan

The release plan for Season 1 of the **PHX Founders** podcast from PHX Ventures, as a one-page interactive calendar.

## What's in it

- **Month calendars (Dec 2026 to Mar 2027).** Release days are filled in each guest's colour, shorts show as dots, and production milestones are flagged in the corner. Click any date to see everything going out that day.
- **Week by week.** All 9 episodes with release date, title, guest, host, and the posting schedule for every LinkedIn short.
- **Production milestones.** Editing and scheduling deadlines from December through the finale.
- **Every release week.** The weekly posting rhythm in four lines.

## Season at a glance

| Week | Release | Episode | Guest | Host |
| --- | --- | --- | --- | --- |
| 1 | Jan 12 | Igniting the Go-to-Market Engine | Kaled Alhanafi, Basata | Jeff Kerr |
| 2 | Jan 19 | Building Customer Success | Chris Chumley, Coursedog | Bennett Scoresby |
| 3 | Jan 26 | Interviewing Your First Key Hires | Sasha Robinson, Trainual | Jackson Scoresby |
| 4 | Feb 2 | Building a Co-founder Relationship That Lasts | Kaled Alhanafi, Basata | Jeff Kerr |
| 5 | Feb 9 | From Single Product to Multi-Product | Chris Chumley, Coursedog | Bennett Scoresby |
| 6 | Feb 16 | Founder-Led Hiring vs. Outsourced Recruiters | Sasha Robinson, Trainual | Jackson Scoresby |
| 7 | Feb 23 | Hiring for Startup Intensity | Kaled Alhanafi, Basata | Jeff Kerr |
| 8 | Mar 2 | What Three Startups Taught Me About Vertical SaaS | Chris Chumley, Coursedog | Bennett Scoresby |
| 9 | Mar 9 | Hiring Your First People Ops Leader | Sasha Robinson, Trainual | Jackson Scoresby |

Episodes release on Tuesdays. Each week has two shorts from the new episode (Tuesday and Thursday) plus a Monday throwback short from an earlier episode, all posted on the PHX LinkedIn page. Titles for weeks 4, 7 and 8 are proposed and still need sign-off from the hosts.

## Viewing it

Open `index.html` in any browser, or visit the GitHub Pages site once it's turned on (see below). It works on desktop and phone.

## Publishing with GitHub Pages

1. In the repository, go to **Settings > Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two the site is live at `https://<account-name>.github.io/phx-podcast-plan/`.

GitHub Pages is free for public repositories. A private repository needs a paid GitHub plan to use Pages.

## Updating the plan

Everything is in `index.html`, with no build step or dependencies (fonts load from Google Fonts). To change the plan, edit the data near the top of the `<script>` block:

- `EPS`: one entry per episode (release date, guest key, title, number of shorts).
- `LATER`: dates for each episode's throwback and post-finale shorts.
- `MS`: production milestones (date, description).

The calendar, week-by-week list and day popouts all update from those lists.
