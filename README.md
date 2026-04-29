# GPD Task Manager
### Global Publications Department — Technical & Innovations Unit

> A real-time task management and reporting platform built for the GPD Tech Unit at Rhapsody of Realities. Manage tasks, track team progress, generate reports, and coordinate across platforms — all in one place.

---

## 🚀 Getting Started

### Accessing the App
1. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari)
2. Or visit the hosted Netlify link shared by your admin
3. Sign in with your name and password

### Default Accounts
Contact **Omoyele Shonubi** (Admin) for your login credentials.

> To create a new account, click **"Create account"** on the login screen and enter your name, role, password, and the admin code (provided by Omoyele).

---

## 👥 Roles & Permissions

| Role | What you can do |
|------|----------------|
| **Admin** (Omoyele) | Full access — add/edit/delete tasks, manage team members, view all reports, access settings |
| **Developer** (Mayowa, John) | View full dashboard, create and edit tasks, move tasks, add comments and attachments |

---

## 📋 Features

### Dashboard
- Live overview of all tasks — total, completed, in progress, overdue
- Filter tasks by status (All / To-do / In Progress / Done)
- Goals & KPI snapshot
- Team workload bars
- Daily standup submission form

### Tasks & Board
- **List view** — full table of all tasks with filters by member, platform, priority and status
- **Board view** — Kanban-style columns (To-do / In Progress / Done)
- **Drag and drop** tasks between columns
- Click any task to open and edit details
- Add **comments** and **file/link attachments** to tasks

### Planning
- **Calendar** — monthly and weekly view of task due dates and events. Click any day to add a calendar event (meetings, deadlines, personal events)
- **Roadmap** — tasks grouped by platform showing completion progress

### Goals & KPIs
- Set weekly, monthly or quarterly goals with targets
- Link goals to a KRA — progress auto-calculates from completed tasks
- Live KPI dashboard with team completion rates
- Target vs Actual comparison bars

### Team Tracker
- Progress bars per team member
- Platform completion tracking
- See which tasks each member is currently working on

### Alerts & Notifications
- Overdue task alerts
- Due-today highlights
- Notification feed (reminders, task updates, digest)
- Set custom reminders with date and time
- Generate daily digest summary
- Toggle notification preferences

### AI Reports
- **Daily Report** — generates full KRA + operational table in GPD format
- **Weekly KRA Scorecard** — calculated scores, grade and citation
- **Monthly Summary** — full executive narrative
- **Priority Analysis** — AI-recommended priorities and daily schedule
- AI chat panel (bottom-right 🤖 button) — ask anything about your tasks

### Settings
- Change your password
- Add or remove team members (Admin only)
- Configure unit profile
- Add custom task fields and platforms
- Integrations: Slack, Email, Google Calendar, WhatsApp, Webhook
- Export tasks as CSV or JSON
- Import tasks from CSV

---

## 📱 Using the App

### Adding a task
1. Click **"+ New task"** from any page
2. Fill in title, platform, KRA, assignee, priority, due date
3. Click **Save task**

### Moving a task
- **Drag and drop** on the Board view, or
- Click the task → change the Status field, or
- Use the **← Todo / In Progress / ✓ Done** buttons on each card

### Submitting a standup
1. Go to **Dashboard**
2. Scroll to the standup form at the bottom right
3. Fill in what you completed, what you're working on today, and any blockers
4. Click **Submit standup**

### Generating an AI report
1. Go to **AI Reports** in the sidebar
2. Select the report type (Daily / Scorecard / Monthly / Priority)
3. Choose the date and team member
4. Click **✨ Generate**
5. Use **📋 Copy** to copy the output

### Adding a calendar event
1. Go to **Calendar**
2. Click **+ Event** or click directly on any day
3. Fill in the event details and save

---

## 🔥 Firebase & Data

All data is stored in **Firebase Firestore** and syncs in real-time across all team members.

- **Project:** `gpd-task-manager`
- **Sync status:** shown in the top-left of the sidebar (🟢 Live when connected)
- Changes made by one team member appear instantly for everyone else

---

## 🌙 Dark Mode

Click the **🌙** button in Settings → Account to toggle dark mode. Your preference is saved automatically.

---

## 🤖 AI Assistant

The AI is powered by **Google Gemini** (free tier — 1,500 requests/day).

- Click the **🤖 button** (bottom-right of any page) to open the chat panel
- Use quick buttons for common requests or type anything
- The AI reads your live task data and generates specific, formatted responses

---

## 📤 Sharing & Hosting

The app is a single HTML file hosted on **Netlify**.

- **URL:** *(shared by admin)*
- To update the app, upload a new `index.html` to Netlify
- All team members use the same link — data is shared via Firebase

---

## 🛠️ Troubleshooting

| Problem | Fix |
|---------|-----|
| Can't log in | Check your name is spelled exactly as registered. Contact admin to reset password |
| Tasks not loading | Check internet connection. Wait a few seconds for Firebase to connect (watch 🟢 Live status) |
| AI not working | Gemini API has a daily limit. Try again after a few minutes |
| Dark mode not saving | Enable cookies/localStorage in your browser settings |
| Can't drag tasks | Use Chrome or Edge for best drag-and-drop support |

---

## 📞 Support

Contact **Omoyele Shonubi** (Administrative Lead) for:
- Account creation or password resets
- Admin code for new accounts
- Any technical issues

---

*GPD Technical & Innovations Unit · Rhapsody of Realities · Global Publications Department*
