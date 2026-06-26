Consider the followings and the files attached and wait for my further instructions
The solution shall provide an enterprise-grade marketing automation platform enabling IndiGo to orchestrate and execute customer engagement campaigns across multiple digital channels. The platform should support customer segmentation, audience management, campaign workflow creation, automated journey orchestration, personalization, scheduling, analytics, and reporting capabilities.The platform shall be capable of managing retention, lifecycle, loyalty, promotional, and transactional communications while ensuring secure handling of customer data. The solution should integrate with IndiGo's existing data sources, CRM platforms, booking systems, customer data repositories, APIs, and file transfer mechanisms for real-time and batch campaign execution.Key capabilities should include:Customer segmentation and audience managementAutomated campaign workflow design and executionMulti-channel campaign orchestration (Email, SMS, Push, WhatsApp, RCS, etc.)Dynamic content personalizationA/B testing and optimizationTrigger-based customer journeysCampaign scheduling and automationDelivery, engagement and conversion analyticsData import/export through APIs and SFTPRole-based access control and audit loggingData retention and consent managementIntegration with external marketing and customer platforms
Brief Description of Services
Adobe Campaign is an enterprise marketing automation platform used for executing customer retention, lifecycle, and engagement campaigns. The platform supports audience segmentation, campaign orchestration, personalized communications, workflow automation, analytics, and integration with IndiGo systems. Customer data is securely exchanged through approved interfaces and used for campaign execution and reporting. Based on current assessment, all retention channels are executed through Adobe Campaigns.
This wording should work well for TPRM, InfoSec review, and the RFP scope.
--- Slide 1 ---
CRM Mission
1
20 November, 2024
Customer Relation Management

Centralized CRM team driving engagement, retention strategies across all IndiGo verticals / functions and touchpoints.
Strategic Support

Running campaigns for multiple verticals, projects, and stakeholders across organization
CDP & Marketing Automation
CDP led automated campaigns and deployment on 6+ communication channels
AMP Emailers

Transforming the traditional emailers into dynamic AMP powered emailers
Innovation

Pioneering up to date retention marketing practices like BIMI, AMP, Annotations &
AI-powered campaigns
BAU

Calendarize and ensure smooth execution of all Promotional & Transactional Campaigns for all CRM Channels
--- Slide 2 ---
AEM, Target
Analytics
Campaign MKT Instance
Campaign RT Instance
Campaign Database
CDP
( First Hive )
Campaign Segmentation
Delivery/Tracking Logs
Reporting
PERSONALIZATION
DIGITAL MESSAGING
Navitaire
Via IndiGo MFT and APIs
Adobe Campaign ( Event Base Real Time Messages )
Itinerary Payload
RT Messages
Adobe Experience Cloud
Campaign Architecture
--- Slide 3 ---
CDP Marketing Integration
3
20 November, 2024
IndiGo MFT
Campaign MKT Instance
Campaign RT Instance- Delivery
Campaign Database
FirstHive

NPS Salesforce
In-Flight Sales (MPOS)
Navitaire
Website
Mobile App
Vernost Hotel
Loyalty
JustPay
Campaign Segmentation
Delivery/Tracking Logs
Reporting
PERSONALIZATION
DIGITAL MESSAGING
API’s
WIP
--- Slide 4 ---
Understanding the Data Flow
IndiGo 
MFT
Adobe Analytics
User
Adobe 
Campaign
Navitaire
Abandon cart
Flight Bookings
CDP
Data Cleaning
Data Mapping
Abandon Cart
Flight Bookings
Attributes
Attributes
Daily Data Flow
1:00 AM: Adobe fetches the daily booking 
and Abandon cart list with user details.

2:00 AM: Adobe drops the file on the MFT.



3:00 AM: CDP processes and enriches
the file with 218+ attributes.

7:00 AM: CDP places the enriched file 
back on the MFT.


8:00 AM onward: Adobe retrieves the enriched 
file and updates customer profiles.

Updated profiles are then used to run 
personalised journeys and campaign logic.
*Only Specific to CDP x Marketing Integration
Personalised Comms
--- Slide 5 ---
Channel Capabilities & Reach
5
20 November, 2024
Journey Mailers ~3-5mn
Email
~18mn
APP PN
~4.5mn
Web Push
~2.7mn
RCS
~4.3mn
SMS
~11mn
WhatsApp
~7.2mn
Adobe
Contactable
~103mn+
Booking Attributes
~221+
CDP
PNR
~241mn+
Trips
~392mn+
--- Slide 6 ---
Campaign Types & Use Cases
6
20 November, 2024
Email Subdomains
Promotional Campaigns

