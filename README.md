# InterviewX AI — Phase 1 Frontend

A responsive multi-page frontend prototype built with HTML5, CSS3, and vanilla JavaScript.

## Included pages
- `index.html` — landing page
- `register.html` — student registration
- `login.html` — login
- `dashboard.html` — student dashboard and practice activity
- `interview-setup.html` — interview preferences

## Folder structure
```text
InterviewX_AI_Phase1/
├── index.html
├── login.html
├── register.html
├── dashboard.html
├── interview-setup.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── assets/
└── README.md
```

## Run the project
1. Extract the ZIP file.
2. Open the folder in Visual Studio Code.
3. Recommended: install the **Live Server** extension.
4. Right-click `index.html` and choose **Open with Live Server**.
5. Register a demo account, then log in and explore the dashboard and interview setup.

You can also open `index.html` directly in a modern browser, although Live Server is recommended.

## Demo behavior
- Registration stores a demo user in browser `localStorage`.
- Login checks the demo user stored in that browser.
- Dashboard displays session settings saved from the interview setup page.
- Logout clears the current demo login.
- Responsive navigation collapses on smaller screens.

## Important security note
This is a learning/demo frontend only. Passwords are stored in browser `localStorage` for demonstration and are **not secure**. Do not use real passwords or personal information. A production app must use a backend and a proper authentication provider (for example, Supabase Auth), server-side validation, and access controls.

## Phase 2 ideas
- Connect Supabase Auth and PostgreSQL.
- Add a backend API for interview sessions.
- Generate questions with an AI provider from the server.
- Evaluate answers and show feedback.
- Add voice practice and session reports.
