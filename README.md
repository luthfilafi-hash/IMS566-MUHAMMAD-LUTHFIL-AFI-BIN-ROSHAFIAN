# 🏋️ Paradis Island Gym — Web Application

> **Course Assignment:** IMS566 — Web Design and Development[cite: 1]  
> **Author:** Muhammad Luthfil Afi Bin Roshafian[cite: 1]  
> **Institution:** Universiti Teknologi MARA (UiTM) Shah Alam, Selangor[cite: 1]  

---

## 🔗 Live Links

* **Live Website (GitHub Pages):** [https://luthfilafi-hash.github.io/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN/](https://luthfilafi-hash.github.io/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN/)
* **GitHub Repository:** [https://github.com/luthfilafi-hash/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN](https://github.com/luthfilafi-hash/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN)

---

## 📁 Key Project Files

* **`index.html`**: The core source file containing the complete application markup, styles, and JavaScript application logic[cite: 1].
* **`image_1c1de5.png`**: Project submission requirement and deliverables reference image.

---

## 📌 Project Overview & Description

**Paradis Island Gym** is a dynamic, modern single-page web application (SPA) designed for gym members in Shah Alam, Selangor to manage their workout schedules, track fitness statistics, and explore trainer profiles[cite: 1]. 

Built with a sleek dark aesthetic and glassmorphic UI, the application provides a central portal for athletes looking to book weekly practice sessions, view muscle focus maps, and monitor their attendance in real time[cite: 1].

---

## 🔐 Login System & Authentication Details

### Demo Credentials
To evaluate and test the application's client-side authentication, use the hardcoded credentials built into `index.html`[cite: 1]:

* **Username:** `user`[cite: 1]
* **Password:** `handsomeL`[cite: 1]

### How the Login System Works

1. **Client-Side Validation:** The form input values on the login page are captured and verified against predefined credentials inside `index.html`[cite: 1].
2. **Session Persistence:** Upon successful verification, the script writes `gym_isLoggedIn = true` into the browser's `sessionStorage`[cite: 1]. This ensures the user stays logged in while navigating the single-page app or refreshing[cite: 1].
3. **Automated Redirection & Personalized Greeting:** The app hides the `#login-section` and automatically displays the primary landing view (`#about-section`) while dynamically updating the dashboard greeting to welcome the user[cite: 1].
4. **Access Control:** All main navigation links (Dashboard, Register Session, Trainers) and the session logout modal are unlocked once logged in[cite: 1].
5. **Secure Logout:** Triggering the **Logout** button opens a confirmation modal[cite: 1]. Confirming clears `sessionStorage` and safely returns the user back to the login screen[cite: 1].

---

## 🔥 Key Features Included

### 1. 🔑 Client-Side Authentication & Session Management
* Secure login interface using built-in credentials (`user` / `handsomeL`)[cite: 1].
* Persistent login state maintained across page reloads using browser storage[cite: 1].
* Interactive logout modal with action confirmation[cite: 1].

### 2. 📊 Interactive Fitness Dashboard
* **Dynamic Counter:** Real-time calculation of total **Booked** vs. **Attended** workout sessions[cite: 1].
* **Interactive Muscle Map:** Custom SVG body diagram highlighting targeted muscle groups (Chest, Shoulders, Arms, Back, Core, Legs) with color-coded hover state sync[cite: 1].
* **Calories Burned Bar Chart:** Weekly energy expenditure graph powered by ApexCharts[cite: 1].
* **Availability Heatmap:** Displays trainer shift coverage across the week[cite: 1].
* **Peak Traffic Area Chart:** Visualizes gym capacity curves throughout operating hours[cite: 1].

### 3. 📅 Weekly Practice Booking System
* **Weekly Schedule:** Organized Monday through Sunday featuring distinct class titles, times, and trainers[cite: 1].
* **Interactive Booking Buttons:** Real-time state updates toggling from "Book" to "Booked"[cite: 1].
* **Booked Sessions Modal:** 
  * View active reservations grouped by day[cite: 1].
  * Mark sessions as **Attended (✓)** to update stats[cite: 1].
  * Cancel/Remove sessions **(🗑️)** from your list[cite: 1].
* **Trainer Schedule Filtering:** Filter classes on the registration page to view sessions for a specific trainer selected from their bio page[cite: 1].

### 4. 🎴 Elite Trainers Directory & Profiles
* **Trainer Profiles:** Features 5 coaches (Chris Bumstead, Joel Twinem TNF, David Laid, Elijah Mundy, Jacob Oestreicher)[cite: 1].
* **Comprehensive Bio Pages:** Full modal profiles detailing background stories, specializations, certifications, philosophy, and direct contact details[cite: 1].

---

## 🛠️ Frameworks & Libraries Used

* **HTML5:** Structuring the single-page layout within `index.html`[cite: 1].
* **CSS3:** Built using standard CSS variables, CSS Grid, Flexbox, and glassmorphic backdrop filters[cite: 1].
* **Vanilla JavaScript (ES6+):** Handling SPA view transitions, event handlers, DOM manipulation, and state storage[cite: 1].
* **[ApexCharts.js](https://cdn.jsdelivr.net/npm/apexcharts):** Third-party charting library loaded via CDN in `index.html` to render performance analytics[cite: 1].
* **Google Fonts (`Poppins`):** Applied for modern typography styling[cite: 1].

---

## 🧪 Quick Test Guide

1. Open your browser and navigate to the **[Live Website Link](https://luthfilafi-hash.github.io/IMS566-MUHAMMAD-LUTHFIL-AFI-BIN-ROSHAFIAN/)**.
2. On the login screen, enter:
   * **Username:** `user`[cite: 1]
   * **Password:** `handsomeL`[cite: 1]
3. Click **LOG IN**[cite: 1].
4. Navigate through the top navigation bar to explore the **Home**, **Dashboard**, **Register Session**, and **Trainers** sections[cite: 1].

---

*© 2026 Paradis Island Gym. Educational project created for the IMS566 assignment by Muhammad Luthfil Afi Bin Roshafian.*[cite: 1]
