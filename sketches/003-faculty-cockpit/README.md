## Variant: Faculty Cockpit (cohort in focus)

### Design stance
Teaching is relational. The dashboard should always have a student in view — because every grading decision, every deadline, every announcement comes back to a person.

### Key choices
- **Layout:** three-pane split — sections list (left), section detail with roster (center), student detail panel (right). Top tabs for switching workspaces (Today / Sections / Grading / Advising / Inbox).
- **Typography:** Inter with editorial warmth; warm earth-tone palette (terracotta `#7a3d2f` on cream `#f6f3ec`) to differentiate from the rest of Northstar's sage and signal "this is the deep-work surface."
- **Color:** terracotta accent, warm grays, no harsh reds. At-risk students flagged with `⚠` (amber), high performers with `★`.
- **Interaction:** click a roster row → right panel updates to that student. Click a section card → center pane updates. Selected states use a tinted background. Roster rows show trend arrows and current grade with a sparkline-style trend bar.

### Trade-offs
- **Strong at:** the loop faculty actually live in — see section → see student → act. Makes individual students visible (A. Okafor at 42%, F. Diallo at 38%) instead of treating them as anonymous submissions.
- **Weak at:** a single-glance "what's the day" view. The Today tab is implied but not built here. Also assumes the user is willing to think in terms of one section at a time, which breaks for someone teaching 4+ courses.

### Best for
Faculty who teach smaller, more relationship-driven sections and want advising-style detail always one click away.
