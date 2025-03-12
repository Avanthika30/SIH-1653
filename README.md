# Smart India Hackathon Workshop
# Date:12.03.2025
## Register Number:212224040039
## Name:AVANTHIKA B
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The increasing amount of electronic waste (e-waste) is a growing concern, leading to environmental pollution and health hazards due to improper disposal. To tackle this, we propose a web-based platform that helps users locate the nearest e-waste collection and recycling facility.

The website will feature:

Real-time location tracking to identify the nearest e-waste facilities.

Educational pop-ups to inform users about hazardous components in e-waste.

A credit point system that rewards users based on the amount of precious metals recovered from disposed devices.

## Proposed Solution / Architecture Diagram
The proposed solution consists of a web-based platform integrated with AI-powered location tracking and educational features. The core components include:

Frontend (User Interface): React.js for an interactive web experience.

Backend (Server & API): Node.js for processing user requests and handling database interactions.

Database Management: PostgreSQL for storing user data, facility locations, and reward points.

Mapping & Geolocation: Google Maps API for facility locating and navigation.

Authentication & Security: Firebase Authenticator for user access control.

Reward System: A database-driven system to track and award credits based on disposal activity.

AI & Image Recognition: To categorize e-waste and suggest appropriate disposal methods.

Architecture Diagram (Conceptual Overview):

User Interaction → Frontend UI (React.js)

User Data & Requests → Backend API (Node.js)

Facility Locator & Maps → Google Maps API

Authentication → Firebase

Database Storage & Management → PostgreSQL

Reward System & Analytics → Backend Processing

## Use Cases
1.User Searches for E-Waste Facility

Inputs location or enables GPS

Receives a list of nearby facilities with distance and directions

2.User Uploads E-Waste Image

AI categorizes the waste type

Suggests nearest suitable facility

3.User Learns About E-Waste Impact

Educational pop-ups inform about hazards

Suggestions for safe disposal methods

4.User Earns Reward Points

Registers device for disposal

Earns points based on recovered materials

Redeems points for eco-friendly incentives

5.E-Waste Facility Monitors Impact

Facility views real-time collection statistics

Reports generated on recycling rates and environmental benefits.

## Technology Stack
Frontend: React.js

Backend: Node.js

Database: PostgreSQL

Mapping Service: Google Maps API

Authentication: Firebase Authenticator

Development Tools: Git, Postman/Insomnia

## Dependencies

Mapping service integration-10 days

Data collection & facility database setup-10 days

AI model for image recognition-15 days

User interface development-20 days

Reward points system implementation-15 days

Testing & Deployment-15 days
