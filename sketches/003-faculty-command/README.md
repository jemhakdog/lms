## Variant: Faculty Command (dense, action-first)

### Design stance
A faculty member's job is a queue. Show the queue ranked by urgency, with the signals (overdue grading, at-risk students, unread messages) visible at a glance — like a control room.

### Key choices
- **Layout:** dark theme (contrast with the rest of Northstar) to reduce glare during long grading sessions; 6-up KPI strip, full-width action queue table, right column with section health bars and inbox.
- **Typography:** Inter, dense 12.5–13px body, tabular numerals for counts/percentages, monospace `⌘K` hints.
- **Color:** near-black `#0f1714` base, mint accent `#2dd4a4`, red `#ff7a6b` for overdue, amber `#f5b941` for warning. One alert tile (`overdue grading`) uses a red gradient to draw the eye.
- **Interaction:** queue tabs filter (All / Grading / Advising), clicking a message marks it read, sparkline placeholders under each KPI.

### Trade-offs
- **Strong at:** triage. A faculty member with 100+ submissions can see what to do first without scrolling. Numbers everywhere, all aligned, all scannable.
- **Weak at:** tone. Dark, dense, and urgent can read as stressful — wrong vibe for someone who just wants to check what's on for the day. The cohort context (who is Femi Diallo? why is he at 38%?) is also missing.

### Best for
Senior faculty, program directors, or anyone whose week is dominated by grading and advising volume rather than classroom time.
