consider the content of the followings and wait for my further instructions: 
Hello Everyone,

Please find attached the Minutes of Meeting (MoM) for the Daily Stand-up Meeting (DSM) held yesterday at 12:00 PM.
Minutes of Meeting (MoM)
Connection Enhancement Program (CEP)
DSM - Scope Alignment & Dependency Review
Meeting Date: 16 July 2026
Duration: 35 Minutes
Facilitator: Swati Kothiyal
Attendees: Swati Kothiyal, Subham Srivastava, Heena Malhotra, Kshitij Khshtarpal, Nihardip Sharma, Vinay Yadav, Mayank Tyagi, Gunjan Mathur, Shreenivas, Prayas Ahuja, Rajat Upreti. 

Meeting Objective
Review the status of Release-1 scope under the Connection Enhancement Program, identify blockers, align ownerships, confirm dependencies, and establish action plans for critical EPICs targeted for the August release. 

Executive Summary
The team reviewed critical Release-1 EPICs including Timeline Journey View, Date Change Indicators, Unified Boarding Pass, Static Airport Maps, Transfer Guidance, Operations Dashboard, Connection Status Notifications, and Connection Disruption Management. Major concerns highlighted were delayed user stories, unresolved PSS dependencies, airport map acquisition strategy, notification trigger ownership, and aggressive timelines leading to the 25-Aug release milestone. 

EPIC-wise Discussion, Ownership & Accountability
EPIC 1: Date Change Indicators
Discussion
•	Design inputs have been received.
•	Feedback shared by Subham requires additional discussion with Design.
•	Requirement impacts passenger understanding of itinerary changes and connection journeys.
Owner (Responsible)
•	Subham Srivastava
•	Prayas Ahuja / Design Team
Accountable
•	Swati Kothiyal
Dependencies
•	UX Design Sign-off
•	User Story Completion
•	CX Validation
Risks
🟡 Moderate

Actions
Action Item	Owner	Timeline
Conduct dedicated design brainstorming session on feedback received	Subham, Prayas	Immediate
Finalize design accommodating all user cohorts	Design Team	Within current sprint
Obtain design sign-off	Swati	Before development start

EPIC 2: Timeline Journey View
Discussion
•	Design delivery expected by 25 July.
•	Timeline includes boarding pass, airport information and connection milestones.
•	Design team raised concern over incomplete user stories.
Owner (Responsible)
•	Subham Srivastava
Accountable
•	Swati Kothiyal
Dependencies
•	User Stories
•	PSS Inputs
•	Boarding Pass Data
•	Kafka Event Samples
Risks
🔴 High

Actions
Action Item	Owner	Timeline
Complete all user stories and use cases	Nihardip Sharma	Same day
Share data samples and Kafka payloads	Product & Tech Teams	Current week
Complete design and obtain approvals	Design Team	Before 25 Jul

EPIC 3: Unified Boarding Pass
Discussion
•	Questionnaire shared by Design Team remains unanswered.
•	PSS dependency identified.
•	Eight-week timeline communicated by PSS is impacting planning.
Owner (Responsible)
•	Sachin (PSS)
•	Swati Kothiyal
Accountable
•	Subham Srivastava
Dependencies
•	PSS Integration
•	Boarding Pass Data Availability
•	Design Questionnaire Responses
Risks
🔴 High

Actions
Action Item	Owner	Timeline
Gather responses to design questionnaire	Swati	This week
Obtain phased delivery approach from PSS	Swati, Heena	Immediate
Define Release-1 feasible scope	Product Team	Next DSM

EPIC 4: Static Airport Maps
Discussion
•	Airport maps required to support transfer guidance.
•	Hyderabad identified as potential POC airport.
•	Airports may provide PDFs/JPEG assets instead of APIs.
Owner (Responsible)
•	Vinay Yadav
•	Heena Malhotra
Accountable
•	Swati Kothiyal
Dependencies
•	Airport Operators
•	Airport CIO Coordination
•	Business Requirements Document
•	Product Specification
Risks
🔴 High

Actions
Action Item	Owner	Timeline
Identify POC airport	Heena, Vinay	Immediate
Discuss with Hyderabad Airport CIO	Vinay	Same day
Create one-page product specification	Heena, Product Team	Current week
Assess map formats/API feasibility	Vinay, Tech Team	Current week
Submit recommendation for Release-1	Vinay, Subham	Next DSM

EPIC 5: Transfer Guidance
Discussion
•	Directly dependent on airport map availability.
•	Complex airport layouts need to be considered during design.
Owner (Responsible)
•	Heena Malhotra
Accountable
•	Swati Kothiyal
Dependencies
•	Static Airport Maps
•	Airport POC
•	Design Journeys
Risks
🔴 High
Actions
Action Item	Owner	Timeline
Finalize transfer guidance requirements	Heena	Current week
Align guidance content with airport layouts	CX Team	Post POC
Review with Design & Product	Heena, Subham	Next workshop

EPIC 6: User Stories & Design Enablement
Discussion
•	Design team flagged significant dependency on missing stories.
•	User stories required for all Release-1 items before UX work proceeds.
Owner (Responsible)
•	Nihardip Sharma
•	Elene
Accountable
•	Swati Kothiyal
Dependencies
•	Business Requirements
•	Data Samples
•	Kafka Events
Risks
🔴 High

