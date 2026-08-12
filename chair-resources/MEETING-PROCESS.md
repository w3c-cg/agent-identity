# Meeting Process Guide

> This document is intended for use by the Chair(s) of the Agent Identity Registry Protocol Community Group. It is published here for transparency and continuity purposes.

This document describes the end-to-end process for scheduling, running, and publishing records of Agent Identity Registry Protocol CG meetings. Follow this sequence for every meeting.

---

## Overview

Each meeting involves four stages: scheduling, agenda preparation, running the meeting, and publishing the minutes record.

---

## Stage 1 — Schedule the Meeting

1. Log into your W3C account at w3.org
2. Go to the group page: https://www.w3.org/groups/cg/agent-identity/
3. Click the **Calendar** tab
4. Create a new event with:
   - Date, time, and duration
   - Time zone (use UTC as the reference)
   - Call link (Zoom, Google Meet, or equivalent)
   - Whether it recurs (weekly, biweekly, monthly)
   - Mark as **Tentative** by default — confirm or cancel closer to the date
5. W3C will notify all participants by email automatically

---

## Stage 2 — Prepare the Agenda (before the meeting)

1. Copy `meetings/templates/agenda-template.md`
2. Rename it `meetings/YYYY/YYYY-MM-DD-agenda.md`
3. Fill in the date, time, call link, and agenda items
4. Open a **GitHub Issue** in this repo labeled `agenda` — paste the agenda there and invite participants to comment with additional items
5. Update the W3C calendar event to link to the GitHub issue
6. Post the agenda to the mailing list: public-agent-identity@w3.org

---

## Stage 3 — Run the Meeting

- Start the call with introductions for any new participants
- Designate automated note-taking at the start of the call
- Follow the agenda order
- State resolutions clearly and explicitly before moving on — they will be recorded in the minutes
- Assign action items with a named owner and due date
- Close by confirming the next meeting date

---

## Stage 4 — Publish the Minutes (within 10 calendar days)

1. Copy `meetings/templates/minutes-template.md`
2. Rename it `meetings/YYYY/YYYY-MM-DD-minutes.md`
3. Edit the automated notes into the minutes format — attendees, discussion summaries, resolutions, action items
4. Commit the file to this repo
5. Update the W3C calendar event to link to the published minutes
6. Post a summary to the mailing list: public-agent-identity@w3.org

---

## File Naming Convention

```
meetings/YYYY/YYYY-MM-DD-agenda.md
meetings/YYYY/YYYY-MM-DD-minutes.md
```

Example:
```
meetings/2026/2026-09-15-agenda.md
meetings/2026/2026-09-15-minutes.md
```

---

## Checklist

### Before the meeting
- [ ] Meeting scheduled in W3C calendar
- [ ] Agenda prepared from template
- [ ] GitHub issue opened with agenda, labeled `agenda`
- [ ] Calendar event updated with link to GitHub issue
- [ ] Agenda posted to mailing list

### After the meeting
- [ ] Minutes drafted from automated notes
- [ ] Minutes committed to repo as `YYYY-MM-DD-minutes.md`
- [ ] Calendar event updated with link to minutes
- [ ] Summary posted to mailing list
