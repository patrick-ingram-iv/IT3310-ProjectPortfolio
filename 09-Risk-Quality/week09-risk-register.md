# Risk Register: RCHN Patient Intake and Scheduling System

**Consultant:** Patrick Ingram IV  
**Role:** Associate Consultant, NovaTech Consulting  
**Engagement:** Regional Care Health Network (RCHN)  
**Date:** November 2, 2026

---

## Risk Entries

### Risk 1 — Appointment-Data Accuracy

- **Category:** Technical
- **Description:** If unresolved appointment-data discrepancies reach the live system, then incorrect or missing appointments could disrupt patient care.
- **Probability:** High (3)
- **Impact:** High (3)
- **Score:** 9 — High priority
- **Response Strategy:** **Mitigate.** Compare migrated appointment records with source data, correct discrepancies, and verify accuracy before deployment. Postpone rollout if serious errors remain.
- **Trigger or Monitoring Condition:** Unresolved appointment-data discrepancies are identified during final verification.
- **Owner:** **Developer.** Investigates and corrects technical data problems and verifies migrated records. The Project Manager oversees progress and coordinates schedule implications.
- **Status:** Open

### Risk 2 — Employee Training Readiness

- **Category:** Stakeholder
- **Description:** If employees are not fully trained before launch, then scheduling mistakes and patient-service delays could occur.
- **Probability:** High (3)
- **Impact:** Medium (2)
- **Score:** 6 — High priority
- **Response Strategy:** **Mitigate.** Provide training and require staff to demonstrate proficiency. Arrange additional instruction and delay a clinic's deployment if its staff are not ready.
- **Trigger or Monitoring Condition:** Required training is incomplete or staff cannot demonstrate proficiency before their clinic's rollout.
- **Owner:** **Scrum Master.** Helps remove obstacles to training by coordinating with trainers and clinic managers, who deliver instruction and confirm staff readiness.
- **Status:** Open

### Risk 3 — Critical System Testing

- **Category:** Technical
- **Description:** If critical system testing is not completed before launch, then undetected defects could disrupt scheduling across RCHN clinics.
- **Probability:** Medium (2)
- **Impact:** High (3)
- **Score:** 6 — High priority
- **Response Strategy:** **Avoid.** Do not deploy until critical acceptance tests are complete, serious defects are corrected, and acceptance criteria are met.
- **Trigger or Monitoring Condition:** Critical acceptance tests remain incomplete, critical defects are unresolved, or the system fails acceptance criteria.
- **Owner:** **Product Manager.** Coordinates with Developers and testing personnel to verify that the product meets requirements and acceptance criteria; recommends postponing deployment when it does not.
- **Status:** Open

### Risk 4 — Staff and Resource Availability

- **Category:** Resource
- **Description:** If necessary staff and resources become unavailable before rollout, then implementation could face delays, increased costs, and potential scope changes.
- **Probability:** Medium (2)
- **Impact:** High (3)
- **Score:** 6 — High priority
- **Response Strategy:** **Mitigate.** Cross-train qualified personnel, identify backups for critical roles, and adjust workloads to maintain implementation progress.
- **Trigger or Monitoring Condition:** A key team member becomes unavailable or staffing drops below the level needed for scheduled work.
- **Owner:** **Project Manager.** Monitors staffing, coordinates backup personnel, and manages workload and resource adjustments.
- **Status:** Open

### Risk 5 — Critical Project Schedule Delays

- **Category:** Schedule
- **Description:** If critical project activities fall behind schedule before rollout, then the assumed launch before January may not be achievable.
- **Probability:** Medium (2)
- **Impact:** High (3)
- **Score:** 6 — High priority
- **Response Strategy:** **Mitigate.** Monitor critical-path progress and dependencies, address developing backlogs, and adjust resources or timelines without compromising quality.
- **Trigger or Monitoring Condition:** A critical activity slips or threatens a dependent task, milestone, or planned rollout.
- **Owner:** **Project Manager.** Oversees the schedule, dependencies, milestones, and corrective coordination.
- **Status:** Open

---

## Bring Forward

**Week 5 assumptions:**

1. The new system can be launched before January.
2. The necessary staff and resources will be available for implementation and training.

**Week 7 backlog item:** RCHN-101 — Standardize required intake fields (**Must Have**). Consistent fields support accurate patient intake and appointment records.

**Week 8 schedule item:** WBS 3.4 — User acceptance testing during project weeks 12–13, followed by the UAT sign-off milestone.

## Assumption Connection

Risk 4 challenges the Week 5 assumption that necessary staff and resources will be available. Losing staff or resources could threaten planned completion and rollout dates, increase costs, create extra work, and delay implementation across RCHN's six clinics.

Risk 5 challenges the Week 5 assumption that the system can launch before January. Delays in development, testing, or training could create a backlog that is difficult to recover from. The schedule was developed around estimated workloads and completion times; cascading delays could overload the remaining work, place pressure on staff, and jeopardize the assumed launch timeline.

## Score Justifications

**Risk 1 — High probability, High impact (9):** Appointment-data discrepancies were discovered during migration but have not been confirmed as resolved. This raises the likelihood that inaccurate records could reach the live system. The impact is High because incorrect records could cause missed appointments, scheduling conflicts, and disruptions to patient care across six clinics.

**Risk 3 — Medium probability, High impact (6):** Critical acceptance testing was unfinished, leaving the possibility that some defects could go undetected. The probability is Medium because problems are possible but not inevitable. The impact is High because an undetected system problem could disrupt scheduling and patient services, delay rollout, and create additional costs.

## Reflection 1 — Most Important Risk

I consider appointment-data errors the most important risk because inaccurate records could directly affect patient care, scheduling, and confidence in the new system. These errors could also delay go-live, increase project costs, and create additional work for staff.

Critical system testing is closely related because completing testing and correcting serious defects can help prevent these problems before deployment. Although eliminating every software bug may not be realistic, addressing critical problems before launch would allow the team to focus on staff training, accurate data entry, and successful implementation.

## Reflection 2 — Future Risks Versus Existing Issues

Correcting existing problems gives the project team a foundation for preventing and addressing future problems. By identifying what went wrong and how it was corrected, the team can develop better procedures and reduce the likelihood of similar problems occurring again.

The five risks in this register describe uncertain future consequences rather than simply listing conditions that have already occurred. For example, discovered migration discrepancies, incomplete training at two clinics, and unfinished acceptance testing are existing issues; inaccurate appointments, staff errors, and undetected defects disrupting the live system are possible future consequences. Existing issues require corrective action, while risks require monitoring and preventive measures. Understanding the difference helps the team prepare before potential problems disrupt the project.
