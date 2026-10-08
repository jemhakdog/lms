## Variant: Faculty Day (calendar-forward)

### Design stance
The day itself is the dashboard. The first thing a teacher needs to know is *what's happening now and what's next*; everything else is downstream.

### Key choices
- **Layout:** persistent left sidebar (sage, like the rest of Northstar) + full-width main with a hero "now" card, an hour-by-hour timeline, and a two-card footer (to-grade + announcements).
- **Typography:** Inter, generous line-height, large display for greeting.
- **Color:** sage primary `#126b5b` on cream `#f4f7f5`; today's hero flips to a deep green gradient to make the in-session class the visual anchor.
- **Interaction:** timeline rows are clickable; week chips toggle. Live class row marked with a `LIVE` pill.

### Trade-offs
- **Strong at:** orienting a faculty member the moment they open the app. Lowest cognitive load of the three. Feels calm and trustworthy — the rest of Northstar's voice.
- **Weak at:** quick triage. There is no single "what's broken" view. Grading and advising are mentioned but not ranked.

### Best for
Faculty who teach 2–4 sections and want a daily-planner feel — the day is the unit of work, not the cohort.
