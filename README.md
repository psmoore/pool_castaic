# Castaic Aquatic Center — Pool Relay embed preview

A mockup of [castaic.lacountypools.com](https://castaic.lacountypools.com/), the LA County Parks pool at the
Castaic Regional Sports Complex, with its fall schedule on live [Pool Relay](https://www.poolrelay.com)
calendars and a page per program.

Not an official Los Angeles County page. It says so in a ribbon across the top.

Built with `python3 build.py` (the chrome lives there; edit it, not the HTML) and served by GitHub Pages.

## The pages

| Page | Calendar | Scoped to |
|---|---|---|
| `index.html` — Find a swim time | [`94hllfke…`](https://www.poolrelay.com/v/94hllfke9HUuzUaHoB2ZZH) | the pool, one day, a row per part of the pool; **Teams** menu |
| `week.html` | [`R07JQHtJ…`](https://www.poolrelay.com/v/R07JQHtJ4XjdAAarm8ofK7) | everything, the whole week; **Teams** menu |
| `lap-swim.html` | [`SupzWBAn…`](https://www.poolrelay.com/v/SupzWBAnEkR2SZcZ16sDpL) | lap swim |
| `swim-lessons.html` | [`1MbB9BQQ…`](https://www.poolrelay.com/v/1MbB9BQQR4z5zvvAvSFLvW) | lessons; **Practice Groups** menu picks a level |
| `rec-swim.html` | [`SsfGHB7n…`](https://www.poolrelay.com/v/SsfGHB7nk1aV8w8DRqQoYf) | rec swim and water exercise |
| `water-polo.html` | [`FeqLr6dg…`](https://www.poolrelay.com/v/FeqLr6dg7dmWVv650PO6tv) | Youth Water Polo Team, Masters Family Water Polo |

## Sources (read 2026-09-25)

- **Home page** Fall 2026 grid (Aug 24 – Nov 21): lap swim, rec swim, water exercise; closed Sundays.
- **ActiveNet** (`center_ids=263`; REST `rest/activities/list` and `rest/activity/detail/meetingandregistrationdates/{id}`,
  both plain curl): Session 3 weekday lessons (Sep 21 – Oct 2), the Saturday session (Aug 29 – Oct 31), the
  Youth Water Polo Team (weekdays 5–6pm to Nov 20), Masters Family Water Polo (Sat Sep 26, 8:30–11am).
- **Lessons** page: session dates through Nov 20; its class list is still Session 1.
- **Team Sports** page: water polo, swim team ("Winter 2026", 5–6pm), dive and artistic swimming (TBA).

## What is ours

- **Five areas in one pool**: Lap Lanes, Lesson Area, Water Exercise Area, Team Area, Rec Swim Area. No page
  says how the pool is divided.
- **Lessons at the same time are one block** (Levels 3 and 4 at 6pm and 7pm; two Parent and Child sections at 9am).
- Sessions 4–7 are not entered: their classes aren't posted yet.

## Open questions (also on the hub page)

| | |
|---|---|
| **Gap** | Lanes left for lap swim 4–8pm with lessons, water polo (5–6) and water exercise (6–7) in the pool. |
| **Conflict** | The Lessons page lists Session 1 classes; Session 3 on ActiveNet adds a 7pm Level 3 and a 6pm Level 4. |
| **Gap** | Sat Sep 26 Masters Family Water Polo 8:30–11 during lap swim, water exercise and lessons. |
| **Gap** | Weekdays 11am–3pm: nothing scheduled. |
| **Gap** | Swim Team "Winter 2026"; Dive Team and Artistic Swimming TBA. |
