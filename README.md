# 📝 To-Do List App

A simple and elegant to-do list application built with pure HTML, CSS, and JavaScript. Stay organized and get things done.

## ✨ Features

- **Add Tasks** — Quickly add new tasks to your list
- **Complete Tasks** — Check off tasks when done
- **Delete Tasks** — Remove tasks you no longer need
- **Filter Tasks** — View All / Active / Completed tasks
- **Persistent Storage** — Tasks are saved in browser localStorage (no backend needed)
- **Responsive Design** — Works on desktop and mobile devices

## 🛠️ Tech Stack

- **HTML5** — Markup structure
- **CSS3** — Styling with gradient background and clean UI
- **JavaScript (Vanilla)** — Task management logic with localStorage

## 🚀 Getting Started

### Option 1: Open directly
1. Download or clone this repository
2. Double-click `index.html` to open in your browser

### Option 2: Live Server (recommended)
```bash
# If you have VS Code with Live Server extension
# Right-click index.html → Open with Live Server
```

Or use any local HTTP server:
```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .
```

Then open `http://localhost:8000` in your browser.

## 📁 Project Structure

```
todo-list/
├── index.html      # Main HTML structure
├── style.css       # Styling and layout
├── app.js          # Task management logic
└── README.md       # This file
```

## 📖 How to Use

1. Type a task in the input field and press **Enter** or click **Add**
2. Click the **checkbox** to mark a task as completed
3. Click the **×** button to delete a task
4. Use the **filter buttons** (All / Active / Completed) to sort tasks
5. Your tasks are automatically saved — close and reopen anytime!

## 📸 Screenshot

```
┌─────────────────────────────────┐
│         📝 To-Do List           │
│    Stay organized and get...    │
├─────────────────────────────────┤
│  [ Add a new task...  ] [ Add ] │
├─────────────────────────────────┤
│  All  Active  Completed   2 left│
├─────────────────────────────────┤
│  ☐  Buy groceries            ×  │
│  ☑  Finish homework (striked)×  │
│  ☐  Call mom                 ×  │
└─────────────────────────────────┘
```

## 🔧 Customization

You can customize the app by editing:
- `style.css` — Change colors, fonts, and layout
- `app.js` — Modify task logic or add new features

### Change Theme Color
In `style.css`, find the `body` background gradient:
```css
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## 📄 License

MIT License — feel free to use and modify.

## 👤 Author

Created as a simple web project.
