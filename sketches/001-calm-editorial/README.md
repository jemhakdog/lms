## Variant: Calm Editorial

### Design stance
Treat the department dashboard like the front page of a small magazine — generous whitespace, editorial typography, content first, and trust the reader to scan naturally rather than forcing density.

### Key choices
- **Layout:** Single column with a wide masthead, two-column "story + sidebars" pattern, then a clean three-column course grid. No persistent sidebar.
- **Typography:** Fraunces (serif display) for headings, Inter for body. Big editorial h1 (56px), 16px body, real hierarchy via type rather than color
- **Color:** Warm off-white background (#fbfaf7), brown accent (#8b5a2b — academic, not corporate), soft borders. Almost no saturated color.
- **Interaction:** All hover states are subtle (border-color shift, underline on accent color). No flashy transitions. Top nav as the only chrome.

### Trade-offs
- **Strong at:** Welcoming a chair/administrator opening the dashboard for a morning review, presenting the department to external readers, on mobile (single column reflows gracefully)
- **Weak at:** Triaging 20+ requests, comparing fill rates across 40+ courses, finding a specific section quickly, conveying real-time urgency

### Best for
- Department chairs who treat the dashboard as a daily briefing, not a control panel
- An audience that values the academic register and wants the software to feel less like SaaS
- Smaller departments where the data isn't overwhelming
