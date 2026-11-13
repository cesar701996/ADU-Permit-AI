# ADU Permit AI (demo)

A clickable mockup of an ADU permit review tool for a small-town city hall. First city: Greenfield, California.

Open `index.html` in a browser. It needs internet only for the font.

## Screens

- **Applications**: the planner's queue, sorted by state deadline, with a code check, a lot diagram and a drafted letter for each application.
- **Pre-check**: what a homeowner sees before applying, in English or Spanish.
- **Rules**: every rule the check runs on, with its code section.

## What is real and what is not

- Real: the rules, coded from Greenfield Municipal Code Chapters 17.90 (ADUs) and 17.30 (zoning height limits), and the state deadlines in Gov. Code § 66317.
- Invented: the sample applicants and addresses, and the city holiday calendar.
- Simulated: reading values off uploaded plans, sending letters, logins. Buttons only change state in the browser.
- Draft: the Spanish translation. A fluent reader should confirm the legal terms.

## Sources

- Greenfield Municipal Code Ch. 17.90: https://ecode360.com/47084735
- Greenfield Municipal Code Ch. 17.30: https://ecode360.com/47083391
- HCD ADU Handbook, March 2026: https://www.hcd.ca.gov/sites/default/files/docs/policy-and-research/ADU-Handbook-Update.pdf

## Design checks

`.taste-skill/direction.json` holds the design direction used by the tasteskill inspector. Its screenshots are not tracked.
