# CIS 4374 Semester Project - Smart Parking Platform

Vision, Scope, and Software Requirements Specification (SRS)

**Project:** Smart Parking Platform  
**Version:** 1.0 (Draft)  
**Date:** 09.08.2026

Contents

[CIS 4374 Semester Project - Smart Parking Platform 1](#_Toc239968872)

[**1\. Project Research and Existing Software:** 2](#_Toc239968873)

[**How Will the Smart Parking Application We Are Building Be Different?** 3](#_Toc239968874)

[**2\. Project Vision and Scope:** 3](#_Toc239968875)

[**3\. Draft of SRS with Use Cases** 4](#_Toc239968876)

# **1\. Project Research and Existing Software:**

During the research phase of this project, I saw that were a number of existing software solutions that try to address issues with parking. Existing software solutions like ParkMobile, SpotHero, Passport Parking, and Easy Park. The following table will go into more detail about these existing solutions.

| **Existing Parking Platform Software Solutions** | | | |
| --- | | | | --- | --- | --- |
| **Solution** | **What The App Does** | **Strengths** | **Weaknesses/Limitations** |
| ParkMobile | \- Parking lookup<br><br>\- Mobile Payments<br><br>\- Parking Availability<br><br>\- Parking Management Tools<br><br>\- Digital Tools | \- Large parking network<br><br>\- Large user base<br><br>\- Supports on-demand and reservations in advance<br><br>\- Parking Availability info and tools to manage pricing | \- Reservation availability depends heavily on the specific parking facility<br><br>\- Availability feature is not available in every location<br><br>\- Paywall for some features |
| SpotHero | \- Parking Lookup<br><br>\- Reservations<br><br>\- Parking Passes<br><br>\- Reservation Modification<br><br>\- Event Parking | \- Strong reservation capabilities<br><br>\- Users can modify reservations before they start | \- Reservations don't guarantee a parking space<br><br>\- In & Out privileges can vary by facility<br><br>\- Availability and features can depend on parking partners |
| Passport Parking | \- Mobile Payments<br><br>\- Parking Maps<br><br>\- Update Notifications<br><br>\- Reporting Dashboards<br><br>\- Parking Operator Tools<br><br>\- Remote Extensions | \- Strong operator capabilities<br><br>\- Combines payments, reporting, enforcement, and customer parking services | \- Primary focus is on mobile payment rather than navigation experience, which is more important to the customers<br><br>\- Depends on integration with other parking platforms |
| Easy Park | \- Parking Payments<br><br>\- Parking Lookup<br><br>\- Navigation Assistance<br><br>\- Predictive/Probability for getting parking space | \- Heavy focus on helping people locate parking<br><br>\- Uses real-time data and probability estimates to direct users to open spots | \- Predictions are probabilities rather than guarantees for the availability of specific parking spots |

Key Points: The existing solutions for this use show that this industry already has some apps that have strong capabilities. However, there is room for improvement for each one, which our application could excel in.

## **How Will the Smart Parking Application We Are Building Be Different?**

After reviewing the existing software solutions for a Smart Parking Platform, it is evident that there is opportunity for differentiation between our application and their applications. The plan for this Smart Parking Platform is going to combine real-time data, parking reservations, navigation, seamless payments, adequate notifications, and more functionality for operator-side functions. Using real-time data for parking spot occupancy can provide more information to customers for more reliable estimates and availability. This application will differentiate itself from these existing solutions by connecting real-time data on availability, reservations, interactive maps, notifications, and more. This platform will directly support this project's high-level requirements for things like availability, reservation capabilities, payments, navigation, notifications, and administrative tools. The experience on this app will be more unified, seamless, intuitive, and useful for the potential userbase.

# **2\. Project Vision and Scope:**

**Introduction:**

WE ARE \$oftware ¢orp is a software development studio that aims to provide seamless solutions to issues customers may have. The company has an unlimited budget and resources that will allow it to get together development teams and the technologies to support their projects. The goal for this project is to develop a project management plan for the creation of a Smart Parking Platform system.

**Acquisition:**

This Smart Parking Platform project was acquired by WE ARE \$oftware ¢orp through a competitive approval proposal that was initiated by a city transportation department who wants to improve parking availability, improve reservation capabilities, reduce traffic, and to increase the utilization of parking facilities. There was (RFP) Request for Proposal for a web and mobile platform that can provide real-time parking availability, reservations, payments, navigation, and management tools. Because of WE ARE \$oftware ¢orp's technical approaches and project management capabilities, we were selected to develop the solution. The project will be developed with an unlimited budget and resources but must be done within the timeline.

**Rough Overview:**

The proposed Smart Parking Platform is being created to address the issue regarding people spending too much time trying to get parking. There is also a need for parking operators to have more efficient ways to manage occupancy, pricing, and utilization. For this project, there is a huge emphasis on real-time availability, interactive maps, reservations, payments, analytics, receipts, notifications, management tools, and more. The goal is to develop a project management plan for the creation of this system, including requirements gathering, stakeholder management, scheduling, budgeting, management, and team coordination. Even though there is an unlimited budget, there are several constraints like a fixed timeline, third party dependencies, compliance with privacy and similar requirements, and city & ordinance laws. The scope of this project will be updated throughout the semester.

# **3\. Draft of SRS with Use Cases**

**Software Requirements Specification (SRS)**

**Project:** Smart Parking Platform  
**Version:** 1.0

**Functional Requirements**

- **FR1:** The system shall allow users to register and log in securely.
- **FR2:** The system shall display real-time parking availability.
- **FR3:** The system shall display parking locations using an interactive map.
- **FR4:** The system shall allow users to search for parking facilities.
- **FR5:** The system shall allow users to view parking facility details and pricing.

**Non-Functional Requirements**

- **NFR1:** The system shall support at least 1,000 concurrent users.
- **NFR2:** The system shall display updated parking availability within 5 seconds of receiving new occupancy data.

**Use Cases**

**Use Case 1  
Title:** Register Account  
**Actor:** Customer  
**Precondition:** User does not have an account  
**Steps:** User enters required information and submits registration.  
**Postcondition:** A user account is created.

**Use Case 2  
Title:** Log In  
**Actor:** Customer  
**Precondition:** User has an account  
**Steps:** User enters valid credentials and selects "Log In."  
**Postcondition:** User is authenticated.

**Use Case 3  
Title:** Find Available Parking  
**Actor:** Customer  
**Precondition:** User has access to the platform  
**Steps:** User enters a destination and views available parking.  
**Postcondition:** Available parking options are displayed.

**  
<br/>Use Case 4  
Title:** View Parking Map  
**Actor:** Customer  
**Precondition:** Parking locations are available  
**Steps:** User opens the map and selects a parking location.  
**Postcondition:** Selected parking facility is displayed.

**Use Case 5  
Title:** View Parking Details  
**Actor:** Customer  
**Precondition:** Parking facility is selected  
**Steps:** User views availability, pricing, and facility information.  
**Postcondition:** Parking information is displayed.

**Use Case 6  
Title:** Reserve Parking Space  
**Actor:** Customer  
**Precondition:** User is logged in and parking is available  
**Steps:** User selects a time and confirms the reservation.  
**Postcondition:** Parking is reserved.

**Use Case 7  
Title:** Make Digital Payment  
**Actor:** Customer  
**Precondition:** User has a reservation  
**Steps:** User selects a payment method and submits payment.  
**Postcondition:** Payment is processed and recorded.

**Use Case 8  
Title:** View Reservation History  
**Actor:** Customer  
**Precondition:** User has reservations  
**Steps:** User opens reservation history and selects a reservation.  
**Postcondition:** Reservation details are displayed.

**Use Case 9  
Title:** Receive Parking Notification  
**Actor:** Customer  
**Precondition:** User has an active reservation  
**Steps:** System detects a relevant event and sends a notification.  
**Postcondition:** User receives the notification.

**Use Case 10  
Title:** Modify Reservation  
**Actor:** Customer  
**Precondition:** User has an eligible reservation  
**Steps:** User changes the reservation details and confirms the change.  
**Postcondition:** Reservation is updated.

**Use Case 11  
Title:** Cancel Reservation  
**Actor:** Customer  
**Precondition:** User has an eligible reservation  
**Steps:** User selects "Cancel" and confirms cancellation.  
**Postcondition:** Reservation is cancelled.

**Use Case 12  
Title:** Get Parking Directions  
**Actor:** Customer  
**Precondition:** Parking facility is selected  
**Steps:** User selects "Get Directions."  
**Postcondition:** Navigation directions are provided.

**Use Case 13  
Title:** Monitor Parking Occupancy  
**Actor:** Parking Operator  
**Precondition:** Operator is logged in  
**Steps:** Operator opens the dashboard and views occupancy information.  
**Postcondition:** Current occupancy is displayed.

**Use Case 14  
Title:** Manage Parking Facility  
**Actor:** Parking Operator  
**Precondition:** Operator has management privileges  
**Steps:** Operator updates parking availability or rates and saves changes.  
**Postcondition:** Facility information is updated.

**Use Case 15  
Title:** Generate Occupancy Report  
**Actor:** Parking Operator  
**Precondition:** Occupancy data is available  
**Steps:** Operator selects a reporting period and generates a report.  
**Postcondition:** An occupancy report is available for review.
