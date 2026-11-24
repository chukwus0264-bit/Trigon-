
## 1. Target Users


**Primary Users**
- Undergraduate and postgraduate students residing in the halls of residence
- Students moving between academic buildings, library, cafeteria, sports facilities, and the teaching hospital
- Staff members who require short-distance movement within the campus


**Secondary Users**
- Tricycle operators working within the university community
- Relevant university units responsible for campus transportation and safety (for future oversight)






## 2. Current Coping Mechanisms


Students and staff currently manage the difficulty of accessing tricycles through the following informal methods:


1. Waiting at popular pickup points, often for extended periods during peak hours
2. Walking long distances between locations when no tricycle is available
3. Contacting known drivers via phone calls or messaging applications
4. Relying on information from friends or course mates about the location of free tricycles
5. Using motorcycles (okada) as an alternative when tricycles cannot be found
6. Adjusting personal schedules to avoid periods of high demand


These methods are inefficient, unpredictable, and frequently result in lateness, physical fatigue, and loss of productive time.






## 3. Limitations of Existing Approaches


- No dedicated digital system currently exists within Babcock University for real-time visibility of available tricycles or for requesting rides.
- General commercial ride-hailing platforms are not designed for short intra-campus trips and are rarely practical within the gated university environment.
- Informal communication channels (phone calls and messaging) are unreliable and do not scale effectively.
- Physical waiting at junctions contributes to congestion and does not assist individuals located far from common pickup points.






## 4. Minimum Viable Product (MVP) Objectives


The first version of the system will focus on solving the core difficulty of locating and requesting available tricycles within the campus.


### Core Features of the MVP
1. User registration and authentication for students (using student email or phone number)
2. Driver registration with basic verification
3. Ability for drivers to indicate availability status (Available / Busy)
4. Real-time display of approximate locations of available tricycles
5. Ability for students to request a ride by specifying pickup and destination points
6. Driver acceptance or rejection of ride requests
7. Basic status updates for the assigned ride (accepted, en route, arrived)
8. Display of standard campus fare information
9. Simple ride history for both students and drivers


### Features Deferred to Later Versions
- In-app payment processing
- Rating and review system
- Ride sharing among multiple passengers
- Administrative dashboard for university oversight
- Push notifications
- Estimated time of arrival calculations






## 5. User Stories (MVP)


- As a student, I want to view nearby available tricycles so that I can decide whether to wait or make alternative arrangements.
- As a student, I want to request a tricycle to my current location so that I do not have to search or walk long distances.
- As a driver, I want to receive and respond to ride requests so that I can serve passengers more efficiently.
- As a driver, I want to update my availability status so that only free tricycles are shown to students.






# 6. Success Metrics


The following indicators will be used to evaluate the effectiveness of the MVP:


- Number of completed ride requests per day
- Average waiting time after a ride request is made (target: under 10 minutes)
- Percentage of users who report reduced walking or waiting time
- Number of active drivers using the system daily
- Rate of repeat usage by students






## 7. Research Approach and Findings


**Research Methods**
- Structured and semi-structured interviews with students across different halls of residence
- Direct observation at major pickup points during peak and off-peak periods
- Short survey distributed among students


**Key Observations**
*(Replace this section with actual data collected by the team)*


- Peak demand periods typically occur between 7:30–9:00 a.m., 12:00–2:00 p.m., and 4:30–6:30 p.m.
- Students in halls located farther from academic areas experience greater difficulty in accessing tricycles.
- Many students expressed willingness to use a digital system if it is simple and reliable.


Note: Primary research involving at least 15–20 interviews or a survey of 40 or more respondents should be completed and the findings inserted here before final submission.






## 8. Scope Definition


**Included in MVP**
- Real-time availability of tricycles
- Ride request and acceptance workflow
- Basic location sharing
- Student and driver account management


**Excluded from MVP**
- Payment integration
- Complex route optimisation
- Full administrative analytics
- Native mobile applications (initial version will be a responsive web application)
- Integration with the university identity management system






## 9. High-Level Technical Considerations


- Development will begin with a mobile-responsive web application
- Backend services required for user management, real-time location updates, ride matching, and status communication
- Location services will rely primarily on GPS, with manual pin selection as a fallback
- Authentication will use email or phone number with secure verification
- Real-time communication will be handled through appropriate web technologies


Detailed technical architecture will be defined after approval of this document.






## 10. Risks and Open Questions


- Level of adoption by tricycle operators
- Accuracy of GPS signals in certain parts of the campus
- Existing university regulations governing commercial transport within the campus
- Privacy and safety considerations related to location sharing
- Reliability of campus internet connectivity


These issues will be examined during the pilot phase.






## 11. Recommended Next Steps


1. Complete primary research (interviews and survey)
2. Refine the MVP feature list based on research findings
3. Develop basic user flow diagrams and wireframes
4. Select an appropriate technology stack for the backend
5. Build and conduct a limited pilot with selected drivers and students


12. Functional Requirements

Functional requirements describe what the system must do.

1. User Registration: The system shall allow students and drivers to create accounts.
2. Authentication: The system shall allow registered users to log in and log out securely.
3. Driver Management: Drivers shall be able to register and update their availability (Available or Busy).
4. Location Tracking: The system shall display the approximate locations of available tricycles.
5. Ride Requests: Students shall be able to request rides by selecting pickup and destination points.
6. Ride Management: Drivers shall be able to accept or reject ride requests.
7. Ride Status: Students shall be able to view ride updates, including Accepted, En Route, and Arrived.
8. Fare Information: The system shall display standard campus transportation fares.
9. Ride History: Students and drivers shall be able to view their previous rides.

13. Non-Functional Requirements

Non-functional requirements describe how well the system should perform.

1. Performance: The system should load quickly and process ride requests with minimal delay.
2. Security: User accounts and personal information shall be protected against unauthorized access.
3. Reliability: The system should function consistently and handle temporary network interruptions.
4. Usability: The system should have a simple, user-friendly interface that requires minimal training.
5. Compatibility: The system should work on mobile phones, tablets, and computers using modern web browsers.
6. Scalability: The system should support an increasing number of students and drivers.
7. Maintainability: The system should be easy to update, debug, and improve.
8. Privacy: Users' personal and location information shall only be accessible when necessary and to authorized users.
9. Availability: The system should remain accessible during normal campus transportation hours.
10. Data Integrity: The system shall maintain accurate ride records and prevent conflicting ride assignments.
