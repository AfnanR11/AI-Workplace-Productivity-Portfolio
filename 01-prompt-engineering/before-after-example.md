# Before and After Prompt Example

## Scenario

A Media Production Project Manager receives scattered updates from several team members and needs to understand the overall project status.

---

## Before: Weak Prompt

> Summarize these project updates.

---

## Initial Result

The result provided a general summary, but it did not clearly separate completed work, delays, risks, or action items.

The output was difficult to use for project decision-making.

---

## After: Improved C.A.R.E. Prompt

**Context:** I am a Media Production Project Manager coordinating a video production project. I receive updates from the script, filming, editing, graphics, and audio teams.

**Action:** Review the updates below and transform them into a decision-ready project status brief.

**Role:** Act as a project management assistant.

**Expected Output:** Use the following headings:

1. Completed
2. In Progress
3. Delayed or Blocked
4. Risks
5. Action Items
6. Recommended Next Action

Do not invent information. If information is missing, write [Not Specified].

---

## Improved Result

### Completed
- Script has been approved.
- Filming equipment has been prepared.

### In Progress
- Video editing is ongoing.
- Motion graphics are being designed.

### Delayed or Blocked
- Voice-over recording is delayed.

### Risks
- The delayed voice-over may affect the final editing schedule.

### Action Items
| Action Item | Owner | Deadline | Status |
|---|---|---|---|
| Confirm voice-over recording date | Audio Team | [Not Specified] | Open |
| Review editing progress | Project Manager | [Not Specified] | In Progress |

### Recommended Next Action

Contact the audio team to confirm the recording schedule and assess whether the production timeline needs to be adjusted.

---

## What Improved?

- The improved prompt provided clear context about the workplace situation.
- The AI was given a specific role and task.
- The expected output structure made the result easier to review.
- The instruction not to invent information reduced the risk of inaccurate project data.
