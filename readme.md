# Seva4You - Hack4Bengal

## Project Overview

Seva4You is a comprehensive health and welfare application designed to bridge the gap between patients and healthcare providers. This project, developed as part of the Hack4Bengal hackathon, consists of three interconnected applications:

1. **User App (Seva4You)**: Enables users to schedule appointments with doctors, have one-on-one video interactions, book nearby ambulances with live location tracking, and stay updated with the latest health blogs.

2. **Ambulance Driver App (Seva4YouDriver)**: Allows ambulance drivers to fetch bookings and navigate to booking locations using maps.

3. **Doctors Portal**: Provides doctors with a platform to register, manage appointments, and conduct video consultations.

## Problem Statement

The healthcare system often struggles with accessibility and timely response, especially in emergency situations. Patients face challenges in:

- Scheduling timely appointments with specialized doctors.
- Accessing reliable and real-time information on the availability of ambulance services.
- Obtaining professional medical advice remotely, particularly during emergencies or in remote areas.
- Staying informed about the latest health trends and advice.

## Purpose

The purpose of Seva4You is to provide an integrated solution that addresses these critical issues by offering a user-friendly platform where:

- Patients can easily book appointments and access emergency services, enhancing their overall healthcare experience.
- Ambulance drivers can efficiently manage bookings and navigate to destinations, ensuring quicker response times.
- Doctors can streamline their appointments and offer remote consultations, expanding their reach and improving patient care.
- Users can read and stay updated with the latest health blogs, keeping them informed and proactive about their health.

## Features

### User App (Seva4You)

- Appointment Scheduling: Users can book appointments with doctors of various specializations for one-on-one video interactions at specific time slots.
- Emergency Ambulance Booking: Users can fetch and book nearby ambulances with live location tracking displayed on a map.
- Health Blogs: Users can read and stay updated with the latest health blogs.

### Ambulance Driver App (Seva4YouDriver)

- Booking Management: Ambulance drivers can view and manage incoming bookings.
- Navigation: Drivers can navigate to the booking locations using integrated maps.

### Doctors Portal

- Doctor Registration: Doctors can register and create a profile.
- Appointment Management: Doctors can view upcoming appointments and manage their schedules.
- Video Consultations: Doctors can join video conferences with patients for remote consultations.

## Technology Stack

- Frontend: React Native (for User and Driver Apps)
- Backend: Node.js, Express.js
- Database: MongoDB
- Video Conferencing: ZegoCloud
- Maps and Navigation: Mapbox

## Running the Development Environment

### Prerequisites

- Node.js
- MongoDB
- React Native CLI

### Installation

**Clone the repository**
`git clone https://github.com/Siddhartha-0709/Seva4You-Hack4Bengal`

**Move to Directories and Install Dependencies**

- `cd seva4you/backend`
`npm install`

- `cd ../user-app`
`npm install`

- `cd ../driver-app`
`npm install`

- `cd ../doctor-portal`
`npm install`

**Start the Backend Server**
- `cd seva4you/backend`
`npm start`

**Start the Front-End Application**
- `cd ../user-app`
`npm start`

- `cd ../driver-app`
`npm start`

- `cd ../doctor-portal`
`npm start`

## Running the Production Environment
The backend is deployed on [DigitalOcean](https://lionfish-app-qvjag.ondigitalocean.app/) simply click on the link to visit the sample home route which says Hello World.

The release apk of user app is available on `cd seva4you/UserMobileApp` there you will fine the **Seva4You.apk** file you can simply install it.

The release apk of driver app is available on `cd seva4you/DriverMobileApp` there you will fine the **Seva4YouDriver.apk** file you can simply install it.

The doctor's web app is deployed live on [Vercel](https://seva4-u-doctors-portal.vercel.app/)

## References
1. https://github.com/Siddhartha-0709/Seva4You-Hack4Bengal
2. https://lionfish-app-qvjag.ondigitalocean.app/
3. https://seva4-u-doctors-portal.vercel.app/

#### This project was created using [React Native CLI](https://reactnative.dev/docs/cli) by Team Aloo Posto at [Hack4Bengal](https://www.hack4bengal.tech/)