# Communication Plan: RCHN Patient Intake and Scheduling System
**Consultant:** [Osazee John Alohan]
**Role:** Project Manager, NovaTech Consulting
**Engagement:** Riverside Community Health Network (RCHN)
**Date:** November 17, 2026

---

## Communication Matrix

### Entry 1
**Stakeholder:** RCHN Chief Medical Officer
**Information Needed:** Clinical workflow alignment, patient safety standards, and system integration updates
**Timing / Trigger:** Throughout planning, workflow design, and system testing
**Frequency:** Weekly
**Format:** Status email
**Owner:** Product Manager
**Method:** Push

### Entry 2
**Stakeholder:** RCHN Board of Directors
**Information Needed:** High-level project progress, budget status, and major scope or timeline decisions
**Timing / Trigger:** At major project milestones, phase gates, and executive reviews
**Frequency:** Bi-weekly
**Format:** Executive summary
**Owner:** Project Manager
**Method:** Pull

### Entry 3
**Stakeholder:** Clinic Intake Coordinators
**Information Needed:** System usability updates, standardized intake field changes, and staff training steps
**Timing / Trigger:** During prototype testing and prior to the six-clinic launch
**Frequency:** Weekly
**Format:** Plain-language briefing
**Owner:** Project Manager
**Method:** Push

### Entry 4
**Stakeholder:** Patients
**Information Needed:** New check-in procedures, appointment scheduling instructions, and launch dates
**Timing / Trigger:** Immediately prior to and during the six-clinic system rollout
**Frequency:** As-needed
**Format:** Plain-language briefing
**Owner:** Project Manager
**Method:** Push

### Entry 5
**Stakeholder:** RCHN IT Support
**Information Needed:** Technical architecture, server load requirements, and EHR data integration troubleshooting
**Timing / Trigger:** During the technical design and system integration testing phases
**Frequency:** Weekly
**Format:** Meeting
**Owner:** Project Manager
**Method:** Interactive

### Communication Method Justification
I chose Pull for the RCHN Board of Directors because the information is big-pictured and reference-based, and our Week 4 analysis showed they have a High Influence and High Interest but they do not manage daily project tasks.
This means Pull is appropriate because placing executive summaries on a self-service dashboard lets Board members check project progress and budgets whenever they are ready for a decision.

I chose Interactive for RCHN IT Support because the information is complex and urgent, and our Week 4 analysis showed they have High Influence and High Interest in keeping the servers running during busy clinic hours.
This means Interactive communication is appropriate because the live meetings let the team ask questions, solve technical problems fast, and make sure the system is ready to launch.

---

## Escalation Path
* **Level 1: Project Manager**, handles issues that can be resolved at the team level within 24 hours. Triggered when a daily task, minor technical bug, or scheduling conflict happens that stays within the current project budget and timeline.

* **Level 2: RCHN Chief Medical Officer (with RCHN IT Support)**, handles issues that require client-side involvement. Triggered when a problem affects clinic workflows, internal IT systems, or cannot be fixed by the team alone within 24 hours.
            Expected response time: 48 hours (planning recommendation).

* **Level 3: RCHN Board of Directors (and Executive Sponsor)**, handles issues that require executive decision-making. Triggered when an unresolved issue threatens major project deadlines, requires extra budget, or creates serious legal or patient privacy risks.
            Expected response time: 72 hours, or 24 hours for urgent safety/compliance issues (planning recommendation).

### Escalation Scenario
If the failed data integration between the new intake system and RCHN's existing Electronic Health Record systems materialized, the escalation would unfold as follows:

* **Step 1:** The Project Manager would work with the development team to test backup fixes and assess the delay because they own Level 1 resolution and must try to solve technical problems at the team level first.

* **Step 2:** If not resolved within 24 hours, the Project Manager would escalate to the RCHN Chief Medical Officer and RCHN IT Support because fixing the connection requires access to RCHN's internal servers and decisions 
on how clinic staff should handle patient check-ins during the outage.

* **Step 3:** The final escalation level would involve the RCHN Board of Directors because a prolonged EHR failure delays the six-clinic launch, requires extra emergency funding to fix, 
and needs executive approval to adjust the project scope or timeline.

---

## Connection to Prior Artifacts
* **Connection to Week 4 stakeholder register:** My communication plan entry for RCHN IT Support was shaped by their High Interest / High Influence classification because they keep the clinic servers running during busy hours,
                                                 so they need weekly live meetings instead of basic emails.


* **Connection to Week 8 project schedule:** The 6 clinic launch phase from Week 8 drove my decision to send more frequent, plain-language briefings for Clinic Intake Coordinators and Patients because 
                                             the front-desk staff need training and the patients need clear check-in instructions right before launch day.


* **Connection to Week 9 risk register:** My escalation path was shaped by the failed data integration with RCHN's Electronic Health Record system from the risk register because if this risk materializes,
                                          NovaTech cannot fix it alone and they have to quickly alert RCHN IT Support, the Chief Medical Officer, and the Board for the launch to not be delayed.

---

## Gap Analysis
### Communication Gap
The gap I identified in my communication plan is that Healthcare Privacy Regulators were left out of the five communication matrix entries, so there is no scheduled check-in to review patient data privacy. 
This matters for the RCHN engagement because the new intake system collects private patient health records, and breaking privacy rules could stop the launch or cause legal fines. 
To fix this gap I would add a row for a Privacy Compliance Reviewer with Interactive meetings at major milestones because checking privacy rules early prevents expensive fixes later.

### Silence as a Communication Decision
A situation where NovaTech silence could create a stakeholder problem is during back-end coding and system testing, when the team is working behind the scenes without visible screen updates. 
Even though the project is on track, the RCHN Chief Medical Officer and Clinic Intake Coordinators might assume that work has stopped or the team is ignoring their clinic workflow needs because they cannot see any new features yet. 
My communication plan prevents this by sending weekly status emails to the Chief Medical Officer and weekly plain-language briefings to Clinic Intake Coordinators, which keeps everyone updated on behind-the-scenes progress even when nothing looks new on screen.