🎯 Sale Campaigns
✈️ Ancillary Services
🌍 New Sectors Launch
🤝 Partner Campaigns
Transactional Comms

📝 Itinerary Emails
🧾 Booking Confirmations
🛒 Abandon Cart – Hotels
🛫 Abandon Cart – Flights
User Journeys

🔄 Re-engagement Campaigns
🛫 90-day Journey
🔁 Cross Sell Journey
⏳ Drip Campaigns
marketing@goindigo.in
exclusive@goindigo.in
customer@goindigo.in
--- Slide 7 ---
Projects & Stakeholders
7
20 November, 2024
Ancillary & Sales
6E Fare Hold
Stretch Upgrade
Addons, Meals & Seats
Other Communications
Executive - CEO Newsletter
Ethics & Compliance
Agent & SMEs
Collab & Partnerships
Spotify
AIFF
No Filter
Hotels & Marketplaces
Hotel Promotional
Hotel Cross Sell
Hotel Drip Campaigns
DPO (legal)
Data governance & alignment
IBC (Loyalty)
Loyalty Promotional
IBC Transactional
K2
--- Slide 8 ---
Marketing Typology Rules
8
20 November, 2024
Frequency capping ensures optimal customer experience while maintaining engagement effectiveness across all channels.
✅ Prevents customer fatigue and unsubscribes
✅ Maintains high engagement rates across channels
✅ Ensures compliance with communication regulations
--- Slide 9 ---
KPI & Performance Snapshot - YTD
9
20 November, 2024
Email Performance
Open Rate: 35%
Avg CTR: 0.9%
Communication Volume
Sent: 1.75B
Monthly Avg: 291M
--- Slide 10 ---
Adobe Campaign Platform
10
20 November, 2024
Marketing Instance

Campaign Design & Creation
Audience Segmentation
Content Management
Workflow Automation
A/B Testing
Real Time Instance

Live Campaign Execution
Real-time Personalization
Trigger-based Communications
Journey Orchestration
Performance Monitoring
Key Platform Capabilities
CRM Integration
Advanced Analytics
Dynamic Personalization
Multi-channel Orchestration
Real-time Processing
Performance Optimization
--- Slide 11 ---
Innovation Initiatives
11
20 November, 2024
Current Implementations - LIVE
BIMI
AMP - Booking
Email Annotations
Itinerary Segmentation
Voucher Code Distribution
Web Push
Pipeline Projects
WhatsApp Carousel
RCS on iOS
Adobe Campaigns V8
--- Slide 12 ---
12
Industry First
Interactive
User Convenience
Seamless
Device Friendly
AMP
--- Slide 13 ---
13
Engagement
Booking
Hello 6E
AMP Booking
45.39%
97% higher than usual
37.10%
61% higher than usual
35.79%
56% higher than usual
Awareness
Gamification
Open Rate
Performance Overview – AMP Mailers
--- Slide 14 ---
14
Step 1: 
Flight search
Step 2: 
Flight details
Step 3: 
Contact & 
Passenger Details
Step 4: 
Flight summary
Current AMP Booking Flow:
--- Slide 15 ---
HTML
15
20 November, 2024
Sale
Destination Launch
Anniversary
AMP
AMP Booking
IndiGoal Quiz Mailer
Collab & Partnerships
Spotify
AIFF
No Filter
Hotels
Hotel Promotional
Hotel Cross Sell
Hotel Drip Campaigns
Marketplace
Sight Seeing
Cabs
Loyalty
Loyalty Promotional
IBC Transactional
K2
HTML
--- Slide 16 ---
2024 Performance Snapshot
16
20 November, 2024
YTD Progress (Jan-Nov 2025)
15.2mn
Active Base
Open Rate: 34.80%
Comms Sent : 432.5 Cr
2024
1.4%
Click Rate
19.77%
Open Rate
3.47bn
Comms
17.5mn
Active Base
2025
2%
Click Rate
35%
Open Rate
4.32bn
Comms
Email : 150 Cr
PN : 248 Cr
RCS : 10.9 Cr
--- Slide 17 ---
Adobe Dashboards for reporting
17
20 November, 2024
--- Slide 18 ---
Monthly Performance
18
20 November, 2024
--- Slide 19 ---
Campaign Calendar
19
20 November, 2024
--- Slide 20 ---
Next 4 Month Plan
20
20 November, 2024
New Transactional Nudges : Web check-in reminder, Low fare reminders, Last-minute upgrades(B+6h)

Discovery : “Book on 6ESkai” Campaign.

Adoption : Exclusive Ancillary Bundles, Stretch Fare, Special Fare Bookings

