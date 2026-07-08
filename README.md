# Paradis Island Gym - Web Application

Course Assignment: IMS566 - Web Design and Development
Author: Muhammad Luthfil Afi Bin Roshafian
Institution: Universiti Teknologi MARA (UiTM) Puncak Perdana, cawangan Selangor


## Live Links

* Live Website (GitHub Pages): https://luthfilafi-hash.github.io/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN/
* GitHub Repository: https://github.com/luthfilafi-hash/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN


## Key Project Files

* index.html: Core source file containing application structure, styling definitions, and JavaScript functionality.
* image_1c1de5.png: Reference document detailing assignment criteria and deliverables.


## Project Overview

Paradis Island Gym is a single-page web application (SPA) developed for gym members in Shah Alam, Selangor to manage class schedules, view gym analytics, and browse trainer credentials.

The application uses a dark glassmorphism user interface, providing a central hub for members to reserve weekly practice slots, track workout attendance, and inspect targeted muscle groups using an interactive anatomical diagram.


## Authentication and Access Control

### Testing Credentials
To test the authentication functionality, use the credentials embedded inside index.html:

* Username: user
* Password: handsomeL

### Authentication Process

1. Input Verification: Form inputs are validated against the stored credentials in index.html.
2. Session Persistence: Upon verification, the application writes the login state to sessionStorage as gym_isLoggedIn. This maintains the session across page reloads.
3. Section Redirection: The interface hides the login form, activates the main landing section, and updates the dashboard user greeting.
4. Navigation Rights: Authenticated users gain full access to the Dashboard, Session Registration, and Trainer Directory.
5. Session Termination: Selecting Logout opens a modal confirmation window. Confirming clears sessionStorage and redirects back to the login screen.


## Core Features

### 1. Authentication and Session State
* Login system running client-side authentication logic.
* Session state persistence utilizing browser web storage.
* Logout confirmation modal to prevent accidental session exit.

### 2. Member Statistics Dashboard
* Dynamic counters calculating total booked versus completed sessions.
* Interactive SVG anatomical map highlighting muscle groups (Chest, Shoulders, Arms, Back, Core, Legs) with coordinated legend states.
* Weekly calories burned bar chart rendered with ApexCharts.
* Trainer shift availability heatmap.
* Peak gym traffic area chart displaying peak occupancy hours.

### 3. Weekly Class Reservation System
* Schedule organized from Monday to Sunday with specified session times and assigned instructors.
* Instant button state updates transitioning from Book to Booked.
* Booked sessions manager allowing members to mark attendance or remove registered sessions.
* Schedule filtering option to view classes for a specific trainer selected from their profile page.

### 4. Trainer Directory and Profiles
* Directory featuring 5 coaches: Chris Bumstead, Joel Twinem TNF, David Laid, Elijah Mundy, and Jacob Oestreicher.
* Individual profile pages detailing background, area of specialization, certifications, philosophy, and contact details.


## Technologies and Libraries Used

* HTML5: Page layout and structural markup in index.html.
* CSS3: Custom properties, CSS Grid, Flexbox layouts, and backdrop filter styling.
* Vanilla JavaScript (ES6+): Single-page navigation logic, DOM manipulation, state persistence, and event handling.
* ApexCharts.js: External charting library imported via CDN in index.html for rendering dashboard charts.
* Google Fonts: Integration of the Poppins font family.


## Quick Testing Guide

1. Open the live website link in your web browser.
2. Enter the demo credentials on the login page:
   * Username: user
   * Password: handsomeL
3. Click LOG IN to access the system.
4. Use the navigation bar to test dashboard widgets, book classes, and filter trainer schedules.


(c) 2026 Paradis Island Gym. Educational assignment created for the IMS566 course by Muhammad Luthfil Afi Bin Roshafian.
