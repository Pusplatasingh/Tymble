# 🧠 Tymble – The Smart Daily & Weekly Planner

Tymble is a stylish, intuitive, and theme-adaptive to-do planner that supports both **weekly** and **daily** planning modes. It enhances productivity with clean UI, task prioritization, and real-time features like a live clock. 🌱

---

## 🌟 Features

### ✨ General
- Responsive and clean **user interface**
- Live **clock** display with date and time
- **Dark Mode / Light Mode** toggle 🌙☀️
- Beautiful, minimal UI using CSS Grid and Flexbox

### 📆 Planning Modes
- **Weekly View**: View and plan tasks for all days at once
- **Daily View**: Focused view of today’s tasks only
- Easy toggle between modes via dropdown

### ✅ Task Management
- Add task with:
  - Title
  - Time ⏰
  - Priority (Low / Medium / High)
- Mark tasks as **Completed** ✅ or **Pending** ⏳
- **Edit / Delete** individual tasks
- Status-based motivational messages: 🎉 / 🥺

### 🧠 Smart Features
- **Time conflict detection**: Prevents multiple tasks at the same time
- **Persistent data structure**: Internally stores tasks per day

### 🎨 Theming
- Fully supports **Light Mode** (default) and **Dark Mode**
- Dynamically switches logo and theme styles
- Beautiful gradient colors and aesthetic spacing

---

## 🛠️ How It Works

All logic is handled through pure **HTML**, **CSS**, and **Vanilla JavaScript**:

- Uses `data-day` attributes to dynamically track which day each task belongs to.
- Tasks are stored in a JS object `tasksByDay` which maps day → task array.
- Re-rendering ensures updated state is always shown after adding, editing, or completing a task.
- Clock uses `setInterval()` to update every second.
- Theme switching updates DOM classes and the logo dynamically.

---

## 🚀 Getting Started

### 📁 Folder Structure
                                tymble/
                                │
                                ├── index.html # Main HTML file
                                ├── assets/
                                │ └── logos/
                                │ ├── logo-light.png
                                │ └── logo-dark.png
### ▶️ Run Locally

1. Clone or download the repository
2. Open `index.html` in your browser
3. Enjoy planning with Tymble!

---


### 🧭 Weekly View (Light Mode)
> Organize your week in a glance.

### 🌓 Dark Mode
> Comfortable at night with beautiful dark palette.

### ✅ Task Interactions
> Add, complete, edit or delete tasks seamlessly.

---

## 📌 Roadmap / Possible Features

- [ ] LocalStorage / Cloud sync for saving tasks
- [ ] Pomodoro Timer integration 🍅
- [ ] Mobile-first design improvements
- [ ] Add deadline reminders or notifications
- [ ] Drag & Drop task sorting

---

## 🙌 Credits

Built with ❤️ using HTML, CSS, and JavaScript.

---

## 📄 License

MIT License – use freely, modify creatively, and build awesomely!

