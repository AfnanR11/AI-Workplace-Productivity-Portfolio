# Prompt Library

This library contains reusable prompts designed for my role as a Media Production Project Manager.

---

## 1. Project Status Brief

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Project Status Brief | Summarize scattered project updates | C.A.R.E. | **Context:** I am managing a media production project with multiple team members. **Action:** Review the project updates below and summarize the current status. **Role:** Act as a project management assistant. **Expected Output:** Create a structured status brief with Completed, In Progress, Delayed, Risks, and Recommended Next Actions. Do not invent missing information. Mark missing details as [Not Specified]. | A concise project status report with clear next actions. |

### Example Output

**Project Status Brief**

**Completed**
- Initial script approved.
- Shooting schedule prepared.

**In Progress**
- Video editing is ongoing.
- Graphics team is preparing motion graphics.

**Delayed**
- Final voice-over recording.

**Risks**
- Voice-over delay may affect the editing deadline.

**Recommended Next Action**
Confirm the voice-over recording date and update the production schedule.

---

## 2. Action Item Extractor

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Action Item Extractor | Extract tasks from meeting notes | C.A.R.E. | **Context:** I have notes from a media production meeting. **Action:** Extract all action items and organize them into a table. **Role:** Act as a project coordination assistant. **Expected Output:** Action Item, Owner, Deadline, Priority, and Status. Do not guess missing information; use [Not Specified]. | A clear action-item table. |

---

## 3. Task Assignment Assistant

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Task Assignment Assistant | Organize project tasks | R.C.T.O. | **Role:** Act as a Media Production Project Manager assistant. **Context:** I need to organize tasks for a media production project. **Task:** Group the provided tasks by production stage and suggest a logical owner based only on the roles provided. **Output:** A table with Task, Production Stage, Suggested Role, Priority, and Dependency. | A structured task-assignment table. |

---

## 4. Production Schedule Planner

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Production Schedule Planner | Create a production schedule | C.A.R.E. | **Context:** I am planning a media production project with pre-production, production, and post-production stages. **Action:** Organize the tasks into a realistic sequence. **Role:** Act as a project planning assistant. **Expected Output:** A phased schedule showing tasks, dependencies, and milestones. Do not create dates unless dates are provided. | A structured production plan. |

---

## 5. Follow-Up Message Generator

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Follow-Up Message Generator | Follow up on delayed tasks | C.A.R.E. | **Context:** A production task has not been completed by its expected deadline. **Action:** Draft a professional follow-up message. **Role:** Act as a professional project coordinator. **Expected Output:** A polite and concise message that asks for the current status, identifies blockers, and requests an updated completion date. | A professional follow-up message. |

### Example Output

**Subject: Follow-Up on Production Task**

Hello [Team Member],

I hope you are doing well.

I am following up regarding the current status of the assigned production task. Could you please provide an update on the progress and let me know if there are any blockers affecting completion?

Please also share the expected completion date so that I can update the project schedule.

Thank you.

Best regards,  
Media Production Project Manager

---

## 6. Meeting Summary Generator

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Meeting Summary Generator | Summarize production meetings | R.C.T.O. | **Role:** Act as a project documentation assistant. **Context:** The following notes come from a media production team meeting. **Task:** Summarize the key decisions, progress updates, risks, and action items. **Output:** Use the headings Decisions, Progress Updates, Risks, and Action Items. | A structured meeting summary. |

---

## 7. Production Risk Identifier

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Production Risk Identifier | Identify possible project risks | C.A.R.E. | **Context:** I am managing a media production project. **Action:** Review the provided project status and identify potential risks or dependencies. **Role:** Act as a project risk assistant. **Expected Output:** List each risk, its possible impact, and a recommended action. Base the analysis only on the provided information. | A risk register with recommended actions. |
