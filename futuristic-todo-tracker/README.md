# 🌿 TaskFlow — Simple & Aesthetic To-Do List & Calendar Tracker

A clean, minimalist, and aesthetic **To-Do List & Calendar Tracker** featuring an elegant dark theme with soft emerald green accents, an interactive calendar for scheduling tasks on specific dates, flexible recurring task management, and customizable reminders with gentle notifications.

---

## ✨ Design & Experience
- **Simple & Aesthetic**: Clean typography (*Plus Jakarta Sans*), rounded corners, subtle dark surfaces (`#0d120f`), and soft emerald green highlights (`#22c55e`).
- **No Clutter**: Stripped of complex sci-fi jargon, loud sirens, and scanlines in favor of a calm, distraction-free productivity workflow.
- **Gentle Acoustic Chimes**: Uses soft harmonic sine chimes via the Web Audio API for task completions and subtle reminders (toggleable anytime).

---

## 🚀 How to Launch
- **Option 1**: Double-click `launch.bat` in this folder.
- **Option 2**: Double-click `index.html` to open in any web browser (Chrome, Edge, Safari, Firefox, Brave).

No installs, node, or servers needed. Everything runs locally and persists in your browser (`localStorage`).

---

## 🎯 Key Features

### 1. 📅 Interactive Calendar Grid
- **Monthly Overview**: View the entire month, navigate between months, or click **Today** to refocus.
- **Date-Specific Tasks**:
  - Click any date to view only tasks due on that day.
  - Click **"+ Add on date"** to create a task pre-filled with the active date.
- **Subtle Day Indicators**: Small green and priority dots under dates indicate scheduled tasks.

### 2. ↻ Repeating / Recurring Tasks
- **Frequency Options**:
  - **Every day** (Daily)
  - **Every weekday** (Monday through Friday)
  - **Specific days of the week** (Choose any combination of Mon–Sun)
  - **Every month** (Monthly)
  - **Custom interval** (e.g., every 3 days)
- **Automatic Rollover**: When you check off a recurring task, it prompts you and advances cleanly to the next scheduled date.

### 3. 🔔 Task Reminders & Notifications
- **Browser Notifications**: Click **"Notifications"** in the header to allow desktop push alerts for upcoming tasks.
- **In-App Reminder Banner**: An aesthetic floating card slides up when a task is due, offering **Complete** and **Snooze 10m** actions.
- **Advance Notice**: Choose to be reminded at the task time, or 5m, 15m, 30m, 1h, or 1d before.

### 4. 📋 Task Organization
- **Filter Tabs**: Quickly view `All`, `Today`, `Upcoming`, `Recurring`, or `Completed` tasks.
- **Instant Search**: Search through task titles, notes, and category tags.
- **Priority Levels**: Critical, High, Medium, and Low.
- **Backup & Restore**: Export your tasks to a JSON file or import existing backups.
