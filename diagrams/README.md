# System Modeling & Design Artefacts (Part 3)

This directory contains the core architectural and behavioural models for the **Smart Study Planner & Focus Analyzer** project, verified against the Part 2 Software Requirements Specification (SRS).

---

## 📊 Summary of System Models

1. **Use Case Diagram (`Figure 1`)**
   * *Scope:* Models primary user interactions (Student) and administrative tasks (Admin).
   * *SRS Mapping:* Supports FR-01 through FR-15 and defined user roles.

2. **Class Diagram (`Figure 2`)**
   * *Scope:* Details domain classes (`User`, `Course`, `Task`, `FocusSession`, `Analytics`), attributes, operations, and multiplicities.
   * *SRS Mapping:* Supports NFR-05 (Modular Layered Architecture) and core business logic.

3. **Activity Diagram (`Figure 3`)**
   * *Scope:* Visualizes the Pomodoro study session workflow, handling pause/interruption logic and automated database persistence.
   * *SRS Mapping:* Supports FR-09, FR-10, FR-11, and FR-12.

4. **Sequence Diagram (`Figure 4`)**
   * *Scope:* Documents time-ordered messaging between UI, Application Controller, and MySQL Database during session completion.
   * *SRS Mapping:* Supports FR-12, FR-13, FR-14, and FR-15.

5. **Database / Entity-Relationship Diagram (`Figure 5`)**
   * *Scope:* Specifies relational entities (`USERS`, `COURSES`, `TASKS`, `FOCUS_SESSIONS`), primary/foreign keys, and referential integrity.
   * *SRS Mapping:* Forms the data persistence foundation for all functional requirements.
