# 📚 Study Desk Workspace

Study Desk is a fully self-contained, browser-based productivity dashboard designed for students and self-learners. It centralizes your study materials, time management, and focus music into one unified, customizable interface without requiring a backend or database.

## ✨ Features

* **📖 Multi-Tab Document Reader:** Open multiple PDFs or websites side-by-side. 
  * **LMS Support:** Uses vanilla iframes to securely load authenticated portals like Allen LMS without dropping cookies.
  * **Smart YouTube Embedding:** Automatically parses standard YouTube or Shorts links into embedded, distraction-free video players.
  * **Local File Support:** Renders local PDFs securely using in-memory object URLs.
* **⏱️ Pomodoro Focus Timer:** Built-in timer with presets for Focus, Short Break, and Long Break modes. Track your progress against a customizable Daily Target.
* **🔥 Streak Tracking:** Persists your daily study streaks using browser `localStorage` to keep you motivated.
* **📅 School Timetable:** A dedicated modal grid to map out your weekly schedule from Monday to Sunday.
* **🎵 Spotify Sidebar:** Persistent sidebar layout to keep your study playlists accessible. Includes a "Hide Music" toggle that dynamically expands the main workspace.
* **🎨 Dynamic Theme System:** 
  * **☀️ Light Mode:** Clean, crisp focus.
  * **🌙 Dark Mode:** Easy on the eyes for night study.
  * **✨ Magic Realm:** A deep violet aesthetic featuring an animated, floating particle background on a custom HTML5 canvas.

## 🚀 Getting Started

Since Study Desk is built with completely vanilla frontend technologies, there is no complex build step or server required.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/study-desk.git](https://github.com/yourusername/study-desk.git)