Habit Creation : Low Cost Fare on 6ESkai, Trip Planner with 6ESkai

Innovation: Multilingual Support ,Voice note & Vernacular support

Hyper-Personalized Experience : recent searches, frequent routes, saved profiles
D2C
6ESkai
Loyalty
To run recurring campaigns on Student Cohort, High Spend High Frequency Cohort, Infant Cohort to increase D2C share

Reduce Abandon Cart Campaign trigger time

Increase AMP Mailer across Promotional and Transactional campaigns (Abandon Cart, E-itinerary, Sale etc.)

App tracking & Redirection in place for App PNs

Solve App Abandonments redirection issues

Increase Stretch adoption and awareness

Restructure monthly retention campaigns to increase Click Rates (Engage – Entertain – Educate)

Launch Personalized Video WhatsApp Cross Sell Campaign, powered by Whilter AI
Drive Co-Branded Card registrations by encouraging high-intent traffic to sign up
Mailer, App PN, Web PN, RCS and WhatsApp campaigns to generate 300mn reach and 300k visits
Promotional & Transactional mailers, report review 
Destination and nudges refresh basis performance
LOBs
Sight Seeing
Cabs
Setup complete Retention channels & nudges
Promotional/Transactional Campaigns, Abandon Cart & Drip Campaign for Cabs Launch
--- Slide 21 ---
Way Forward
21
20 November, 2024
Building Connected Journeys, Smarter Campaigns, and Stronger Loyalty
1. Strengthen Martech Ecosystem
- Ensure seamless integration between Adobe Campaign and all Martech tools (AppsFlyer, Analytics, Upshots, RCS, Web Push, Target).

2. Complete CDP Integration
- Common Identifier to fix duplication and improve customer profile data
Migration to V8, which utilizes Snowflake for seamless CDP integration with Adobe Campaign
Optimize campaign delivery & personalization (frequency, segmentation, consolidation).

3. Drive Innovation & Experimentation
- Identify high value, high engagement Cohorts, ex. High Spend, High Frequency.
- AMP Automation with AMP Itinerary, AMP Abandoned carts, Booking via AMP
- Marketing Automation to be extended with partners 

4. Enhance Tracking & Reporting Intelligence
- Enable real-time campaign tracking
- Publish Weekly retention campaign performance reports to key stakeholders 

5. Strengthen Strategy Alignment & Campaign Governance
- Enforce frequency caps and reduce overlaps to <2 per month.
- Institutionalize structured campaign briefs across teams (Brand, Loyalty, Partnerships, Sales).
--- Slide 22 ---
Thank you
--- Slide 23 ---
YoY Increase At 14% For D2C Revenue
--- Slide 24 ---
ANNEXURE
--- Slide 25 ---
CAC for Oct ‘25 down by 28% Compared to Sep ’25, Increase in D2C Share
Lower CPA on BAU campaigns driven by key optimizations increasing cost efficiency
Source : IndiGo Backend Data
October Data till 25th Oct
--- Slide 26 ---
26
CTR : 2.43%
CTR : 1.95%
CTR : 0.66%​
Hotel Campaign Creatives
--- Slide 27 ---
Abandon Cart
BAU
BAU GOSTAY
Hotel Campaign Creatives
--- Slide 28 ---
YoY Increase At 29% For Visits & 73% For Searches
--- Slide 29 ---
YoY Increase At 14% for D2C Revenue & 4% for Segments
--- Slide 30 ---
Objective – To address the demand for flights to Amsterdam Manchester from India, several campaigns were created on the below platforms 
Google – Search, Display, Pmax, Discovery, YT
Meta/Instagram 
Programmatic Channels
Uber
Samsung CTV
DOOH
Sky Scanner
Spotify

 Results
Budget: INR 3.5 Cr (June’25 – Jan’26)
Impressions: 315 Mn
Reach: 28.7 Mn
Campiagn Engagement: 32.1 Mn
Amsterdam/Manchester (Outbound) Expansion
--- Slide 31 ---
Objective – To Increase awareness & demand for flights from Amsterdam/Manchester to India, platforms activated include:
Google – Search, Display, Pmax, Discovery, YT
Meta/Instagram 
Programmatic Channels
Uber
Tripadvisor
Sky Scanner
Spotify

 Results
Budget: INR 6.6 Cr (June’25 – Jan’26)
Impressions: 113.1 Mn
Reach: 11.51 Mn
Campiagn Engagement : 15.1 Mn
Amsterdam/Manchester (Inbound) Expansion
--- Slide 32 ---
Objective –To address the demand for flights to London /Copenhagen from India, several campaigns were created on the below platforms 
Google – Search, Display, Pmax, Discovery, YT
Meta/Instagram 
Programmatic Channels
Uber
Samsung CTV
DOOH
Sky Scanner
Spotify

