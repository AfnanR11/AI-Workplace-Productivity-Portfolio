# Information Processing Workflow

## Information Task Used

**Summarizing and Extracting Action Items**

The purpose of this workflow is to transform scattered media production updates into structured information that supports project decisions.

---

# 1. Raw Input

The following fictional updates were received from the production team:

> Script team: The final script was approved yesterday.

> Filming team: Camera and lighting equipment are ready. We are waiting for confirmation of the filming location.

> Video editor: The first draft of the video is approximately 60% complete. I need the final voice-over file before completing the audio synchronization.

> Audio team: Voice-over recording has not yet been scheduled.

> Graphics team: Motion graphics concepts have been approved and production has started.

---

# 2. Prompt Used

**Context:** I am a Media Production Project Manager receiving updates from multiple production teams.

**Action:** Analyze the updates and extract project progress and action items.

**Role:** Act as a project coordination assistant.

**Expected Output:**

1. Completed Work
2. Work in Progress
3. Blockers
4. Action Items

Create an action-item table with Owner, Deadline, Priority, and Status.

Do not invent information. Use [Not Specified] when information is missing.

---

# 3. AI Output

## Completed

- Final script approved.
- Camera and lighting equipment prepared.
- Motion graphics concepts approved.

## In Progress

- Video editing is approximately 60% complete.
- Motion graphics production has started.

## Blockers

- Filming team is waiting for filming location confirmation.
- Video editing depends on the final voice-over file.
- Voice-over recording has not yet been scheduled.

---

# 4. Human Review

I reviewed the AI output and checked that:

- Every point came from the original updates.
- No deadlines were invented.
- No owners were assigned unless clearly identified.
- The dependency between voice-over and video editing was correctly identified.

---

# 5. Final Structured Output

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm filming location | [Not Specified] | [Not Specified] | High | Open |
| Schedule voice-over recording | Audio Team | [Not Specified] | High | Not Started |
| Continue video editing | Video Editor | [Not Specified] | Medium | In Progress |
| Continue motion graphics production | Graphics Team | [Not Specified] | Medium | In Progress |

## Recommended Project Manager Action

The highest priority is confirming the filming location and scheduling the voice-over recording because both items create dependencies that may affect the production timeline.