Actions
Action Item	Owner	Timeline
Complete Release-1 user stories	Nihardip	Same day
Complete all remaining stories	Nihardip	By Friday
Attach sample events and payloads	Product & Tech Teams	Current week

EPIC 7: Baggage Belt, Arrival Gate & Claim Information
Discussion
•	Data appears available in PRMISC.
•	Testing blocked due to non-production validation limitations.
Owner (Responsible)
•	Kshitij Khshtarpal
Accountable
•	Subham Srivastava
Dependencies
•	Kafka Integration
•	GoNow Access
•	Test Environment Updates
Risks
🟡 Moderate

Actions
Action Item	Owner	Timeline
Enable testing in Navigator Test Environment	Kshitij	Immediate
Coordinate GoNow access for development team	Kshitij, Subham	Current week
Validate baggage events	Development Team	Current sprint

EPIC 8: Connection Disruption Management (CDM)
Discussion
•	Solutioning discussion required with Salil and Solution Tech Team.
•	Continue dependency assessment.
Owner (Responsible)
•	Salil
•	Solution Tech Team
Dependencies
•	Solution Architecture
•	Operations Data
•	Notification Framework
Risks
🟡 Moderate
Actions
Action Item	Owner	Timeline
Schedule solution workshop	Swati	Immediate
Finalize technical approach	Solution Team	Current sprint

EPIC 9: Operations Dashboard
Discussion
•	Requirements finalized for Navdeep and UCG.
•	Solution Tech workshop scheduled.
•	Hotels and baggage sources currently unavailable.
Owner (Responsible)
•	Mayank Tyagi
Dependencies
•	Navdeep
•	UCG
•	Solution Tech
Risks
🟡 Moderate

Actions
Action Item	Owner	Timeline
Complete Solution Tech workshop	Mayank	Same day
Finalize solution architecture	Present Team	By Monday
Obtain delivery estimates	Engineering Team	By Monday

EPIC 10: Connection Status Notifications
Discussion
•	Notification delivery expected through Notification Hub.
•	Trigger ownership remains unclear.
•	Transactional messaging to be evaluated.
Owner (Responsible)
•	Mayank Tyagi
•	Ashpreet (Notification Hub)
Dependencies
•	Trigger Source Identification
•	Notification Hub
•	WhatsApp/SMS/Email Channels
Risks
🔴 High

Actions
Action Item	Owner	Timeline
Define notification trigger points	Business Team	Immediate
Confirm source application generating events	Architecture Team	Current week
Arrange detailed requirements workshop	Swati, Heena, Subham, Nihardip	Current week

Key Blockers
Blocker	Impact	Owner
Pending user stories	Design delay	Nihardip
PSS response awaited	Boarding Pass delay	Sachin
Airport map acquisition strategy not finalized	Transfer Guidance delay	Vinay / Heena
Notification trigger ownership unclear	Notification solution blocked	Mayank
Connection disruption solution not finalized	Delivery risk	Solution Tech
Missing business data samples and Kafka events	Design and development delay	Multiple teams

Decisions Taken
1.	Daily DSM to continue for proactive blocker management. 
2.	Hyderabad Airport to be considered as initial POC candidate for Airport Maps. 
3.	User stories to be completed and shared with Design immediately. 
4.	Airport Map solutioning discussions to proceed separately from DSM. 
5.	Unified Boarding Pass dependency and phased delivery to be discussed with PSS offline. 
6.	Operations Dashboard requirements expected to be finalized by Monday. 

Primary Focus for Next DSM: User story completion, PSS alignment, Airport Map POC decision, Notification trigger ownership, and Resolution of Release-1 blockers

Kindly review the minutes and let me know if there are any corrections or additions.


Regards,

Hello All,

As discussed in our previous meetings, a recurring DSM has been scheduled at 12:00 PM, effective 16 July, to regularly review and track the progress of the project.

Please find the attached project tracker for your reference. 
The tracker will be reviewed during each session to monitor progress, discuss dependencies, address any risks or blockers, and ensure alignment on project milestones.

Your timely participation and updates will be appreciated to help keep the project on track.



As discussed yesterday, a meeting will be scheduled to align with the respective SPOCs, and the details will be shared accordingly.

During the meeting, we will address the questions outlined in your email below and provide the necessary clarifications.

Workshops (07 Jul – 10 Jul) – Scope Alignment (Day 4)
Dear All,

Here are the questions we need clarity on Boarding Pass. Wireframes are already shared by Swati in MOM. 

TECHNICAL FEASIBILITY (PSS / AOCS Digital)
1.	Can a single 2D QR code encode IATA BCBP data for both legs, scannable at separate gates?
a.	Impact: If NO → dual barcode per leg (Option A approach) becomes mandatory across all options
2.	Do IndiGo’s gate scanners at ALL stations support 2D QR codes today?
a.	Impact: If NO → QR-based stub in Options B & C is not operationally viable
3.	How are SEQ numbers generated for multi-leg -- per leg independently or from a shared pool?
a.	Impact: If non-sequential, stub design must handle non-ordered SEQ display (e.g. 037 / 214)
4.	What IATA BCBP encoding standard applies to multi-leg? 
5.	Can PSS generate a unified pass at Leg 1 check-in with confirmed Leg 2 seat + gate data?
a.	Impact: If Leg 2 data unavailable at print time, gate/seat fields cannot be pre-filled

