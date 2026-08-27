# StudyFlow — Week 2 Front-End Application

## Project Overview
StudyFlow is a student task and study planner. Week 2 focuses on developing the front-end application based on the architecture and wireframes prepared in Week 1.

## Week 2 Objectives
- Build a functional front-end using React.
- Create at least three interconnected views/pages.
- Implement reusable UI components.
- Add navigation and user interactions.
- Make the interface responsive.
- Follow basic accessibility and front-end best practices.
- Document the development process and local setup.

## Pages / Views
1. **Landing Page** — Introduces StudyFlow and provides access to login/get started.
2. **Dashboard** — Shows task statistics, today's tasks, status and task-management options.
3. **Task Details** — Shows complete information about a selected task and provides actions.

## Technologies
- React
- JavaScript
- HTML
- CSS
- Bootstrap
- React Router

## Component Structure
```text
src/
├── components/
│   ├── Navbar
│   ├── TaskCard
│   ├── Button
│   └── Sidebar
├── pages/
│   ├── Landing
│   ├── Login
│   ├── Dashboard
│   └── TaskDetails
├── services/
│   └── api
├── App
└── main
```

## Development Process
1. Set up the React project.
2. Created the basic application layout.
3. Converted the Week 1 wireframes into front-end screens.
4. Created reusable components.
5. Added page navigation using React Router.
6. Added task interactions.
7. Added responsive layouts for desktop and mobile.
8. Added basic accessibility practices.
9. Tested navigation and user interactions.
10. Prepared documentation.

## Design Approach
The interface uses a simple dashboard-based design so students can understand their tasks quickly. Reusable components prevent repeated UI code, while page-level components represent individual views.

## Navigation Flow
```text
Landing
   ↓
Login / Get Started
   ↓
Dashboard
   ↓
Task Details
   ↓
Back to Dashboard
```

## Interactivity
- Navigation between pages
- Task selection
- Task completion
- Add-task interaction
- Edit/delete task actions
- Responsive navigation
- Form input and validation

## Responsive Design
The interface is designed for desktop, tablet and mobile screens.

## Accessibility
- Labels for form fields
- Descriptive button text
- Keyboard-friendly controls
- Readable text and spacing
- Meaningful headings
- Alternative text for relevant images

## Local Setup
Install Node.js and npm, then run:

```bash
npm install
npm run dev
```

Open the local URL shown by the terminal, normally:
`http://localhost:5173`

## Testing Checklist
- Landing page loads.
- Navigation links work.
- Dashboard opens.
- Task details open from a task.
- Task completion interaction works.
- Add/edit/delete interactions respond.
- Layout works on different screen sizes.
- No sensitive credentials are stored in source code.

## Future Integration
The Week 2 front end can later be connected to the Node.js/Express REST API and MySQL database planned in Week 1.

## Author
Student: ____________________

## Version
Week 2 — Front-End Application Development
