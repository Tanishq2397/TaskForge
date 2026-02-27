# TaskForge — Personal Productivity Web App

Responsive task manager built with **HTML, CSS, and JavaScript**.

## Features

### Core
- **Add / complete / delete tasks**
- **Task categories**: Personal, Work, Study, Fitness
- **Task priority**: High / Medium / Low (color-coded pill)
- **Deadlines** stored in **LocalStorage** so tasks persist after refresh
- **Flexible due dates**: choose **date & time** or **date-only**

### Task list & UX
- **Filter** by All / Pending / Completed
- **Search** by task title or category
- **Progress bar** with % of tasks completed
- **Drag & drop reordering** (in All view with no search/filter)
- Clean, responsive layout (desktop + mobile)

### Focus & motivation
- **Pomodoro timer**
  - Focus / break modes
  - User-set focus & break duration (minutes)
  - Sound + optional browser notification when a session ends
- **Motivation quotes**
  - Instant quotes from a local list
  - Author shown on the next line

### Calendar
- Monthly calendar view showing all tasks **with a due date**
- Days with tasks are highlighted and list task titles (with "+N more" if many)

## How to run

You can simply open `index.html` in your browser by double-clicking it.

For a smoother experience, run a small local server (recommended):

```powershell
cd "c:\Users\tanis\OneDrive\Desktop\Task management"
python -m http.server 5173
```

Then open `http://localhost:5173` in your browser.