OPERATIONS & LAYOUT (Airport Ops / AOCS Business)
1.	Which boarding pass fields are mandatory (regulatory/operational) vs optional (CX-facing)? 
a.	Impact: Determines what can be removed from compressed Leg sections to free up space
2.	Are stub/perforation requirements identical across domestic + international IndiGo stations?
a.	Impact: Option with perforation line may not be operationally supported at all airports
3.	Which team retains the boarding pass stub at each gate? Does the stub differ per leg?
a.	Impact: Determines if a split stub (Option A) or combined stub (Options B) is operationally correct
4.	If Leg 1 is delayed, how is Leg 2 boarding data on the printed pass kept accurate?
a.	Impact: All 3 options are static at print time -- a re-print or dynamic update process is required
5.	How should “Gate TBD” (Leg 2 gate unassigned at print time) be shown on the boarding pass?
a.	Impact: Both options need a graceful unassigned-gate state -- KLM convention uses “--”
6.	How should mixed cabin class per leg (e.g. Economy on Leg 1 + Business on Leg 2) be displayed?
a.	Impact: Visual hierarchy and colour treatment differ per option — needs CX + Business sign-off

REGULATORY & COMPLIANCE (Airport Ops / CX Business)
1.	What DGCA approvals and compliance checks are required before the new format can go live?
a.	Impact: Approval process timeline may push Phase 1 launch date significantly
2.	Are there IATA resolutions or BCBP specifications that restrict the boarding pass physical layout?
a.	Impact: Any IATA-mandated layout constraints override design freedom across all 3 options
3.	Will Phase 1 be domestic connections only, or include international IndiGo connections?
a.	Impact: International adds customs + immigration fields, making the canvas even more space-constrained
4.	What is the regulatory approval timeline -- does compliance sign-off gate the Phase 1 delivery date?
a.	Impact: If compliance is on critical path, engineering delivery may need to wait for approvals

PRODUCT & PHASE PLANNING (Product / Leadership)
1.	Is Journey Timeline better suited as digital/app-only rather than a printed pass? 
2.	If QR feasibility or scanner compatibility fails -- what is the Phase 1 fallback plan?
a.	Impact: Without a fallback, Phase 1 may have no viable option if both critical items block
3.	What is the Phase 1 and Phase 2 timeline estimate for leadership review and commitment? Who is taking that ownership of approval process? 
a.	Impact: Leadership sign-off required before engineering can begin detailed scoping
4.	Should Phase 1 be a pilot at one airport or a full multi-station rollout from day one?
a.	 Impact: A single-station pilot reduces risk but delays benefit realisation for all connecting passengers
5.	Which of the 2 design options does the business want to commit to for Phase 1 scope?
a.	Impact: Option A is lowest risk; Options B require QR feasibility confirmation first
6.	What is the communication and depiction we wanted to convey to customer by putting ‘Heart’ sign in the boarding pass? 

All questions must be answered by the responsible team before the scope is finalised. So UX team can pick up the further design tasks on boarding pass revisions. 


P.S. 

For reference here are 2 options we generated during workshop in high resolutions. 


Hi All,
Please find the minutes of the meeting mentioned below:
Minutes of Meeting (MoM)
Connection Enhancement Program – Scope Alignment & Requirement Workshop
Date: 10 July 2026
Executive Summary
The workshop focused on finalizing Phase-1 scope, design dependencies, boarding pass requirements, connection disruption management, notification strategy, airport maps, and timeline alignment for achieving the first Connection Enhancement Program release targeted for 25 August 2026 and critical operational capabilities before 31 December 2026.
Key Decisions
1.	Real-time connection delay alerts and notifications to be included in Phase-1.
2.	Internal Connection Dashboard and Missed Connection / At-Risk Journey Management moved from Phase-2 to Phase-1 with target delivery before the disruption season.
3.	Static Airport Maps approved for initial implementation due to cost considerations; dynamic maps to be evaluated as a future enhancement.
4.	Unified/Connecting Boarding Pass remains dependent on leadership approval and operational feasibility discussions.
5.	Design work to proceed in parallel while pending operational decisions are escalated.
 
Major Discussion Points
1. Phase-1 Scope Enhancement
Leadership directed that the following be treated as critical Phase-1 deliverables:
•	Connection Delay Notifications
•	Real-Time Connection Alerts
•	Connection Risk Journey Flow
•	Missed Connection Management
•	Internal Operations Dashboard
•	Timeline-Based Passenger Journey Experience
Target Date: Before IROP season (31-Oct-2026)
 
2. Connection Disruption Management
Discussion
The end-to-end disruption handling experience will require integration with the Solution Tech platform to enable:
•	Alternate Flight Recommendations
•	Hotel Suggestions
•	Passenger Protection Journey
•	Missed Connection Recovery Flows
Dependency
Solution Tech Team (Salil / Amar team) to be onboarded.
 
