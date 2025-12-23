# signsverse-client-portal / This project is currently Closed Source. If you are a recruiter or a developer interested in the full source code for review or collaboration, please contact me.
A high-performance, custom-built client portal for WordPress that bridges the gap between Zoho CRM, Zoho Projects, and the end user. This dashboard provides a unified "Single Pane of Glass" view for clients to track their deals, project tasks, and financial status in a modern dark-themed interface.
🚀 Key Features
1. Bi-Directional Zoho Integration
Zoho CRM (Deals): Fetches real-time deal information, including project value, expected closing dates, and current stages.

Zoho Projects (Tasks): Pulls active tasks from multiple projects, displaying them in an organized accordion-style view.

Dynamic Data Filtering: Only displays relevant "Open," "In Progress," or "Completed" tasks to keep the client focused on what matters.

2. Automated Analytics & Reporting.
Stats Grid: Automatically calculates and displays Total Projects, Combined Deal Value, and overall Active Task counts.

Design Preview System: Smart detection of "Design Artfile" & links from Zoho CRM fields to allow one-click design approvals.

Overdue Task Tracking: Intelligent date logic that highlights overdue tasks in red to alert clients/managers.

3. Modern & Responsive UI/UX
Full-Page Dark Mode: A sleek, professional dark interface built with Inter font and FontAwesome icons.

Mobile Optimized: Fully responsive design with a dedicated mobile drawer menu and touch-friendly cards.

Interactive UI: Smooth transitions between sections (Dashboard, Task List, Support) without page reloads using JavaScript.

4. Support & Communication
Integrated Issue Submission: A built-in form that uses WordPress wp_mail with attachment support to send client issues directly to the account manager.

Financial Quick-Links: One-click access to the Zoho Books/Financial portal.

5. Security & Branding
White-Label Experience: Replaces standard WordPress branding with custom logos on the login page and dashboard.

Access Control: Robust redirection logic ensures only logged-in clients can access the sensitive data.

🛠 Technical Stack
Language: PHP (WordPress Hook & Filter API)

APIs: Zoho CRM API v2, Zoho Projects REST API

Authentication: OAuth 2.0 (Refresh Token Flow)

Frontend: HTML5, CSS3 (Custom Grid & Flexbox), Vanilla JavaScript

Database: WordPress Metadata (ACF for storing Zoho IDs)
