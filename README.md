# 🌿 EcoCampus Hub – Sustainable Campus Platform

**Building a greener campus through technology, awareness, and community participation.**

## 📌 About the Project

EcoCampus Hub is a web-based sustainability platform designed to encourage students, faculty, and campus communities to adopt environmentally friendly practices. It provides a centralized interface to monitor sustainability indicators, report environmental issues, participate in green challenges, organize eco-friendly events, and share innovative ideas for creating a greener campus.

The platform combines an interactive dashboard with gamification features such as Eco-Points, achievement rankings, and sustainability challenges to motivate users to contribute to environmental conservation.

## 🎯 Objectives

- Encourage sustainable habits among students and faculty.
- Promote responsible use of electricity, water, paper, and plastic.
- Make it easier to report campus environmental issues.
- Increase participation in recycling and green initiatives.
- Recognize sustainability efforts through Eco-Points and leaderboards.
- Support collaboration by sharing ideas and organizing environmental events.

## ✨ Key Features

### 1. 🔐 User Login Interface
- Login form with name and institutional ID.
- Role selection for students, faculty/staff, and event organizers.
- Department selection.
- Personalized user information displayed after login.

### 2. 📊 Sustainability Dashboard
- Displays waste diversion, water conservation, energy savings, and campus eco-score.
- Interactive charts using Chart.js.
- Period selection for viewing sustainability trends.
- Visual summaries of resource conservation and waste breakdown.

### 3. 🚨 Environmental Issue Reporting
- Report water leakage, electricity wastage, overflowing bins, plastic accumulation, and e-waste concerns.
- Enter the incident date, campus location, urgency, and description.
- Option to select a photo as evidence and preview it.
- View submitted reports in the reported history section.

### 4. 📋 Reported Issue History
- Displays environmental issues in a structured table.
- Filter reports by issue type and resolution status.
- Tracks statuses such as Pending, In Review, and Resolved.

### 5. ♻️ Waste Separation Guide
- Provides categories for recyclable, organic, electronic, and hazardous waste.
- Shows waste descriptions and disposal recommendations.
- Includes interactive cards and detail modals.

### 6. 💡 Daily Resource-Saving Checklist
- Separate sections for electricity, water, and paper/plastic conservation.
- Awards Eco-Points for checking off sustainable actions.
- Updates the user's points when checklist items are selected or deselected.

### 7. 🏆 Green Challenges
- Plant a Sapling Drive.
- Zero Single-Use Plastic Week.
- Challenge submission forms with participant details and photo-proof fields.
- Awards Eco-Points for submitted challenges.

### 8. 🥇 Campus Eco Leaderboard
- Separate rankings for students and faculty.
- Displays names, institutional IDs, departments, and Eco-Points.
- Highlights top performers with gold, silver, and bronze rankings.
- Includes a celebration animation using Canvas Confetti.

### 9. 📅 Green Event Planner
- Interactive October 2026 calendar.
- Displays scheduled sustainability events.
- Shows event descriptions, organizers, times, and locations.
- Allows users to organize and publish new eco-friendly events.

### 10. 🌱 Idea Hub and Community Ideas
- Submit sustainability problems and proposed solutions.
- Browse ideas shared by the campus community.
- Search ideas by author, problem, or solution.
- Upvote ideas to encourage community participation.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Webpage structure and forms |
| CSS3 | Styling, layouts, animations, and responsive design |
| JavaScript | Application logic and interactive features |
| Bootstrap 5 | Responsive layout and UI components |
| Font Awesome | Icons |
| Chart.js | Interactive dashboard charts |
| Canvas Confetti | Leaderboard celebration effects |
| LocalStorage | Browser-based persistence for selected data |

## 📂 Project Structure

```text
EcoCampus-Hub/
│
├── index.html       # Main application, styles, and JavaScript
├── README.md        # Project documentation
└── .gitignore       # Optional Git ignore rules
```

The current implementation keeps the HTML, CSS, and JavaScript in a single `index.html` file. They can be separated into individual files as the project grows.


## 💾 Data Storage and Current Limitations

- Selected reports, shared ideas, and events are stored using browser LocalStorage.
- Other information, including user session details and leaderboard data, is maintained primarily in JavaScript variables.
- The login screen is a frontend demonstration, not secure authentication.
- The dashboard indicators and initial leaderboard entries contain sample data for demonstration.
- Challenge forms demonstrate submission interactions; they do not upload images to a server.
- Data is not shared between users or synchronized across devices through a backend.
- A production version would require secure authentication, a database, server-side validation, image storage, and role-based permissions.

## 🔮 Future Enhancements

- Integrate a backend and database for persistent campus-wide data.
- Add secure institutional login and user profiles.
- Implement administrator tools to review and resolve environmental reports.
- Enable actual image uploads and evidence verification.
- Add real-time notifications for reports and campus events.
- Introduce monthly sustainability reports and downloadable analytics.
- Add achievement badges and additional eco-friendly challenges.
- Connect the platform to real campus energy and water usage data.

## 🌍 Expected Impact

EcoCampus Hub aims to make sustainability more interactive and measurable by encouraging everyday environmental responsibility, improving awareness of resource conservation, and bringing the campus community together to create a cleaner and greener environment.

## 👩‍💻 Project Information

- **Project Name:** EcoCampus Hub
- **Project Type:** Web Development Project
- **Domain:** Sustainability and Green Campus Technology
- **Status:** Frontend Prototype


**🌱 Small actions. Shared responsibility. A greener campus.**