3. Unified / Connection Boarding Pass
Key Concerns Raised
•	Stretch vs Economy identification.
•	Fast Forward entitlement visibility.
•	Lounge eligibility identification.
•	Upgrade journeys across connecting sectors.
•	Ground staff visibility and servicing implications.
•	Boarding pass scalability for future phases.
Open Leadership Decisions Required
1.	How to identify Stretch customers in a unified boarding pass.
2.	Handling mixed cabin itineraries.
3.	Upgrade entitlement management.
4.	Ground operations readiness.
5.	Transit upgrade scenarios.
These items require CX, Airport Operations and Leadership approval before finalization.
2 wireframe options Design team has shared.

 
4. Hub & Spoke Notifications (not a part of the Project)
Discussion
Requirement includes:
•	Connection notifications
•	Delay alerts
•	Sector-specific communication
•	Customer guidance notifications
Pending
Final notification trigger strategy approval:
•	Current proposed trigger: T-24
•	Leadership requested evaluation for earlier communication.
5. Airport Maps
Current Direction
Phase-1 will include:
•	Static airport maps
•	Airport map access points within app journey
 
Future Consideration
•	Dynamic maps
•	Airport APIs
•	Directional guidance
•	Location-aware navigation
Owner from Airport Operations team (Aditya/Gaurav team) to provide airport integration inputs.
 
Action Tracker
ID	Action Item	Owner	Target Date	Dependency	Status
1	Share 54 KPI metrics, supporting slides and Excel	Mayank Tyagi	13-Jul-2026	None	Open
2	Add Connection Delay Alerts and Real-Time Notifications to Phase-1 scope	Subham Srivastava	13-Jul-2026	Leadership direction	Open
3	Share Hub & Spoke requirements, website screenshots, FAQs and process document (Not a part of this project)	Brain Victor Solomon	14-Jul-2026	CX inputs	Open
4	Share Air India implementation benchmarks and comparison	Heena Malhotra	14-Jul-2026	Internal review	Open
5	Organize Solution Tech integration workshop	Swati Kothiyal	14-Jul-2026	Salil, Amar team availability	Open
6	Finalize disruption management approach and recovery flows	Heena Malhotra / Subham Srivastava	18-Jul-2026	Solution Tech workshop	Open
7	Share boarding pass design questions and assumptions	Shreenivas Ransubhe	11-Jul-2026	None	Open
8	Obtain leadership clarification on Stretch/Economy unified boarding pass scenarios	Swati Kothiyal	18-Jul-2026	CX, Airport Ops leadership	Open
9	Validate upgrade and entitlement scenarios for connecting journeys	Airport Operations Team	18-Jul-2026	Leadership inputs	Open
10	Share Date Change Indicator user stories in CEP Board	Swati Kothiyal	13-Jul-2026	None	In Progress
11	Complete Date Change Indicator wireframes	Shreenivas Ransubhe	16-Jul-2026	Stories & requirements	Planned
12	Complete Journey Duration Banner wireframes	Shreenivas Ransubhe	16-Jul-2026	Requirements freeze	Planned
13	Review designs with leadership and CX team	Heena Malhotra, Raja Karmakar	17-Jul-2026	Design delivery	Planned
14	Identify static airport map integration ownership and API feasibility	Aditya / Airport Operations Team	18-Jul-2026	Airport Systems team	Open
15	Collect complaint data related to auto check-in seat allocation failures	Heena Malhotra	22-Jul-2026	Customer complaint data	Open
16	Provide Phoenix user stories and acceptance criteria to Design	Nihardip Sharma / Prayas	15-Jul-2026	Phoenix backlog	Open
 
Timeline Commitments Agreed
Deliverable	Owner	Timeline
Date Change Indicator Design	Shreenivas	16-Jul-2026
Journey Duration Banner Design	Shreenivas	16-Jul-2026
Design Leadership Review	CX & Design Teams	17-Jul-2026
Solution Tech Alignment Workshop	Swati	14-Jul-2026
Boarding Pass Clarification Questions	Shreenivas	Immediate
Airport Maps Ownership Confirmation	Airport Ops Team	18-Jul-2026
Connection Journey & Disruption Logic Review	Solution Tech + CX	Week of 13-Jul-2026
Critical Phase-1 Planning Baseline	Digital Team	25-Aug-2026 Go-Live Target
Internal Dashboard & Risk Connection Flow	Program Team	25-Aug-2026
 
Risks Identified
Risk	Impact	Owner
Unified Boarding Pass operational feasibility unresolved	High	CX + Airport Ops
Stretch/Economy entitlement conflicts	High	Airport Ops
Solution Tech dependency for disruption handling	High	Digital
API integration dependency for airport maps	Medium	Airport Ops
Notification trigger approval pending	Medium	CX Leadership
Auto check-in seat assignment failures impacting customer experience	Medium	Digital + Operations
 
Next Steps (Priority Order)
High Priority (Immediate)
1.	Onboard Solution Tech team for disruption management workshops.
2.	Finalize Phase-1 scope changes and leadership-approved features.
3.	Complete boarding pass clarification discussions.
4.	Deliver initial wireframes by 16-Jul-2026.
5.	Prepare leadership review session on 16-Jul-2026.
 
 

Subject: RE: Connection Enhancement Program : Request for In-Person Requirement Workshops (07 Jul – 10 Jul) – Scope Alignment (Day 3)
 
