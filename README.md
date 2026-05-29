from the vendor prospective, please create a table showing critical gaps observed in the answers made by the business team  under indigo response: 
Query ID	RFP Section / Source Document Reference	Core Evaluation Context	Explicit Vendor Question to Sourcing Team	IndiGo Response / Operational Notes
1	Techno-Commercial Proposal Sheet	The template requires fixed line-item pricing for subscriptions, but the scope files do not define the necessary traffic metrics required to select the correct product capacity tiers.	Could IndiGo provide the specific annual volumetric baselines required for our pricing calculations, explicitly: (a) Estimated annual pageviews/impressions for Web digital intercepts? (b) Monthly Active Users (MAUs) across native iOS and Android mobile apps? (c) Target annual session recording/replay counts for the behavioral analytics engine?	Avg. traffic on the Indigo website for last 12 months is about 430 million users. Last 6 months avg. MAU for android and iOS apps is 13 Lakh and 9.5 Lakh respectively
2	"Technical Specifications & SOW
(Final-Customer Experience (CX) feedback -RFP)"	The document outlines an extensive omnichannel operational lifecycle (check-in, lounge, boarding, inflight, baggage) via Email, SMS, and WhatsApp, which follows a response-based commercial architecture.	What is the targeted or budgeted annual survey response volume intended for the core operational CX program (outside of digital website feedback) so we can align the platform subscription tier?	Not applicable as the document titled "Final - Customer Experience (CX) Feedback – RFP" is not a valid document
3	"Functional Detailed Requirements
(Integrations Section - Both RFP Docs)"	The scope text details requirements to pass experience data to 'Systems of Action' and trigger real-time operational responses but leaves the destination software unnamed.	Which specific downstream corporate systems (e.g., specific CRM tools, ticketing platforms, or internal databases) must the platform integrate with natively via Webhooks or APIs to trigger your real-time operational workflows?	Integration is expected with CRM (Salesforce), customer support systems, internal data platforms, and workflow/ticketing tools. Detailed API specifications will be shared during implementation.
4	"Technical Specifications
(Session Replay - Digital Experience RFP)"	The document outlines strict session replay diagnostic requirements across web checkout and check-in paths where third-party frames are often utilized.	Are any core stages of the web booking, payment gateway, or web check-in flows hosted within cross-domain iframes? (Note: Modern browser privacy settings such as Apple ITP automatically block session tracking layers within cross-domain iframes).	Certain components (e.g., payment gateway and third-party integrations) may operate via cross-domain iframes. Vendors should propose feasible tracking approaches considering browser limitations.
5	CX: Journey-Level Feedback Collection	"Journey-Level Feedback Collection	
•	Flight Search Page
•	Passenger Details
•	Add-ons selection
•	Payment Page
•	Booking Confirmation
•	Web Check-in funnel"	"We consider 1 Survey per Journey Touchpoints (Flight Search Page, Passenger Details, Add-ons selection, Payment Page, Booking Confirmation, Web Check-in funnel). 
i.e. total 7 surveys. Please let us know if there are additional surveys you plan to cover in the initial implementation"	These surveys will work for the initial implementation phase
		General - Document focus on digital touchpoint for DX and CX surveys.  Confirmation on the distribution channels	"Considering the focus on the digital journey, we have identified digital intercepts on the website/app as a key channel to display the survey.
Please let us know if you also intend to distribute the survey through communication channels such as Email, SMS, or WhatsApp. In the case of SMS or WhatsApp, kindly confirm whether you have an existing provider for integration (e.g., Twilio, Sinch, etc.)."	In the initial implementation, the surveys will be on the digital journeys only and will not be distributed via other communication channels
		General - Confirmation on the languages	"We observed that the website is currently available only in English; however, certain touchpoints such as the chatbot support multiple languages.
