# Heading 1⏰ MikiClock Dashboard

MikiClock is a comprehensive employee time management system designed to help organizations track employee working hours, manage attendance, and improve productivity.
It provides employees with simple Clock In/Clock Out functionality while also offering admins tools for oversight and reporting.

✨ Features

User Home Page

Personalized welcome message with real-time clock & date.

Quick access to main sections (Dashboard, Admin Panel, Time History, Forum, Settings).

Clock Management

One-click Clock In/Clock Out buttons.

Displays current status, today’s working hours, and clock-in time.

Quick Actions

Dashboard: view recent activity and clock status.

Time History: track detailed records of attendance.

Forum: connect and communicate with colleagues.

Settings: customize profile and preferences.

Stats & Reports

Daily and weekly hours summary.

Average daily working hours.

Monthly records and total activity logs.

Recent Updates

System updates, new features, and enhancements shown on the homepage.

Responsive Sidebar Navigation

Sidebar for desktop view.

Collapsible mobile menu with toggle.

Accessibility & Alerts

SweetAlert for interactive notifications.

Responsive UI built with TailwindCSS.

# Heading 1🛠️ Tech Stack

Frontend: HTML5, TailwindCSS, Font Awesome

Scripts & Utilities: Vanilla JavaScript, SweetAlert2

Storage: Browser LocalStorage (for clock records)

# Heading 1🚀 Getting Started
Prerequisites

A modern web browser (Chrome, Firefox, Edge).

Basic web server (optional, e.g., VS Code Live Server).

Installation

Clone the repository:

git clone https://github.com/yourusername/mikiclock-dashboard.git


Navigate to the project folder:

cd mikiclock-dashboard


Open home.html in your browser.

📂 Project Structure
mikiclock-dashboard/
├── home.html          # Main landing page
├── dashboard.html     # User dashboard
├── admin.html         # Admin panel
├── timehistory.html   # Time history tracking
├── forum.html         # Forum for communication
├── settings.html      # User settings page
├── form.html          # Login / Logout form
└── assets/            # Icons, CSS, JS, images

# Heading 1🔑 Key Pages

Home: Welcome banner, quick clock actions, quick stats, and announcements.

Dashboard: In-depth view of attendance records.

Admin Panel: Manage employees and their clock data.

Time History: Review past attendance logs.

Forum: Internal communication and discussions.

Settings: Profile customization.

# Heading 1⚠️ Limitations

Local Storage Only – Records are stored in the browser’s LocalStorage:

Data is not shared across devices or browsers.

Clearing browser storage removes all records.

No Backend Integration – No database or server-side authentication:

Users are not persisted across sessions.

No real-time multi-user syncing.

Basic Authentication – Login is client-side only (not secure for production).

Single Admin Panel – Only one admin account; no role-based access.

Limited Reporting – Only daily/weekly stats; no export to CSV or advanced analytics.

Responsiveness – Optimized for modern browsers, may break on very small screens (< 360px).

No Notifications – Lacks email/SMS reminders; relies only on in-app alerts.

📸 Screenshots (Optional)

Add screenshots of your dashboard UI here to showcase the interface.

# Heading 1🤝 Contributing

# Heading 2Contributions are welcome! Please fork the repo and submit a pull request.






