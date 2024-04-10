Blood Bank

Team Members :
Hari Krishnan Raj Kumar, Lakshmi KS, Nidhi Kumar, Shristi Shrivastava

Version 1.0

Summary of Project:

4.5 million Americans would die each year without life saving blood transfusions. Approximately 32,000 pints of blood are used each day in the United States. Every three seconds someone needs blood, with the casualties spiking up due to lack of blood pints, it's high time a tech enabled community based product helps to solve this alarming issue. A community based blood bank application involving all people and Hospitals in a community to tackle emergency situations
Project Analysis

Value Proposition:

Number of U.S. blood donors hits all-time low for past 20 years - Red Cross.
The value proposition lies in addressing the decline in blood donations by facilitating quick and efficient communication between donors and hospitals. This not only benefits the general public by saving lives but also enhances hospitals ability to serve their patients effectively.
Primary Purpose:

The primary focus is to benefit the public, hospitals registered with the Blood bank can raise push notifications when blood donors are required, this will notify all donors in the nearby area. These emergency situations can be handled.
●	First it helps the common people, saving lives when at crucial situations.
●	Secondly Hospitals are also benefited as it helps them to serve better.
Target Audience:
Primary Target Audience - General Public: People from all age groups and across the board with a commitment of being blood donors daily or during emergencies.This includes:

●	Residents who know the importance of having volunteer blood donors and are trusted with the precious life of another person.
●	People that actively view themselves as health-conscious who like to help, and who want to leave a better world than the one they started with.
●	Students, professionals and retirees at youth and middle age who are characterized with the necessary level of high readiness to increase their regular blood donating rate.

Secondary Target Audience:

Hospitals and Healthcare Facilities:
Public Hospitals: Medical facilities that provide health services to every member of the community government regardless of his financial position. They can thus at ease access a pool of merely possible blood donors in an emergency through the portal.
Private Hospitals: Along with not only the healthcare system which serves patients of diverse levels of insurance. They can enjoy the app's valuable features like the subscription to the premium services such as index priority access to blood donors and an advanced notification system with ease and comfort.
Tertiary Target Audience:

Community Organizations and NGOs:
Blood Donation Drives: They can use the app for  purposes to launch their campaigns, seek donations, and organize pick up appointments for the kind-hearted contributors.
Success Criteria
1. User Adoption and Engagement:
- Registration Rate: Through achieving the registration ratio of 80% among the population eligible for the blood donation, the general contribution to the blood system would be high enough.
- Active User Engagement: The effort to increase the user retention rate of the application shows the users active engagement with the application in not less than 60% of the total registered user monthly.
2. Blood Donation Impact:
- Donation Volume: The application is envisioned as a tool for seeing that 40% of the blood donations facilitated through the application, compared to the baseline, meet the blood supply demands as desired.
- Emergency Response Time: The application’s utility is evident in prompting responses to emergency blood donation requests with a response time of less than 30 minutes.
3. Hospital Adoption and Satisfaction:
- Hospital Registration Rate: Ensuring at least 70% of the hospitals who are eligible bind partnerships allows wide outreach, encouragement and usage of the app for their blood donation management and coordination.
- Satisfaction Surveys: Collect feedback and suggestions and evaluate satisfaction
4. Community Impact and Recognition:
- Lives Saved: Recording and safeguarding the quantitative and qualitative data of the life-saving effect of having the blood donations on schedule due to the application will give undeniable evidence of the lives saved or positively impacted.
- Community Recognition: Achieving positive media coverage, testimonials and procurement of recognition awards from healthcare institutions and community leaders is sufficient proof of the application's significance in solving the blood donation problems and saving lives.

Competitor Analysis:
Partnering the alliance with the donation action groups who are actively engaged in the realm of blood donation like with red cross is the most imminent project on our list of plans. These centers have spent decades in building reputations held on impeccable ness and professionalism in blood storage and supply others are very envious of. They also have various national mobilization campaigns and mobile blood drive services, this is because they set up blood donor centers in locations where they are needed most and wherever a diverse geographical region of the country. We could collaborate with them to provide a better experience for all of us to serve the common good. 

Monetization Model:

Subscriptions: It's free for all public hospitals, but the private hospitals need to pay an annual fee.
Financial Donations: Have financial donation options in the app for people to donate based on their will.
 Sponsorship and Partnerships: Corporate Sponsorships: Partner with corporate sponsorship, which might include pharmaceutical companies, health care businesses, and technology firms to host blood donation drives, events, and marketing campaigns. By way of compensation, sponsors can have brands displayed within the application, sponsored print ads and website content, and possibilities for CSR initiatives.

Initial Design:

The purpose of this section is to define the “Minimum Viable Product” (MVP).  It may also be useful to call out the scope and expected/known limitations for your product here.
Users : people
Signups / login
Update info
Receive notifications/ emails regarding blood groups required
See nearby hospitals
See blood drives
Financial donations - Allow user to donate
See stats and facts
User : hospitals
Signups / login
See all donors
Request for blood group,(sends notifications to all nearby donors)
Financial donations
 
 

UI/UX Design


Technical Architecture
(What are the necessary components to support an MVP?  Data structures?  Storage considerations?  Web/cloud interactions?  Be sure to put in some thoughts as to how to measure your success here.  Call out dependencies on 3rd party services/APIs here, too)
 
System Components:

Mobile App: Consumer-side, web and mobile forms of accessibility for this application. Interface for the registration, login, blood donation requests as well as notifications and others, in short all the user interactions is provided.
Backend Server: The critical element which is responsible for the orderly execution and completion of all user requests, storing the data as well as the connection between frontend interface, database, and any external services.  - Will use the app's codebase for the same.
Database: Create a data management system to store user’s information, hospital details, blood donation requests and any other related data in an organized format. These systems implement a relational database like MySQL.
Authentication Service: Ensures that there are authentication processes using stronger mechanisms for user authorization, such as multi-factor authentication (MFA). A better user experience should be provided via the linking with Firebase Authentication with analogous services and this will handle user sign-up, login, and session management.
Geolocation Service: Create location based capabilities such as getting addresses of hospitals, blood donation centers and more. Keep track of blood donation drives also. Integration of mapping APIs such as Google Maps or Mapbox as well as providing search functionality will offer accurate geolocation functions.
Data Flow:
User Registration and Authentication: Users who access the application from the frontend of the interface must first provide authentication, as the communication process between the frontend interface and the backend server takes place.
Blood Donation Requests: Hospital staff search for blood donations through the server back-end, which checks for availability of nearby registered donors and pushes out notifications to those donors via email  and push notification.
Database Operations: After receiving the data from general users, the hospital staff, and other people in charge (donation request), the backend server communicates with the database to store and retrieve user profiles, hospital information, donation requests, and other critical data.

Challenges and Open Questions

Technical challenges: Ensuring scalability and performance of the application,especially during critical times. Optimized solutions might involve optimizing database queries and utilizing caching mechanisms.
Data privacy and security: Addressing challenges and concerns regarding the storage and handling of sensitive user data and hospital data. Solutions may include implementing encryption and adhering to regulatory standards such as HIPAA.
User adoption: Inspiring wide-scale acceptance for the app from both the donors and the hospitals. Tactics can include, but not limited to customized marketing programs and conjunction with health organizations.
Legal considerations: Ensure the adherence to traditions and regulations of health services both in blood donation and in other healthcare areas. It will perhaps entail collaboration with legal experts in the quest of satisfactorily resolving the topic of intellectual property rights and insurance coverage.



 

