
# Cycle: An Open Software Development Methodology (v1.0)

## Overview
**Cycle** is a flexible, lightweight methodology emphasizing **short-term focus**, **collaboration**, **continuous improvement**, **shared responsibility**, **accountability**, and **business alignment**.  
It empowers the **software team** to manage planning and approvals directly.  
The development of software is itself a cycle—one you should refine and improve with each iteration.

## Core Principles
1. **No Backlog**
   - Only plan for the **Current Cycle**. We believe that more than 90% of the focus should be on the current cycle and less than 10% on what’s coming after the current cycle, which we call the **Next Cycle**.
   - Use the **Next Cycle** for short-term vision only.
   - Tasks depending on external work should not be created unless that work will be ready for the next cycle.

2. **No Fixed Timeframe**
   - Cycles can be longer or shorter depending on scope and capacity.
   - If a task needs a bit more time, it is preferred to stretch the cycle rather than forcing a carry-over unnecessarily.
   - Defining Timeframe for cycles is optional.

3. **Release at Cycle End**
   - Every cycle ends with a release of the planned deliverables. you are open to decide if the release is on production or stage environment. but we suggest choose production release whenever possible.
   - after each cycle its better to have a short **Cycle Gap** for cool down team, bug fixes, better preparation for next cycle or minor maintenance.

4. **Team Responsibility**
      - The **software team itself**—Developers, QAs, and Visionary Architects— collectively holds responsibility for defining and approving tasks.

## Roles and Responsibilities

### Cycle Lead
- Facilitator for the cycle.
- Could be a team lead, technical lead, CTO, or senior engineer.
- In flat teams, rotate this role among senior team members.

### Developers
- **Share responsibility for what enters the cycle**—question unclear requirements and provide feasibility feedback. 
- Collaborate with VAs, QAs, and project managers to clarify or **propose tasks for the Next Cycle**.  
- Implement tasks defined for the current cycle according to specifications and Definition of Done.
- Actively surface technical risks or dependencies that could affect future cycles.
- Accountable for tasks entering the cycle—reviewing and **challenging unclear or incomplete requirements**.  
- May **define tasks for the Next Cycle** themselves with project manager coordination if needed.  

### Visionary Architects (VAs)
- **VAs** for visual tasks, along side writing concise task descriptions, designs views as well.
  - The clearer and more self-explanatory the design, the shorter and more precise the task can be.
- For non-visual projects, VAs should have **technical knowledge** to define what is being built.
- The focus of VAs should be next cycle tasks
- Work with developers, and project managers to **define or refine tasks for the Next Cycle** based on quality insights.
- Ensure requirements, designs, and expected outcomes are prepared before planning.


### QAs (Quality Assurances)
- Ensure deliverables meet quality standards and Definition of Done.
- Perform testing during QA Review stage and provide feedback to developers.
- Help identify potential quality issues early and suggest improvements.

### Project Managers
- Responsible for **deciding next cycle priorities** and ensuring alignment with **OKRs or business requirements**.
- Facilitate coordination and alignment across teams if necessary.

## Cross-Team Coordination
- **Asynchronous Coordination Preferred**
  - Current cycles prepare requirements for other teams’ next cycles.
- **Synchronous Coordination**
  - Use **Cross-Team Planning Sync (CTPS)** only for tightly coupled work.
  - Align cycle endings for teams working in lockstep.

## Meetings
- **Regular Meeting** – Daily or every other day for quick updates.
- **Planning Meeting(s)**
  - Review the previous cycle.
  - Conduct a **Health Check** (rate workload balance, communication, and clarity on a 1–5 scale).
  - Plan tasks for **current cycle only**.
  - Include CTPS if synchronous work is needed.
  - Talk about next cycle task challenges and requirements to make them clear for VAs

## Task Structure
Each task must be clearly define by VAs and include these sections:
1. **As Is** – Current situation.
2. **To Be** – Expected outcome and changes.
3. **Definition of Done (DoD)** – Criteria for approval.
4. **Requirements** – Designs, dependencies, or other assets.
5. **Possible Business Impact** – Accountability for proposed work.

## Labels
You can apply as many labels as you find useful, but **Cycle** defines two primary labels to improve visibility and highlight potential issues:  

- **Carry Over** – A task moved from **Current** in one cycle to **Current** in the next.  
  - Signals possible overcommitment, planning inaccuracies, or areas where team performance or requirements need review.  

- **Vision Drift** – A task that remains in **Next** for multiple cycles without ever moving to **Current**.  
  - Suggests misuse of **Next** as a backlog or unclear upcoming priorities.  
  - May also indicate misalignment between planning and business goals if many tasks are deferred repeatedly.

## Board Structure
The board structure are completely optional but having these columns might help:
1. **Next**
2. **Current**
3. **Doing**
4. **Suspend**
5. **QA Review**
6. **Code Review**
7. **Stakeholder Review**
8. **Ready**

## Scaling Beyond One Team
- Use **asynchronous prep** between teams to reduce conflicts.
- Use CTPS sparingly for synchronous alignment.
- Align release points for interdependent teams.
- Weekly **Cycle Lead syncs** for multi-team communication.

## Metrics and Lightweight Analytics

- **Carry-Over Rate** – The percentage of tasks that slip from one cycle’s **Current** column to the next.  
  - A rising rate suggests overcommitment, unclear requirements, or planning gaps.  

- **Vision Drift Frequency** – How often tasks remain in **Next** for multiple cycles without progressing to **Current**.  
  - Indicates unclear priorities, misuse of **Next** as a backlog, or poor alignment with upcoming goals.  

- **Gap Duration** – The average length of time between cycles.  
  - Long gaps dominated by bug fixes may signal that releases are happening too early or that planning underestimated effort.  

- **Review Stage Dwell Time** – The average time tasks spend in review columns (e.g., Code Review, QA Review, Visionary Review).  
  - Highlights bottlenecks in quality checks, stakeholder alignment, or approval processes.  

- **Team Health Feedback** – Health Check is a simple 1–5 rating gathered during planning meetings on workload balance, communication, and clarity.  
  - Provides a lightweight way to track morale, collaboration effectiveness, and potential burnout risks.  

## When to Use (and Not Use) Cycle
**Cycle** is a methodology—not a silver bullet. No single approach can guarantee success for every team or every kind of software project. If Scrum, Kanban, XP, or another framework or methodology is already working well for your team, you should absolutely continue using it. Cycle is **not intended to replace everything** or dictate a one-size-fits-all process.
Instead, Cycle aims to **open discussions and provide lightweight structure** while leaving many decisions to the team itself. It’s intentionally flexible and minimal, giving teams the freedom to adapt it, mix it with other practices, or abandon parts that don’t fit.  
Ultimately, **you are encouraged to change or discard any part of Cycle** that doesn’t serve your needs. Its value lies in adaptability, not rigidity.