Results
Budget: INR 1.78 Cr (Oct’25 – Dec’25)
Impressions: 208 Mn
Reach: 26.5 Mn
Campiagn Engagement : 31.2 Mn
London/Copenhagen (Outbound) Expansion
--- Slide 33 ---
Objective –To Increase awareness & demand for flights from London/Copenhagen to India, platforms activated include
Google – Search, Display, Pmax, Discovery, YT
Meta/Instagram 
Programmatic Channels
Uber
Tripadvisor
Sky Scanner
Spotify

Results
Budget: INR 3.04 Cr (Oct’25 – Dec’25)
Impressions: 24.4 Mn
Reach: 1 Mn
Campiagn Engagement : 2.8 Mn
London/Copenhagen (Inbound) Expansion
--- Slide 34 ---
Objective – Every Monday new select international destinations have 10% off on fares. Campaigns to promote the same have been taken live on the below platforms:

Meta/Instagram 
Google – Search, Display, Pmax, Discovery, YT
Programmatic Channels
Gpay
Sky Scanner

Results
Budget: INR 1.8 Cr (15th Jul’25 – 30th Nov’25)
Impressions: 352 Mn
Reach: 44 Mn
Campaign Engagement: 13.1 Mn
Destinations of the Week (Outbound)
--- Slide 35 ---
Objective – Drive D2C share growth by leveraging special fares (Student, Infant Travel & Family Fare) exclusively available on D2C channels. 
Platforms live for this channel are:

Meta/Instagram 
Google – Search, Display, Pmax, Discovery, YT
Programmatic Channels
Gpay
Zepto
Snapchat
Rapido
Reddit
Paytm
Spotify
Swiggy
INshorts

Results
Budget: INR 2.5 Cr ( Sep’25 – NOv’25)
Cumulative Reach across platforms – 49M​
Avg. monthly Frequency – 5​
Visits – 1.5M | 6. Searches – 2.06M​ (Post campaign live date)
Student Fare – Daily segments avg. – 2.3K (+98%) Pre vs Post
Infant Fare- Daily segments avg – 1.2K (+49%) Pre vs Post
Family Fare – Daily segments avg. – 853 (+48%)​ Pre vs Post
D2C Special Fares (Outbound)
--- Slide 36 ---
Objective – Create awareness and drive consideration for flights to Almaty, Baku, Tashkent and Tbilisi
Platforms live for this channel are:

Meta
Google Search
Criteo

Results
Budget: INR 40 L ( Sep’25 – Nov’25)
Cumulative Reach across platforms – 15 Mn
Avg. monthly Frequency – 2
Visits –  1.4 Mn|  Searches – 21.6K
CIS (Central Asia) Expansion
--- Slide 37 ---
Objective – Drive awareness, consideration and bookings for Stretch on busiest routes 

Meta/Instagram 
Google – Search, Pmax
Kargo
Performace

Results
Budget: INR  Cr ( Jan’25 – Oct’25)
Cumulative Reach across platforms –​
Avg. monthly Frequency – 
Visits –  | Searches –​
STRETCH (Business Class)
--- Slide 38 ---
Objective –To Increase awareness & demand for flights from Singapore to India, platforms activated includes:

Meta/Instagram 
Google – Pmax, YT
CereOne
Criteo
Performace


Results
Budget: INR 40L ( Sep’25 – Nov’25)
Cumulative Reach across platforms – 49M​
Avg. monthly Frequency – 5​
Visits – 10k | 6. Searches – 791
Singapore Tourism Expansion
--- Slide 39 ---
Objective –To Increase awareness & demand for flights from Athens to India, platforms activated includes:


Youtube- Mobile
Mediasmart
Prismatrix
Meta
Skyscanner
Google Demand Gen
Criteo
Bing Search
Google Search Ads
Google P-Max

Results
Budget: INR 5 Cr ( Oct’25 – Mar’26)
Cumulative Reach across platforms – 49M​
Avg. monthly Frequency – 5​
Visits –  |  Searches –
Athens Greece Expansion
--- Slide 40 ---
Objective – Drive hotel awareness and conversion growth by leveraging special discounts and performance-driven platforms such as EKL and Mobilogi.

Platforms live for this channel are:

Meta/Instagram 
Google – Search, Display, YT
Bing
Criteo
Affiliate Partners

