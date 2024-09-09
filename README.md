# DentalStaff

## Overview

A friendly website that helps you find dental staff for your clinic when you need them the most. You can find doctors, hygienist, dental assistants, chairside assistants, receptionists and more! Psst... you can also offer your services here!

### Problem Space

Admin side: Dental offices are highly dependent on a fully staffed team to operate efficiently. When a team member, whether a dentist, dental hygienist, assistant, or receptionist, is unexpectedly unavailable due to illness, holiday, or personal reasons, the office faces a significant challenge. This often leads to appointment cancellations, overworked staff, reduced patient satisfaction, and lost revenue. Current methods of finding temporary or replacement staff are slow, unreliable, and often involve costly staffing agencies or frantic last-minute phone calls.

Staff side: As a dental professional, your skills are in high demand, but finding flexible opportunities that fit your schedule can be challenging. Whether you're looking to pick up extra shifts, fill gaps in your schedule, or explore different practices, there’s a need for a more efficient way to connect with dental offices in need of temporary or short-term staff.

### User Profile

Dental offices - managers and coordinators. Dental professionals - doctors, hygienists, dental assistants, chairside assistants, receptionists, floaters, etc.

### Features

1- Profile creation for dental professionals like name, photo, role, contact information, qualifications and availability and for dental offices with the name of the office, location and contact details. (they will appear with ratings as well)
2- Job posting and search: Job listings: dental offices can post basic job opportunities with key details like role, date, time and location. Simple search functionality: allow professionals to browse available jobs based on location and role
3- Booking and scheduling: Shift booking: professionals can apply for jobs and offices can accept applications. Basic scheduling calendar: simple calendar showing booked shifts and availability

----


## Implementation

### Tech Stack

HTML, SCSS, BOOTSTRAP, React, MYSQL, React Router, Express.js, Github and Git

### APIs

List any external sources of data that will be used in your app.

### Sitemap

List the pages of your app with brief descriptions. You can show this visually, or write it out.

---
Home Page: a page were you can learn about this website and introduction the service.
Sign-up/Login Page: a form for users to create an account or login
Dashboard: users land on their personalized dashboard. This will show upcoming shifts, job opportunities for dental professionals. For dental offices it will display active job postings, recent applicants and notifications

### Mockups

Provide visuals of your app's screens. You can use pictures of hand-drawn sketches, or wireframing tools like Figma.

### Data

Describe your data and the relationships between the data points. You can show this visually using diagrams, or write it out. 

### Endpoints

List endpoints that your server will implement, including HTTP methods, parameters, and example responses.
------
Home
create-profile/staff
create-profile/clinic
staff/edit
clinic/edit
staff/delete
clinic/delete
get/clinics
get/clinic/:id
get/staff
get/staff/:id 

## Roadmap

Scope your project as a sprint. Break down the tasks that will need to be completed and map out timeframes for implementation working back from the capstone due date. 

---

## Future Implementations
Your project will be marked based on what you committed to in the above document. Here, you can list any additional features you may complete after the MVP of your application is built, or if you have extra time before the Capstone due date.
FEATURE: In-app communication: basic messaging: enable direct messaging between dental professionals and offices for job details and confirmations
FEATURE: Ratings and reviews: allow dental offices to rate professionals after a shift, providing basic feedback
FEATURE: Notifications / New job Alerts that match their role
FEATURE: user authentication email based to ensure security and personalized access
MVP FEATURES: Payment Processing / Advanced Search and Filters / Comprehensive Profile and Verification / Detailed Analytics and Reporting / Expanded Rating and Review System