Hi All,
Please find the Minutes of Meeting (MoM) mentioned below:
Kindly review them and feel free to add any points that may have been missed or highlight any items that require clarification, correction, or further discussion.
Your feedback will help ensure the Minutes of Meeting (MoM) accurately reflects our discussions and agreed actions.
 
=======================================================================================================================================
Date: 09 July 2026

Executive Summary
The workshop focused on:
1.	Finalization of Release-wise delivery approach.
2.	Validation of dependencies for Phase 1 and Release 1 features.
3.	Identification of technical and operational dependencies for:
o	Unified Boarding Pass
o	Static Airport Maps
o	Connection Notifications
o	Operations Dashboard
o	Gate & Baggage Information
4.	Alignment on ownership and workshop cadence.
5.	Acceleration of key customer-facing capabilities into Phase 1 / August release.
 
Key Decisions
Item	Decision
Delivery Approach	Program to be tracked release-wise instead of phase-wise only
DSM Cadence	Dedicated DSM to track feature-level progress and blockers
Connection Notifications	Moved to August release (earlier than planned)
Operations Dashboard	Advanced to August release; workshop required immediately
Airport Maps	Prefer Airport API integration over static image storage approach
Unified Boarding Pass	Requires joint alignment between PSS, CX and Digital
Baggage Belt Information	Feasibility to be assessed using Navitaire "Baggage Reclaim" field
Single Source of Truth	Navitaire to be primary source wherever possible
 
Discussion Summary by Feature
1. Date Change Indicator
Discussion
•	Existing Kafka event framework may support this functionality.
•	Validation required on data source and dependency on PSS.
•	Need detailed review of scenarios.
Outcome
•	Digital team to review Kafka event mechanism.
•	PSS to validate if additional integration support is required.
 
2. Static Airport Maps
Discussion
•	Static storage approach was discussed.
•	CX recommended dynamic airport map updates through Airport APIs.
•	Concern raised regarding outdated maps if maintained manually.
Outcome
•	Airport API integration preferred.
•	AOCS to support API assessment.
 
3. Connection Status Notifications
Discussion
•	Customer notifications identified as critical.
•	Business requested acceleration.
Outcome
Moved to August Release.
 
4. Operations Dashboard
Discussion
•	Dashboard considered critical for disruption handling.
•	Wireframe and requirements workshop required.
Outcome
•	Dashboard delivery advanced to August.
•	Joint workshop mandated.
 
5. Gate & Baggage Belt Information
Discussion
•	Gate information exists in Navitaire.
•	Baggage belt information not currently available.
•	Aditya identified "Baggage Reclaim" field in Navitaire that may support the requirement.
•	Manual update process needs assessment.
Outcome
•	Technical feasibility review required.
•	Single-source architecture preferred.
 
6. Unified Boarding Pass
Discussion
•	Requirement to display:
o	BluChip Tier
o	Heart identifier
o	Consistent boarding pass experience across channels
Concerns
•	Airport-operated kiosks may not support all enhancements.
•	Feasibility depends on PSS pack templates and external kiosk capabilities.
Outcome
•	CX, PSS and Digital including Design Team alignment workshop required.
•	Detailed requirement walkthrough to be scheduled.
 
7. BluChip Tier reflecting on Boarding Pass
Discussion
•	Design and data feasibility to be reviewed.
Outcome
•	Design team will share wireframes for approval.
 
Action Tracker
#	Action Item	Owner	Supporting Teams	Timeline	Dependency	Risk
1	Start DSM governance and weekly feature tracking	Swati Kothiyal	All SPOCs	Immediate (11 Jul 2026)	SPOC availability	Low
2	Finalize Release 1 feature-level delivery plan	Subham	Delivery Team	15 Jul 2026	Requirement sign-off	Medium
3	Validate Kafka event solution for Date Change Indicator	Nihardip / Digital Team	PSS	18 Jul 2026	Kafka event availability	Medium
4	Conduct detailed review of Date Change Indicator scenarios	Sachin Kumar	Digital	16 Jul 2026	Requirement clarity	Medium
5	Assess Airport API availability for airport maps	Aditya Singh (AOCS)	PSS, Airport Ops	18 Jul 2026	Airport vendors	High
6	Finalize Airport Maps implementation approach	Randhir / Digital	CX,PSS, AOCS	22 Jul 2026	API assessment	High
7	Bring Connection Notification feature into August release plan	Arshpreet Narang	Digital, Solution Tek Team	15 Jul 2026	Notification platform readiness	Medium
8	Conduct notification implementation workshop	Swati	Ashpreet, Gulshan, Aditya	17 Jul 2026	Stakeholder availability	Medium
9	Prepare Dashboard wireframe	Raja Karmakar	Mayank	18 Jul 2026	Dashboard requirements	Medium
10	Conduct Operations Dashboard workshop	Swati	Lakshmi, Charu, Mayank, PRISM Team, CX	21 Jul 2026	Wireframe completion	Medium
11	Evaluate Navitaire "Baggage Reclaim" field usage	Randhir Chambail	Aditya Singh, PSS	18 Jul 2026	Navitaire feasibility	High
12	Define solution for Gate and Baggage Belt Information	Digital & AOCS	PSS	24 Jul 2026	Data source confirmation	High
13	Organize Unified Boarding Pass workshop	Swati, Shreenivas	CX, PSS, Digital	16 Jul 2026	Business alignment	High
14	Share boarding pass design samples	Alka Kumari	CX Team	11 Jul 2026	Sample availability	Medium
15	Validate boarding pass printing feasibility across kiosks and channels	Sachin Kumar	PSS, Airport Partners	25 Jul 2026	External kiosk providers	High
16	Review BluChip Tier and Heart display requirements	Sachin Kumar	Loyalty, CIAM, CX	22 Jul 2026	Loyalty data availability	High
17	Identify CIAM/Loyalty system integration requirements	Loyalty Team	Digital, CX	25 Jul 2026	Data mapping	High
18	Capture all program-level blockers and risks in DSM tracker	Swati Kothiyal	PMO	Ongoing	Cross-functional inputs	Medium
19	Finalize Phase 1 scope and sign-off	CX Business Team (Heena/Raja)	Digital, AOCS	31 Jul 2026	Workshop outputs	High
20	Publish consolidated dependency tracker	PMO / Swati	All Workstream Leads	18 Jul 2026	SPOC inputs	Medium
 
