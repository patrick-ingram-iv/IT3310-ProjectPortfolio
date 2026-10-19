# Product Backlog: RCHN Patient Intake and Scheduling System
**Consultant:** Patrick Ingram IV  
**Role:** Associate Consultant, NovaTech Consulting  
**Engagement:** Regional Care Health Network (RCHN)  
**Date:** October 19, 2026

---

## Product Backlog

### Story 1 — RCHN-101: Standardize Intake Fields
**User Story:** As a clinic intake coordinator, I want to use standardized patient intake fields across all six clinics, so that patient information is recorded consistently and staff can work more efficiently.

**Acceptance Criteria:** Given an intake coordinator opens a patient intake form, when they enter patient information, then the same required fields and field labels appear across all six clinics.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### Story 2 — RCHN-102: Confirm Patient Identity
**User Story:** As a clinic intake coordinator, I want to verify a patient's identity before completing intake, so that patient information is associated with the correct record.

**Acceptance Criteria:** Given an intake coordinator selects a patient record, when they begin intake, then the system requires identity confirmation before the intake process can be completed.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### Story 3 — RCHN-103: Show Appointment Availability
**User Story:** As a clinic scheduling staff member, I want to view available appointment times across all six clinics, so that I can schedule patients without unnecessary delays or confusion.

**Acceptance Criteria:** Given a scheduling staff member selects a clinic and date, when they check appointment availability, then the system displays available time slots and excludes already booked appointments.

**Story Points:** 8  
**MoSCoW Priority:** Must Have

### Story 4 — RCHN-108: Warn About Scheduling Conflicts
**User Story:** As a clinic scheduling staff member, I want to receive a warning when an appointment conflicts with an existing booking, so that I can resolve scheduling conflicts before confirming an appointment.

**Acceptance Criteria:** Given an appointment time overlaps an existing booking, when a staff member attempts to schedule it, then the system displays a conflict warning before the appointment is confirmed.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### Story 5 — RCHN-104: Flag Missing Intake Information
**User Story:** As a clinic intake coordinator, I want to receive alerts when required patient intake information is missing, so that I can correct incomplete records before finishing intake.

**Acceptance Criteria:** Given required intake information is missing, when an intake coordinator attempts to complete the form, then the system identifies the missing fields and prompts the coordinator to complete them.

**Story Points:** 3  
**MoSCoW Priority:** Should Have

### Story 6 — Staff Mobile Application
**User Story:** As a clinic staff member, I want to access the intake and scheduling system through a mobile application, so that I can review scheduling information when away from my workstation.

**Acceptance Criteria:** Given an authorized clinic staff member signs in to the mobile application, when they select the appointment schedule, then the application displays scheduling information for their assigned clinic.

**Story Points:** 8 (preliminary future-work estimate)  
**MoSCoW Priority:** Won't Have This Time

---

## Prioritization Rationale

### Must Have Justification
I classified RCHN-108, Warn About Scheduling Conflicts, as a Must Have because scheduling reliability is one of the main problems RCHN needs to address. The Week 3 research identified uncertainty about saved appointments and the possibility of double bookings. A warning system would help staff identify overlapping appointments before confirming them, reducing scheduling errors and unnecessary work.

This requirement is essential to the current planning horizon because replacing the scheduling system without addressing existing conflicts would leave a major problem unresolved. However, Must Have does not necessarily mean the story must be completed in the first Sprint. Its implementation should be coordinated with appointment availability and the team's development priorities.

### Won't Have Rationale
I classified the staff mobile application as Won't Have This Time because it falls outside the Phase One scope established in my Week 5 assignment. Although a mobile application could be useful for clinic employees, the immediate priority is replacing the intake and scheduling system and establishing a consistent workflow across all six clinics.

Developing a mobile application now would require additional time, funding, and resources without directly addressing the most urgent scheduling problems. I would reconsider this feature in a future phase if clinic staff demonstrated a clear need for mobile access, the sponsor approved expanding the scope, and sufficient resources became available. Until then, the team should concentrate on the approved Phase One priorities.

---

## Backlog Reflection

### Persona Connection
RCHN-108, Warn About Scheduling Conflicts, connects directly to my Week 3 user persona, Alfred, an intake coordinator. One of Alfred's main frustrations was that the current system does not always confirm whether appointments were saved successfully. This uncertainty can lead to double bookings and additional work for clinic staff.

A scheduling conflict warning would help address this problem by alerting staff when an appointment overlaps an existing booking. This supports Alfred's goal of completing intake and scheduling accurately and efficiently while improving scheduling reliability across RCHN clinics.

### Scope Connection
RCHN-101, Standardize Intake Fields, connects directly to my Week 5 scope definition, which included standardizing patient intake workflows across all six RCHN clinics. The purpose was to create a more consistent process and reduce confusion caused by different procedures at each location.

This backlog item turns that broader scope requirement into a specific capability for the development team. By requiring the same intake fields and labels across all six clinics, it establishes a clear expectation that developers can implement and test. This helps ensure the completed system supports the consistency identified as a Phase One priority.

---

*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
