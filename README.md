# Paradis Island Gym - Web Application

Course Assignment: IMS566 - Web Design and Development[cite: 1]
Author: Muhammad Luthfil Afi Bin Roshafian[cite: 1]
Institution: Universiti Teknologi MARA (UiTM) Puncak Perdana, cawangan Selangor[cite: 1]


## Live Links

* Live Website (GitHub Pages): https://luthfilafi-hash.github.io/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN/
* GitHub Repository: https://github.com/luthfilafi-hash/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN


## Key Project Files

* index.html: Core source file containing application structure, styling definitions, and JavaScript functionality[cite: 1].
* image_1c1de5.png: Reference document detailing assignment criteria and deliverables.


## Project Overview

Paradis Island Gym is a single-page web application (SPA) developed for gym members in Shah Alam, Selangor to manage class schedules, view gym analytics, and browse trainer credentials[cite: 1].

The application uses a dark glassmorphism user interface, providing a central hub for members to reserve weekly practice slots, track workout attendance, and inspect targeted muscle groups using an interactive anatomical diagram[cite: 1].


## Authentication and Access Control

### Testing Credentials
To test the authentication functionality, use the credentials embedded inside index.html[cite: 1]:

* Username: user[cite: 1]
* Password: handsomeL[cite: 1]

### Authentication Process

1. Input Verification: Form inputs are validated against the stored credentials in index.html[cite: 1].
2. Session Persistence: Upon verification, the application writes the login state to sessionStorage as gym_isLoggedIn[cite: 1]. This maintains the session across page reloads[cite: 1].
3. Section Redirection: The interface hides the login form, activates the main landing section, and updates the dashboard user greeting[cite: 1].
4. Navigation Rights: Authenticated users gain full access to the Dashboard, Session Registration, and Trainer Directory[cite: 1].
5. Session Termination: Selecting Logout opens a modal confirmation window[cite: 1]. Confirming clears sessionStorage and redirects back to the login screen[cite: 1].


## Core Features

### 1. Authentication and Session State
* Login system running client-side authentication logic[cite: 1].
* Session state persistence utilizing browser web storage[cite: 1].
* Logout confirmation modal to prevent accidental session exit[cite: 1].

### 2. Member Statistics Dashboard
* Dynamic counters calculating total booked versus completed sessions[cite: 1].
* Interactive SVG anatomical map highlighting muscle groups (Chest, Shoulders, Arms, Back, Core, Legs) with coordinated legend states[cite: 1].
* Weekly calories burned bar chart rendered with ApexCharts[cite: 1].
* Trainer shift availability heatmap[cite: 1].
* Peak gym traffic area chart displaying peak occupancy hours[cite: 1].

### 3. Weekly Class Reservation System
* Schedule organized from Monday to Sunday with specified session times and assigned instructors[cite: 1].
* Instant button state updates transitioning from Book to Booked[cite: 1].
* Booked sessions manager allowing members to mark attendance or remove registered sessions[cite: 1].
* Schedule filtering option to view classes for a specific trainer selected from their profile page[cite: 1].

### 4. Trainer Directory and Profiles
* Directory featuring 5 coaches: Chris Bumstead, Joel Twinem TNF, David Laid, Elijah Mundy, and Jacob Oestreicher[cite: 1].
* Individual profile pages detailing background, area of specialization, certifications, philosophy, and contact details[cite: 1].


## Technologies and Libraries Used

* HTML5: Page layout and structural markup in index.html[cite: 1].
* CSS3: Custom properties, CSS Grid, Flexbox layouts, and backdrop filter styling[cite: 1].
* Vanilla JavaScript (ES6+): Single-page navigation logic, DOM manipulation, state persistence, and event handling[cite: 1].
* ApexCharts.js: External charting library imported via CDN in index.html for rendering dashboard charts[cite: 1].
* Google Fonts: Integration of the Poppins font family[cite: 1].


## Quick Testing Guide

1. Open the live website link in your web browser.
2. Enter the demo credentials on the login page:
   * Username: user[cite: 1]
   * Password: handsomeL[cite: 1]
3. Click LOG IN to access the system[cite: 1].
4. Use the navigation bar to test dashboard widgets, book classes, and filter trainer schedules[cite: 1].


(c) 2026 Paradis Island Gym. Educational assignment created for the IMS566 course by Muhammad Luthfil Afi Bin Roshafian.[cite: 1]