Could you please confirm if it is acceptable to consider English as the only language for survey translations? Let us know if any other language translations should be considered."	Yes, only English can be considered for now
6	CX 2.2 Real-Time Journey Intervention & Recovery: Ability to redirect users to assisted channels (chat, callback, help desk, agent)	Confirmation on the Assisted channels	"We assume that the requirement involves redirecting users to pre-existing assisted channels of IndiGo, and that the IndiGo team will provide the relevant redirect links.
Please let us know if there are any additional expectations around integration with an AI agent or any external systems."	Not applicable as the document titled "Final - Customer Experience (CX) Feedback – RFP" is not a valid document
7	CX: Cart Abandonment Detection and Recovery	"The system should enable identification of high-intent customers abandoning the booking journey, particularly during:
•        Passenger Details stage
•        Payment stage
•        Differentiation between browse abandonment and high-intent abandonment
•        Support for recovery beyond nudges (e.g., live assistance, escalation routing)
The solution must support triggering contextual engagement prompts or nudges aimed at improving completion rates."	"Is there any additional information, event triggers, or data updates occurring on the website that could help complement dropout identification?
For “Support for recovery beyond nudges,” our understanding is that this would involve generating a ticket and assigning it to the appropriate owner for resolution within a defined SLA. Please confirm if this understanding is correct.
If so, kindly let us know whether you are currently using any ticketing platform that we can integrate with, or if you would be open to leveraging the Qualtrics ticketing feature."	Vendors should leverage behavioral and event-based triggers. Ticketing-based recovery is expected; integration with existing systems (e.g., Salesforce) is preferred. Vendor-native ticketing can be proposed as an alternative.
8	CX + DX: Dashboard	General - Dashboard Approach	"For dashboard design, we are considering a single consolidated dashboard that covers all touchpoints and DX data. This dashboard will be shared with relevant users through role-based access.
Please let us know if there is a need for any additional survey-level dashboards for specific stakeholders."	Initially, a consolidated dashboard will suffice. There should be capabilities to add any additional survey level dashboards later if required
10	CX -  Implementation Methodology 	General - Website design	Could you please confirm whether the IndiGo website is built using a Multi-Page Application (MPA) or a Single Page Application (SPA) within the AEM architecture?	It is built as a Multi-page Application
11	CX Questionnaire	General - Survey readiness	For all touchpoint surveys, we assume that IndiGo has already finalized the survey questionnaire and that no additional advisory support is required. Please let us know if this understanding is correct or if any further support is expected from our side.	The survey questionnaire will be finalized internally based on the exact touchpoint
12	CX and DX document differentiation	General - Document difference	"We observed that there are two RFP requirement documents—“Final - Customer Experience (CX) Feedback – RFP” and “Digital Experience (DX) Feedback – RFP.” While the overall objectives and much of the content appear similar, there are some additional or differing requirements in each document.
Could you please confirm whether this variation is intentional? Additionally, while submitting our response, would it be acceptable to provide a single consolidated proposal covering both CX and DX requirements?
Kindly share any additional context or guidance that can help us align our response more effectively.

Example of differences:

Final - Customer Experience (CX) Feedback – RFP: 
1. This document has missing section ""2.1 Cart Abandonment Detection and Recovery"". 
2. In ""2.1	Journey-Level Feedback Collection"" there is additional touchpoint ""Product Display Page (PDP)"" which is not thee in other document"	Please refer to the document titled "Digital Experience (DX) Feedback – RFP" only; the other is not a valid document
13	CX: 2.6 Integration with Existing Digital Platforms	General - Integration	"We have noted the requirement to integrate with Adobe Experience Manager (AEM), Datadog monitoring environment, and Salesforce customer service platform.
Could you please elaborate on any specific use cases or scenarios you would like us to prioritize or cover for each integration during the initial project implementation?"	Not applicable as the document titled "Final - Customer Experience (CX) Feedback – RFP" is not a valid document
<img width="1797" height="2352" alt="image" src="https://github.com/user-attachments/assets/cd1a1512-a5d2-494d-a210-beecb9be420e" />
