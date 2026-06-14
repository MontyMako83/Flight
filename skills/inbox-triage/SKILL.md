---
name: inbox-triage
description: Reads James's Gmail inbox, filters noise, and returns a prioritized action list organized by urgency. Designed for FD Flight, 301 FSS context.
user-invocable: true
---

# Inbox Triage

Triage James's Gmail inbox. Be direct. No summaries of what you're doing — deliver the output.

## Step 1: Pull Unread Email
Search Gmail for unread messages. Focus on inbox, exclude automated notifications and newsletters.

## Step 2: Categorize by Priority

### Priority 1 — Act Today
- Messages from higher-ranking (Lt Col, Col, CMSgt, MAJCOM, HQ AFRC, Wing/CC)
- Hard suspenses or deadlines due today or tomorrow
- Anything marked urgent or time-sensitive
- Messages from AGR MSgts requiring a decision

### Priority 2 — Act This Week
- Taskings with suspenses later this week
- Coordination requests from peers or other flights
- Customer issues that need follow-up
- Anything tied to Commander slides (if Monday) or Transaction Register (if Wednesday)

### Priority 3 — Monitor / No Action Yet
- FYI emails and CC'd messages
- Updates that require no response
- Items that can wait beyond this week

### Noise — Skip
- Automated system notifications
- Newsletters and subscriptions
- Duplicate or thread follow-ups already addressed

## Step 3: Output

Deliver as a structured list. Active voice. BLUF each item in one line.
No filler. No preamble.

---

# INBOX TRIAGE — [DATE] [TIME]

## Priority 1 — Act Today
[numbered list: sender, subject, action needed]

## Priority 2 — Act This Week
[numbered list: sender, subject, action needed]

## Priority 3 — Monitor
[numbered list: sender, subject, why it's here]

## Bottom Line
[total unread count processed, how many need action today]
