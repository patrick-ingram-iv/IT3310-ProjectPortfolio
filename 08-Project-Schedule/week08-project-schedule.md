# Project Schedule: RCHN Patient Intake and Scheduling System

**Consultant:** Patrick Ingram IV
**Role:** Associate Consultant, Project Manager, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** October 26, 2026

---

## Work Breakdown Structure

### Grouping 1: Project Initiation and Setup
- 1.1 Finalize project charter
- 1.2 Confirm stakeholder register
- 1.3 Conduct project kickoff meeting

### Grouping 2: Project Planning and Backlog Preparation
- 2.1 Finalize prioritized product backlog
- 2.2 Define sprint schedule and cadence
- 2.3 Document technical constraints

### Grouping 3: System Development and Configuration
- 3.1 Configure standardized patient intake workflows
- 3.2 Build appointment scheduling module
- 3.3 Conduct user acceptance testing

### Grouping 4: Clinic Deployment and Project Closure
- 4.1 Train clinic staff and conduct pilot rollout
- 4.2 Deploy scheduling system to all six clinics
- 4.3 Provide 90-day rollout support and project handoff

### WBS Rationale
The WBS reflects the scope established in Week 5 by organizing the RCHN project into four major groupings: initiation, planning, development, and deployment/closure. Initiation establishes the project charter and stakeholders. Planning organizes the prioritized backlog, sprint schedule, and technical constraints. Development covers the standardized patient intake workflows, appointment scheduling module, and user acceptance testing. Deployment and closure include staff training, the pilot rollout, implementation across all six clinics, and 90 days of post-rollout support.

Some activities are combined to keep the WBS manageable. Staff training and the pilot rollout are grouped together, while rollout support and final project handoff are included in the last work package. The patient-facing scheduling portal, billing integration, executive reporting dashboard, and mobile application remain outside the approved project scope. No additional scope is being introduced.

---

## Task Dependencies
- Finalize project charter → Confirm stakeholder register, Finish-to-Start (FS)
- Configure standardized patient intake workflows → Build appointment scheduling module, Start-to-Start (SS)
- Build appointment scheduling module → Conduct user acceptance testing, Finish-to-Start (FS)

### Dependency Logic
One important dependency is completing the appointment scheduling module before user acceptance testing (UAT) can begin. This is a Finish-to-Start relationship because the scheduling functionality must be ready before clinic representatives can properly test it.

If development slips by two weeks, UAT could also begin two weeks late. This could delay UAT sign-off, staff training at the pilot clinic, and the pilot go-live milestone. If those activities are on the critical path and have no available float, the delay could affect the overall project completion date.

The project team could review available float, adjust resources, or prepare training materials in parallel to reduce the impact. However, testing and required approvals should not be skipped just to meet the original schedule.

---

## Activity Schedule

| ID | Activity | Duration (working days) | Predecessors | Start week |
|---|---|---:|---|---:|
| A | Confirm intake requirements | 5 | None | 1 |
| B | Configure standardized intake workflow | 10 | A | 2 |
| C | Develop staff training materials | 5 | A | 2 |
| D | Conduct intake workflow testing | 5 | B,C | 4 |

### Scheduling Gap Explanation
Activity D begins in Week 4 because it must wait for both Activities B and C to finish. Although Activity C finishes in Week 2, Activity B requires 10 working days and does not finish until the end of Week 3. Therefore, Week 4 is the earliest feasible start for Activity D. The waiting time is caused by the dependency on Activity B, not an unnecessary scheduling delay.


### Scheduling Assumptions
I estimated the activity durations using five working days per week and the complexity of each task. Confirming intake requirements should take approximately five days. Configuring the standardized intake workflow will take longer, so I allowed ten days. Developing staff training materials and conducting initial workflow testing are each estimated at five days.

Activity A begins in Week 1. Activities B and C can both begin in Week 2 because they depend on completing the requirements, but they can proceed in parallel. Activity D begins in Week 4 because configuration takes two weeks and both configuration and training materials must be completed before testing begins.

These are preliminary estimates rather than approved dates. One uncertainty is whether clinic representatives will be available to review and test the new workflows. Delayed feedback or additional configuration changes could extend the schedule.

---

## Milestones and Critical Path

### Milestone 1: User Acceptance Testing Completed and Approved
**Target:** End of Project Week 14

**Exit Criterion:** User acceptance testing has been completed, critical defects have been resolved, and authorized RCHN representatives have formally approved the results.

### Milestone 2: Pilot Clinic Successfully Launched
**Target:** End of Project Week 16

**Exit Criterion:** The pilot clinic is using the new intake and scheduling system, staff training is complete, and the project team has confirmed that the system is functioning without unresolved critical issues.

### Critical Path Analysis
The first path, A → B → D, takes 3 + 4 + 2 = 9 working days. The second path, A → C → D, takes 3 + 6 + 2 = 11 working days.

The critical path is A → C → D because it is the longest dependent path. The minimum project completion time is 11 working days.

If an activity on the critical path is delayed by two working days and no corrective action is taken, the project could take 13 working days instead of 11. The A → B → D path has two days of float, so a delay of up to two days on activity B would not necessarily change the original completion date.

This calculation is a separate practice exercise and does not represent the full RCHN project schedule developed in Excel.

---

## Schedule Reflection

### Scope Connection
The System Development and Configuration grouping connects directly to the Week 5 project scope, which identified standardized patient intake and improved appointment scheduling as major deliverables for RCHN.

The work packages include configuring standardized intake workflows, building the appointment scheduling module, and conducting user acceptance testing. These activities support the project's goal of replacing inconsistent procedures across the six clinics with a more reliable and standardized system.

This grouping stays within the established project scope and does not include excluded features such as patient-facing online scheduling or billing integration.

### Objective Connection
The User Acceptance Testing Completed and Approved milestone supports RCHN's objective of improving the reliability and consistency of patient intake and appointment scheduling.

Completing UAT helps confirm that the new system meets the documented requirements before deployment begins. It also provides an opportunity for clinic representatives to identify problems that could affect daily operations.

The proposed target is the end of Project Week 14. This is a planning estimate, not an approved deadline. The project team would need to confirm testing resources, clinic representative availability, acceptance criteria, and the approval process before finalizing this milestone.