Upcoming Milestones
Milestone	Target Date
Requirement Workshop Closure	10 Jul 2026
Solution Finalization	Week of 27 Jul 2026
Release-1 Build Planning	Aug 2026
Connection Notification Delivery	Aug 2026
Operations Dashboard Delivery	Aug 2026
Release 1 Go-Live	25 Sep 2026
Release 2 Go-Live	25 Nov 2026
Release 3 Go-Live	31 Dec 2026
 
Risks & Mitigations
Risk	Impact	Mitigation
Airport API dependency	Delay in maps, gate and baggage features	Early AOCS & PSS engagement
Navitaire integration limitations	Boarding pass enhancements delayed	Early feasibility review with PSS
Boarding Pass Design	BluChip rollout delay	Engagement of CX and Loyalty on the BluChip details
Multiple external airport systems	Inconsistent customer experience	Standardized integration strategy
Manual baggage data updates	Data accuracy issues	Automation assessment using Navitaire fields
======================================================================================================================================

Multiple cross-functional dependencies (PSS, AOCS, Airport APIs, Loyalty, Solution Tech) require closure before solution finalization.
However, Phase 1 scope and delivery dates remain achievable with weekly DSM governance and expedited workshops.
 
Hi All,
Thank you again for today's session.
It was a productive discussion, and we now have initial timelines for the POCs that need to be completed by the respective teams, including AOCS Digital, CX Business, and others.
Going forward, it is important that a CX Business SPOC (either Heena or Raja) is available during the in-person workshops over the next two days.
Since multiple stakeholders are involved in making this project successful, there will likely be several functional and business-related queries that require timely clarification to help us reach conclusions on the requested features and requirements.
==========================================================================================================================================================
Please find below the Minutes of Meeting (MoM):
Meeting Objective
Review Phase 1 and Phase 2 scope, align delivery timelines, discuss technical feasibility and dependencies, and prepare inputs for the leadership review.
Key Discussion Points
1. Phase 1 (0–3 Months) – Quick Wins
The following items were reviewed as Phase 1 deliverables:
•	Date Change Indicator on Website & App
•	Total Journey Banner
•	Single Web Check-in enhancement for connecting flights
•	Static Airport Maps & Terminal Transfer Guide
•	BlueChip Identification on Boarding Pass
•	Initial boarding pass design improvements
 
Discussion Points
•	Single Web Check-in requires additional validation for 48-hour connection scenarios.
•	Static Airport Maps and Terminal Transfer Guide remain dependent on PSS feasibility and data availability.
•	Design team highlighted bandwidth constraints and advised that all initiatives cannot run fully in parallel.
•	Timelines presented are indicative and subject to dependency and approval closures.
 
2. Phase 2 (3–6 Months) – Advanced Capabilities
The following items were proposed under Phase 2:
•	Unified Boarding Pass
•	Live Baggage Tracking
•	Operational Connection Monitoring
•	Automated Misconnection Recovery
•	Internal Monitoring Dashboard (CX & Airport Teams)
•	Gate/Belt Push Notifications
 
Discussion Points
•	Operational Connection Monitoring will leverage Kafka event streams, MCT tables, ETA/ETD data, and Solution Tech logic.
•	OCC representative (Vijender) will be engaged to validate data points and operational workflows.
•	Additional workshop required with OCC, Network Planning, CX and Design teams.
 
3. Live Baggage Tracking – Feasibility Review
Detailed discussion was conducted with Digital and Innovation teams.
Key Outcomes
•	Technical capability exists to track baggage events through Kafka-based integrations.
•	Current visibility is limited to airports where IndiGo BRS capabilities are available.
•	Additional scanning touchpoints can be enabled subject to AOCS operational approval.
•	MVP approach preferred for Phase 1.
 
Proposed Initial Customer Touchpoints
1.	Bag Checked-in
2.	Bag Transferred to Connecting Flight
3.	Bag Loaded on Flight
4.	Bag Arrived at Destination Belt
 
Dependencies
•	AOCS manpower and process readiness
•	Hardware/sensor deployment and POC completion
•	Leadership approval for operational changes
 