Results
Budget: INR 1.3 Cr (Oct’25)
Cumulative Reach across platforms – 25M​
Avg. monthly Frequency – 3
Visits – 1.05M
Searches –​ 37K
Booking – 1,426
Hotels
--- Slide 41 ---
Flights Campaign Creatives
--- Slide 42 ---
Full-funnel activation through curated publisher and partner platforms to build awareness, drive consideration, and convert high-intent audiences for IndiGo routes.
Non-Biddable Architecture
Awareness
Consideration
Conversion
--- Slide 43 ---
Period: Sep’24 – Oct’25 | Total Spends: ₹39 Cr
Campaign, Spend Insights & Impact:

Google: Majority spends on Search (56%), backed by Video and Performance Max — driving high-intent visibility and consistent CTR growth.
Meta: Sales (58%) and Engagement (25%) focus delivered strong conversion efficiency and boosted audience retention.
Publishers: Diverse mix across travel, lifestyle, and premium platforms (Criteo, Skyscanner, Spotify) amplified reach and contextual engagement.


🔹Overall Analysis & Impact:
 The integrated, data-driven media mix enhanced top-of-funnel discovery and bottom-funnel conversions, improving brand visibility, audience quality, and return on ad spend — establishing a more sustained and scalable campaign ecosystem.
Campaign Types And Spend Share (Google + Meta + Publishers)
--- Slide 44 ---
🧩 Campaign Structure — 'Relevance First'
Redesign Indigo’s search campaigns to ensure smoother user journeys and greater ad–keyword–landing page relevancy.
⚙️ Smart Audience Targeting
Leverage DSA + RLSA to dynamically capture incremental intent and re-engage high-value audiences.
🚀 Automation & Coverage
Expand search coverage via automation using smart bidding and keyword automation tools.
📊 Optimization & Efficiency
Implement PMax optimization script to improve budget distribution, conversion efficiency, and ROI.
AUDIT RECOMMENDATIONS MADE TO IMPROVE BIDDABLE PERFORMANCE
Audit done on Bing, Meta and Google and Recommendations Given To Drive Max Efficiency
--- Slide 45 ---
YouTube
Instagram
Facebook
Uber
Snapchat
X (Formerly Twitter)
Google
Affiliates
Mobile  OEM
Criteo
Media Smart
Paytunes
NON-BIDDABLE PLATFORMS SELECTED BASIS FITMENT
Social Media, Travel, Entertainment Key Genres Identified
--- Slide 46 ---
October Performance MTD
Increase observed across all KPIs v/s Sep
Source : IndiGo Backend Data
October Data till 25th Oct
--- Slide 47 ---
Traffic Split by Marketing Channels (Adobe Analytics)
Natural Search dominates with the highest visits and searches, indicating strong organic visibility.
Non-Biddable and Direct channels contribute significantly to total traffic volume.
Meta Search delivers strong performance in both searches and bookings.
Affiliate drives high conversions, ranking among top booking contributors.
Branded Paid Search adds solid volume in searches and bookings, supporting paid visibility.
Overall, top contributors — Natural Search, Meta Search, and Affiliate — account for most of the traffic and bookings.
--- Slide 48 ---
Google Dominates Across Metrics With Highest Traffic and Bookings
--- Slide 49 ---
28M visits                   
   14.6M searches             792K bookings
4.6M visits          
1.37M searches            2.3K Bookings
GOOGLE
META
Meta helps drive visits at lower cost targeting potential customers, while Google helps max out on in-market audience
--- Slide 50 ---
Bing leads in efficiency (7.3% CVR), Affiliate drive conversions, balancing both scale and quality.
BING
AFFILIATE
--- Slide 51 ---
Skyscanner helps drive conversions, while other partners deliver awareness at scale
111.7M visits,
 2.1M searches           21.6K bookings
OTHER PARTNERS
SKYSCANNER
15.7M visits,
 4.37M searches,       278K bookings
--- Slide 52 ---
Source : IndiGo Backend Data
Updated Till Nov ‘25
SON ‘25 saw 27% higher visits, 26% higher searches, & 66% higher bookings compared to SON ‘24
--- Slide 53 ---
Overall Visits and Searches Increased by 29% & 73% Respectively YoY, Bookings up by 15%
--- Slide 54 ---
Period: Sep’24 – Nov25
Search, Meta & Sky Scanner drive conversions, while Spotify, GPay, and DOOH strengthen awareness — supported by Criteo and Performance Max bridging mid-funnel engagement.
Platform Types And Spend Share (Google + Meta + Publishers)
Google 
51%
Meta
19%
Other Media Channels
30%
Others
Skyscanner
Static & Video
--- Slide 55 ---
Campaign Architecture & Structure
