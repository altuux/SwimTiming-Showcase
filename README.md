# SwimTiming-Showcase

A showcase repository of my SaaS product which is consisting of two private repos. SwimTiming and SwimTiming-WebClient.

## Architecture and Tech Stack

The project consists of three main components:
1. **Smart Agent (Backend/Local):** A Python script running locally on the timing system PC. It monitors file changes, parses the data, and pushes it to the cloud.
2. **Cloud (Database):** Firebase Realtime Database for instant data synchronization between the agent and the end-users.
3. **Frontend (Viewer Web & Admin):** Built with Vanilla JavaScript, HTML, and CSS. Deployed on Firebase Hosting. Includes an Admin Dashboard for controlling premium features like sponsor pools and custom color themes.

## How to order:
Currently the project is **IW and im beta testing**, if you want to contact me about something: **aourednik203@gmail.com**

---

## Roadmap and Feature Overview

### Completed (In Production)
* **Smart Agent:** Python application for high-speed Lenex/CSV parsing and timing system monitoring.
* **Cloud Sync:** Real-time Firebase integration with secure PIN authorization.
* **Live Frontend:** Responsive web interface for spectators with automatic updates.
* **Lobby System:** Automated hub for active meets with a 24-hour history (86400s).
* **Theme Engine:** Dark Mode support and remote color management (SaaS ready).
* **Federation Connectivity:** Intelligent meet ID detection with direct links to the ČSPS website.
* **Advanced Settings:** Interactive tag filtering for specific swimmers and clubs.
* **Onboarding Tutorial:** Guided tour for first-time users upon opening a meet.
* **Category & Rank Logic:** Automatic birth year matching and age-group ranking.
* **Timeline Engine:** Manual and automated start time estimates with live delay calculation.
* **Session Management:** Tab-based filtering for multi-day events on mobile and web.
* **TV Mode:** High-visibility auto-scroll interface for public displays (tv.html).
* **Sponsor Integration:** Banner system for displaying partner logos within the app.
* **White-Labeling & Themes:** Full UI customization and VIP themes via Firebase.
* **Scalable Infrastructure:** Firebase Blaze integration for unlimited traffic.
* **Admin Dashboard:** Centralized panel for license management and security.
* **Smart Upload:** Delta-detection in data streams to optimize database write operations.
* **Offline Resilience** Smart client integration function that syncs the update after WiFi disconnect.
* **Share Button** Button at every heat to share, generating special URLs.
* **Feedback Modal** A popup modal that people can vote next updates and give feedback.
* **Splits Analysis:** Extraction of data from touchpads (50m, 100m, 200m) for detailed pace breakdowns.

### In Progress (Current Development)
* **Relay Support:** Full team rosters and club branding for relay events (pending test data).

### Planned (Upcoming Features)
* **Qualification Logic:** Automatic calculation of finalists (A, B) and visual status tags (Q, R1, R2).
* **Meet Records:** Automatic detection and "MR" gold tag assignment for record-breaking times.
* **Progression Analytics:** Improvement leaderboards for clubs and individual swimmers.
* **Speaker Dashboard:** Hidden, high-contrast interface for announcers with real-time race cards.
* **Team Scoring:** Point calculation system based on meet placement.
* **Medal Table:** Live-updated club leaderboard based on podium finishes.
* **Push Notifications:** Early-warning alerts (3 heats before start) for tracked swimmers.
* **Historical Archiving:** Automated migration of completed meets to the "Results History" section.
* **Self-Update System:** Automated client-side updates for the Smart Agent.

---

### DEVELOPED BY: ADAM OUŘEDNÍK // 2026