4. Baggage Tracking POC
•	Vendor to perform airport measurements and hardware assessment next week.
•	Estimated POC preparation timeline: approximately 15–20 days post assessment.
•	Weekly review cadence to be established for POC progress tracking.
•	Vinay/Randhir team to share event definitions, technical feasibility details and proposed solution approach.
 
5. Unified Boarding Pass Discussion
Multiple boarding pass concepts were reviewed.
Key Decisions
•	Two design options will be explored:
o	Dual Barcode Model (one barcode per leg)
o	Single Barcode Model (all journey information in one barcode)
Inputs Required
•	Mandatory boarding pass fields from AOCS/Operations.
•	Regulatory and BCAS compliance requirements.
•	Sample boarding passes from other airlines supporting multi-sector journeys.
•	Barcode feasibility assessment by PSS team.
 
Feedback Received
•	SSR information must remain visible on the passenger section of the boarding pass.
•	Readability of all passenger information must be maintained.
•	Business, BlueChip and loyalty-related information must be accommodated.
•	Airport Operations team to provide field-wise validation and boarding pass requirements.
 
Action Items
Action Item	Owner	Timeline
Finalize and present Phase 1 & Phase 2 roadmap for leadership review	Heena / Swati	Immediate
Share updated baggage tracking feasibility and event details	Vinay / Randhir	Next Working Day
Arrange OCC workshop with Vijender and Network Planning team	Heena	Tomorrow  (09Jul)
Define operational connection monitoring data points	OCC + CX + Digital	Workshop Session
Share mandatory boarding pass field requirements	AOCS Team (Akshita/Alka/Kshitij)	ASAP
Share sample multi-sector boarding passes from other airlines	AOCS Team (Akshita/Alka/Kshitij)	ASAP
Conduct barcode feasibility assessment	Sachin (PSS)	Post receipt of samples
Track baggage POC progress through recurring reviews	Swati / Subham / Vinay	Weekly
Consolidate feature-wise dependencies and approvals	Prayas / Swati	Ongoing
 
Risks & Dependencies
•	PSS feasibility for airport maps and transfer guide.
•	AOCS approval and operational buy-in for baggage tracking enhancements.
•	Availability of real-time event feeds and simulation environments.
•	Design bandwidth constraints across multiple concurrent initiatives.
•	Regulatory and boarding pass compliance approvals.
 
Next Steps
•	Continue requirement workshops feature-by-feature.
•	Review dependencies, approvals and technical feasibility in daily cadence.
•	Present phased roadmap, timelines and identified dependencies to leadership.
•	Conduct in-person workshop with all required stakeholders for detailed requirement finalization.
 
==========================================================================================================================================================
Additionally, please note that the final implementation timelines, along with specific dates, can only be shared after:
•	Detailed discussions on the Phase 1 and Phase 2 scope are completed.
•	Analysis and POCs are finalized by the respective teams, accordingly the design team shares the final wireframes.
 
This approach will help us provide realistic and well-aligned delivery timelines while ensuring all dependencies are adequately addressed.
 
 
Hi All,
Thank you for attending the first day of the workshop.
I sincerely appreciate everyone who took the time to actively participate, share valuable inputs, and discuss the project's risks, dependencies, and key considerations.
Please find the Minutes of Meeting (MoM) mentioned below:
Kindly review them and feel free to add any points that may have been missed or highlight any items that require clarification, correction, or further discussion.
Your feedback will help ensure the Minutes of Meeting (MoM) accurately reflects our discussions and agreed actions.
 
======================================================================
Minutes of Meeting (MoM)
Connection Enhancement Program – Requirement Workshop (Scope Alignment) Date: 07 July 2026
Key Discussion Points
1.	Requirement workshops initiated to clarify CX requirements, user journeys, task flows, design considerations, and implementation feasibility.
2.	Multi-Leg / Unified Boarding Pass identified as the primary feature for discussion.
3.	Unified Boarding Pass has been proposed for Phase-1 delivery, subject to leadership alignment and feasibility assessment.
4.	Cross-functional teams reviewed business, airport operations, AOCS, PSS, product, design, and technology implications.
5.	Multiple operational dependencies were identified around:
o	Sequence numbers for each flight leg
o	SSR handling
o	Boarding pass perforation/stub requirements
o	QR code feasibility
o	Airport scanner compatibility
o	Boarding pass layout constraints
o	Regulatory and operational approvals
 
Ownership & Approval Matrix
Area	Owner(s)	Responsibility
CX Requirement Sign-off	Naresh Rao, Summi Sharma	Final business requirement approval
Product Ownership	Swati Kothiyal, Rajat Upreti, Nihardip Sharma	Product governance, prioritization, requirement alignment
Design & UX	Shreenivas S. Ranasubhe, Gunjan Mathur, Prayas, Ishika Verma	User flows, boarding pass design, prototypes
Airport & CX Business	Heena Malhotra, Naresh Rao, Raja Karmakar	Business requirements and operational approvals
AOCS (Digital)
AOCS (Business)	Kshitij Khshtarpal, Mohit Goyal, Randhir Chambail
Gaurav Malhotra, Prativa Biswal, Mansi Negi	Operational feasibility, boarding validation, airport process impacts
PSS	Sachin Kumar, Purnima	Boarding pass generation, barcode and QR feasibility
Salesforce / Data	Mayank Tyagi, Lakshmi Gopalkrishnan	Platform feasibility and integration assessment
Development & Architecture	Subham Srivastava	Technical architecture and implementation approach
Testing Lead	Vishal, Brian	End-to-end validation and operational testing
 
