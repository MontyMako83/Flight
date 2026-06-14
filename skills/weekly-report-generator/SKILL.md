---
name: weekly-report-generator
description: Pulls the week's activity from James's calendar, email, and Granola meeting notes and generates a commander-ready weekly summary for FD Flight, 301 FSS.
user-invocable: true
---

# Weekly Report Generator

Generate a commander-ready weekly summary for FD Flight. Pull from connected tools.
Active voice. BLUF. Structured with headers. No filler.

## Step 1: Pull This Week's Data

### Calendar (Google Calendar)
Pull all events from Monday through Friday of the current week.
- List meetings attended, trainings conducted, and official engagements
- Note any commander-level briefs or command visits

### Email (Gmail)
Search sent email from this week (in:sent newer_than:7d).
- Identify major actions taken: responses to taskings, coordination completed, products delivered
- Flag any suspenses met or missed

### Meeting Notes (Granola)
Pull meeting notes from this week if available.
- Extract key decisions made, action items assigned, and issues surfaced
- Note any items that carry forward to next week

### Teams
Check Microsoft Teams for this week's tasker completions and project updates.
- List taskers closed this week
- Note any new taskings received

## Step 2: Organize by Category

### Ticket and Customer Service Activity
- Total tickets worked or closed (from vFSS if data is available)
- Notable customer issues resolved
- Walk-in and phone volume if known

### Training and Education Activity
- Formal schools coordinated or completed
- Education actions processed
- Testing activity
- EPME scheduling updates

### Administrative and Compliance
- Transaction Register review completed (if Wednesday)
- Commander slides updated (if Monday)
- Policy or regulatory actions completed
- Suspenses met

### Projects and Improvements
- AI tools or process improvements advanced
- SOPs drafted, updated, or published
- Any products delivered to leadership

### Issues / Watch Items
- Anything unresolved that carries to next week
- Manpower gaps, compliance risks, or open taskings

## Step 3: Generate the Report

Format as a clean weekly summary. Start with the bottom line.
No preamble. Deliver the report directly.

---

# FD FLIGHT WEEKLY SUMMARY
**Week of**: [Monday date] - [Friday date]
**Prepared by**: SMSgt James Cavin, FD Flight

## Bottom Line
[2-3 sentences: what the flight accomplished this week and any open issues]

## Ticket and Customer Service
[bullets]

## Training and Education
[bullets]

## Administrative and Compliance
[bullets]

## Projects and Improvements
[bullets]

## Watch Items / Carry-Forward
[bullets — or "None" if clean]

---

## Step 4: Prompt
After generating, ask:
"Review for accuracy and anything I missed. Add any verbal updates or off-calendar actions before I finalize."

Save output to: active/exports/weekly-summary-[date].md
