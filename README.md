# DentalStaff

## Overview

A friendly website that helps you find dental staff for your clinic when you need them the most. You can find doctors, hygienist, dental assistants, chairside assistants, receptionists and more! Psst... you can also offer your services here!

### Problem Space

- Admin side: Dental offices are highly dependent on a fully staffed team to operate efficiently. When a team member, whether a dentist, dental hygienist, assistant, or receptionist, is unexpectedly unavailable due to illness, holiday, or personal reasons, the office faces a significant challenge. This often leads to appointment cancellations, overworked staff, reduced patient satisfaction, and lost revenue. Current methods of finding temporary or replacement staff are slow, unreliable, and often involve costly staffing agencies or frantic last-minute phone calls.

- Staff side: As a dental professional, your skills are in high demand, but finding flexible opportunities that fit your schedule can be challenging. Whether you're looking to pick up extra shifts, fill gaps in your schedule, or explore different practices, there’s a need for a more efficient way to connect with dental offices in need of temporary or short-term staff.

### User Profile

Dental offices - managers and coordinators. Dental professionals - doctors, hygienists, dental assistants, chairside assistants, receptionists, floaters, etc.

### Features
- As a user I want to be able to create my profile as a dental professional with my name, photo, role, contact information, qualifications, rate and availability, including my ratings
    - As a user I want to be able to browse available jobs based on location and role
    - As a user I want to be able to apply for jobs and offices can accept my application
    - As a user I want to be able to see a calendar showing booked shifts and availability
- As a user I want to be able to create a profile for a dental office with the name of the office, location, our pay range and contact details including our ratings
    - As a user I want to post basic job opportunities with key details like role, date, time and location.
    - As a user I want to be able to accept applications
    - As a user I want to be able to see a calendar showing booked shifts and availability 


## Implementation

### Tech Stack
- React
- Bootstrap
- MySQL
- Express
- Client libraries: 
    - react
    - react-router
    - axios
- Server libraries:
    - knex
    - express

### APIs

No external api's as of now

### Sitemap

- Home Page: a page were you can learn about this website and introduce the service.
- Sign-up/Login Page: a form for users to create an account or login
- Dashboard: users land on their personalized dashboard. This will show upcoming shifts, job opportunities for dental professionals. For dental offices it will display active job postings, recent applicants and notifications

### Mockups

![Figma Mockup!](https://github.com/ara-ventura/ara-ventura-capstone/blob/main/DentaShift.png?raw=true)

### Data

Describe your data and the relationships between the data points. You can show this visually using diagrams, or write it out. 
-Clinics: Name of clinic, photo, name of hiring practitioner, address, phone number, email, number of employees, ratings, active job listings with pay range (with at least three job listings for different dates and positions)
-Dental professionals: Name, photo, specialty, location (not exact), availability, booked dates, reviews and pay rate

### Endpoints

- GET clinics
- GET clinic/:id
- GET clinic/:id/jobs
- POST clinic/jobs
- DELETE clinic/:id 
- DELETE clinic/jobs/:id

- GET staff
- GET staff/:id 
- GET staff/:id/jobs
- POST staff/jobs
- DELETE staff/jobs/:id
- DELETE staff/:id 


## Roadmap

- Day 1: Create two repositories, one for the backend and one for the front end, create wireframes for each page
- Day 2: Create database, set up express with node, create basic data models for users and job postings and develop basic API endpoints
- Day 3: Front end development with react, implement basic layout and navigation (Home page, Sign up/ Login, Dashboard), implement routing
- Day 4: integrate backend with frontend to fetch and display job data
- Day 5: Implement job listings for professionals
- Day 6: Implement job posting for dental offices
- Day 7: Create profile pages for both users
- Day 8-10: Polishing, bug fixes, test test test


## Future Implementations
Your project will be marked based on what you committed to in the above document. Here, you can list any additional features you may complete after the MVP of your application is built, or if you have extra time before the Capstone due date.
- FEATURE: In-app communication: basic messaging: enable direct messaging between dental professionals and offices for job details and confirmations
- FEATURE: Ratings and reviews: allow dental offices to rate professionals after a shift, providing basic feedback
- FEATURE: Notifications / New job Alerts that match their role
- FEATURE: user authentication email based to ensure security and personalized access
- FEATURES: Payment Processing / Advanced Search and Filters / Comprehensive Profile and Verification / Detailed Analytics and Reporting / Expanded Rating and Review System
- ENDPOINTS:
  - PATCH clinic/edit
  - PATCH staff/edit 