Decisions Taken
#	Decision	Owner
1	Unified Boarding Pass to be assessed for inclusion in Phase-1.	CX Business
2	Connecting Journey Tag is a mandatory boarding pass element.	Airport, CX Business
3	Trip Member details are mandatory.	Airport, CX Business
4	Sequence numbers for both flight legs must be displayed.	AOCS (Digital)
5	SSR information cannot be removed from boarding passes.	AOCS (Digital)/ Airport Operations
6	Boarding pass design must support operational stubbing/perforation requirements.	AOCS (Digital) / Design
7	Feasibility of single QR code for multiple legs requires technical validation.	PSS , AOCS, CX Business
8	Airport scanner compatibility must be validated before finalizing QR solution.	PSS , AOCS, CX Business
 
Action Items
Action Item	Owner	Support Team	Priority
Finalize ownership and sign-off matrix for all features.	Swati Kothiyal	CX, Airport Teams, Product, PSS, AOCS, Design	High
Produce detailed Unified Boarding Pass design options.	Shreenivas S. Ranasubhe	Product, Airport Ops	High
Define mandatory vs optional boarding pass fields.	Heena Malhotra	AOCS, PSS	High
Validate sequence number handling for both flight legs.	Mohit Goyal, Kshitij	PSS	High
Assess feasibility of single QR code covering multiple legs.	Randhir Chambail, Vinay Yadav	PSS, AOCS	High
Confirm airport infrastructure compatibility with 2D QR codes.	Sachin Kumar	Airport Operations	High
Obtain Air France/KLM/Etihad boarding pass examples with scannable barcode quality.	Sachin Kumar	PSS	Medium
Validate SSR display requirements and space constraints.	Alka Kumari, Akshita Paul	Design Team	High
Review boarding pass stub/perforation requirements across domestic and international stations.	Mohit Goyal	Airport Operations	High
Prepare timeline estimate for Phase-1 and Phase-2 items for leadership review.	Swati Kothiyal, Rajat Upreti	Design, Tech, CX, AOCS, PSS	High
Conduct airport testing once QR feasibility solution is available.	Heena Malhotra, Brian	PSS, Airport Ops	High
 
Risks & Open Questions
Open Item	Owner
Can one QR code support both flight legs without operational impact?	PSS / AOCS
Will airport scanners and gate devices support new QR format?	PSS
How will boarding pass information be accommodated within size constraints?	Design Team
How will boarding pass data remain accurate if downstream flights are delayed?	CX / Airport Operations
How should SSR information for multiple legs be displayed?	AOCS / PSS
What approval, compliance, and regulatory checks are required prior to rollout?	Airport Operations & CX Team
 
Summary
The workshop established ownership across Product, CX, Design, AOCS, PSS, Airport Operations, and Development teams. The primary focus was the Unified Boarding Pass feature.
While business teams confirmed the mandatory information required on the boarding pass, several feasibility assessments remain open, particularly around QR code implementation, scanner compatibility, SSR handling, and operational boarding pass validation. A detailed design and technical assessment will be completed before final commitment into Phase-1 delivery.
 
======================================================================
Thank you once again for your support and collaboration.
 
Hi All,
As per the email below, the venue for the workshop has been changed to GBP Tower-D, Room D5-505.
All large-capacity meeting rooms in Emaar 1 and Emaar 2 are fully booked.
Accordingly, we will be conducting the workshop at the revised venue mentioned above.
 
Thank you for your continuous support.
Hi Heena,
As part of the ongoing planning and alignment activities for the finalizing the scope, we would like to request a series of requirement workshops with you and your team, along with the Design team, starting from 07 July through 10 July.
To facilitate effective collaboration and faster decision-making, we would prefer these workshops to be conducted in person.
Workshop Details:
•	Dates: 07 July – 10 July
•	Time: 15:30 hrs – 17:30 hrs
•	Mode: In-Person
•	Participants: CX Business Team, Design Team, Product Owners, and relevant stakeholders
We request you to kindly confirm:
1.	Your availability and the availability of the relevant team members for the proposed dates and timings.
2.	The preferred venue/location for conducting the workshops.
The objective of these sessions is to finalize and align the requirements for the items (especially Phase 1), enabling the Design team to proceed with design planning and subsequently allowing the Web and App development teams to provide effort estimations and delivery timelines.
Action Plan
Action Item	Owner	Target Date
Confirm venue/location for workshops	Heena & CX Business Team	07 Jul 2026
Conduct requirement workshops and align requirements (especially Phase 1)  	CX Business Team, Design Team, Product Owners	07 Jul 2026 – 10 Jul 2026
Share design completion ETA for approved requirements	Design Team	Post workshop completion
Provide development effort estimates and timelines	Web & App Teams	After design ETA is shared
 
We look forward to your confirmation and support in ensuring the successful completion of these workshops.
 

