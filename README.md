# My To-Do List

A simple, static To-Do List web app built with HTML, CSS and vanilla JavaScript.

This repository contains a minimal to-do list that supports:
- Adding tasks
- Marking tasks as completed (click a task)
- Removing tasks (click the × button on a task)
- Persistence in the browser via localStorage

Files in this repo
- `index.html` — main HTML file (includes links to `style.css` and `script.js`)
- `style.css` — styles for the app
- `script.js` — JavaScript behavior (add/remove/toggle, localStorage)
- `images/` — folder with icon and checkbox images (ensure this folder is present)

How to run locally
1. Open `index.html` in your browser. For best experience use the Live Server extension in VS Code.
   - In VS Code: right-click `index.html` → _Open with Live Server_
2. Or simply open the file in your browser: double-click `index.html` or drag it into the browser window.

Publish on GitHub Pages
1. Create a new repository on GitHub or push this repo to an existing one.
2. Push your code to the `main` branch and enable GitHub Pages in the repository settings (use the `main` branch root).

Quick git commands (PowerShell)
```powershell
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/LetMeCraft/my-to-do-list-.git
git push -u origin main
```

Notes and next steps
- If images are missing, add them to the `images/` folder (icon.png, checked.png, unchecked.png).
- To persist tasks across devices you'd need a backend — this is intentionally client-only.

License
This project is provided under the MIT License (see `LICENSE`).
