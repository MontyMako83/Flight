---
name: morning-brief
description: Daily briefing for James Cavin — FD Flight, 301 FSS. Pulls calendar, email priorities, ticket queue status, and Teams updates into a single structured summary to start the day.
user-invocable: true
---

# Morning Brief

Generate James's daily briefing. Be direct. BLUF everything. No filler.

## Step 1: Pull Today's Calendar
Check Google Calendar for today's events.
- List all meetings with time, title, and any prep needed
- Flag anything before 0900 (staff meetings are Mon/Wed at 0800)
- Note if today is Wednesday — unit is closed to customers, Transaction Register review day

## Step 2: Check Email
Search Gmail for unread or high-priority emails received since yesterday COB.
- Prioritize anything from higher-ranking (Lt Col, Col, CMSgt, Command)
- Flag any suspenses or action items
- Note anything requiring a response today

## Step 3: Check Teams
Review Microsoft Teams channels for overnight or early updates.
- Flag new taskers assigned to FD Flight
- Note any project updates or deadlines
- Surface anything James needs to act on today

## Step 4: Weekly Rhythm Check
- If today is Monday: Commander slides are due COB — flag this
- If today is Tuesday: Commander's meeting — confirm slides are ready
- If today is Wednesday: Transaction Register review, closed to customers

## Output Format
Deliver as a structured brief with headers. Active voice. BLUF.
No pleasantries. Start immediately with the brief.

---

# DAILY BRIEF — [DATE]

## Calendar
[list today's meetings with times]

## Email Priorities
[list action items from email, ranked by urgency]

## Teams Updates
[list new taskers and updates]

## Weekly Flag
[any Monday/Tuesday/Wednesday-specific items]

## Bottom Line
[1-2 sentences on what today's priority is]
