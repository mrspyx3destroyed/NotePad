# 📝 Notepad — Modern Web Notepad

A clean, responsive, browser-based **Notepad application** built with **HTML, CSS, and Vanilla JavaScript**.

The project combines a minimal dark application interface with a paper-style writing editor. Notes can be created, edited, searched, color-tagged, and deleted, with automatic saving handled through the app's storage API.

---

## ✨ Features

- 📝 Create unlimited notes
- ✏️ Edit note titles and content
- 💾 Automatic saving while typing
- 🔎 Search notes by title or content
- 🎨 Choose a color for each note
- 🗑️ Delete notes with confirmation
- 📊 Live word and character counter
- ⏱️ Relative last-edited timestamps
- 📱 Responsive mobile layout
- 📂 Sidebar note management
- ⌨️ `Ctrl + N` / `Cmd + N` shortcut for a new note
- 🌙 Modern dark UI with a paper-style editor
- 🎨 Custom typography using Google Fonts
- ⚡ Built with plain HTML, CSS, and JavaScript — no framework required

---

## 🖥️ Preview

The interface contains:

- A **sidebar** for searching and managing notes
- A **paper-style editor** for writing
- **Color indicators** for individual notes
- An **autosave indicator**
- A responsive **mobile sidebar**
- Live **word and character counts**

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, responsive design, animations |
| JavaScript | Note management and application logic |
| Web Storage API | Note persistence through the provided storage interface |
| Google Fonts | Typography |

### Fonts

The project uses:

- Fraunces
- Source Serif 4
- Inter
- IBM Plex Mono

---

## 📁 Project Structure

```text
notepad/
│
├── notepad.html
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the project

Open:

```text
notepad.html
```

in your browser or use a local development server.

### 3. Start writing

Create a note using the **+** button, write your content, and the application will automatically save changes through its configured storage interface.

---

## 🧩 Main Functionality

### Create Notes

Click the **+ New Note** button to create a fresh note.

The application also supports:

```text
Ctrl + N
```

on Windows/Linux, or:

```text
Cmd + N
```

on macOS.

### Search

Use the search box in the sidebar to filter notes by:

- Note title
- Note content

### Auto Save

Changes are automatically saved shortly after typing. The interface displays a small **saving/saved** indicator.

### Note Colors

Each note can have its own color. Available colors include blue, purple, pink, orange, teal, green, and red.

### Delete Notes

The delete button requires a second confirmation click before removing the active note.

---

## 📱 Responsive Design

The application adapts to smaller screens.

On mobile devices:

- The sidebar becomes a slide-out menu
- A menu button appears in the top bar
- The editor adjusts its spacing and typography
- The note-taking experience remains usable on smaller displays

---

## 🎨 Design

The UI is designed around a combination of:

- Dark desktop workspace
- Paper-inspired editor
- Glass-like/dark sidebar elements
- Gradient accent colors
- Rounded UI components
- Subtle animations
- Minimal typography
- Responsive layout

---

## ⚙️ Storage

The application uses the following storage key:

```javascript
notepad-notes-v1
```

Notes are stored as JSON data containing properties such as:

```javascript
{
  id,
  title,
  body,
  updatedAt,
  color
}
```

The current implementation calls:

```javascript
window.storage.get(...)
window.storage.set(...)
```

Therefore, the project expects an environment that provides this `window.storage` interface. If you want the project to run as a completely standalone browser application, the storage layer can be replaced with the browser's native `localStorage` API.

---

## 🔐 Privacy

This project is designed as a client-side notepad interface.

No backend server or database is included in the current project.

> **Important:** The exact persistence behavior depends on the storage interface available in the environment where the application is running.

---

## 🔮 Future Improvements

Possible upgrades include:

- 📌 Pin important notes
- 🏷️ Tags and categories
- 🌗 Light/Dark theme switcher
- 📤 Export notes as `.txt`, `.md`, or `.json`
- 📥 Import notes
- ☁️ Cloud synchronization
- 🔒 Password-protected notes
- ↩️ Undo/Redo history
- 📝 Markdown editor
- 📅 Calendar-based note organization
- 🔗 Shareable notes
- 🗃️ Folders and notebooks
- 📱 Installable PWA support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/new-feature
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add new feature"
```

5. Push the branch

```bash
git push origin feature/new-feature
```

6. Open a Pull Request

---

## 📄 License

This project is available for personal and educational use.

If you plan to publish or distribute the project, add your preferred open-source license to the repository.

---

## 👨‍💻 Author

**Developed by**

# MUHAMMAD BILAL | MR SPY X3 DESTROYED

Built with ❤️ using **HTML5, CSS3 & Vanilla JavaScript**.

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Made with HTML • CSS • JavaScript**
