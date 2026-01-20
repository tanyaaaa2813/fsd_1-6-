# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
*Experiment Overview*
This project demonstrates a simple Login Page using React.js with routing to a Dashboard.
The experiment focuses on creating a basic front-end login system, handling form inputs, and navigating between pages using React Router.

*Objective*
To understand React component structure (App.jsx, Login.jsx, Dashboard.jsx).
To implement form handling and validation using React useState.
To practice routing and navigation between pages with React Router DOM.
To style components with CSS for an attractive login page design.

*Tools & Technologies Used*
React.js – for building the UI components
React Router DOM – for routing between Login and Dashboard pages
Vite – as the project build tool and development server
VS Code – for code development
CSS – for styling the login page
Node.js & npm – for managing dependencies

*projecct structure*
my-react-login/
│
├─ public/                 # Static files (HTML, images)
├─ src/
│  ├─ components/
│  │  ├─ Login.jsx         # Login component with form and validation
│  │  └─ Dashboard.jsx     # Dashboard component after login
│  ├─ App.jsx              # Main app component with routing
│  ├─ main.jsx             # Entry point rendering App component
│  └─ Login.css            # CSS for login page styling
├─ package.json             # Project metadata and dependencies
├─ package-lock.json        # Auto-generated dependency versions
└─ vite.config.js           # Vite configuration

*Installation & Setup*

Install Node.js (includes npm) from https://nodejs.org/
Clone the repository or download the ZIP.
Navigate to the project folder in terminal:
cd my-react-login
Install dependencies:
npm install
Start the development server:
npm run dev
Open the browser at the URL shown in the terminal http://localhost:5173/

*How the Project Works*
Login Page (Login.jsx):
Users enter email and password.
Form validation checks if inputs are empty.
On successful submission, navigates to Dashboard.
Dashboard Page (Dashboard.jsx):
displays a welcome message.
Optionally shows user info (if user state is passed).
Routing (App.jsx):
"/" → Login page
"/dashboard" → Dashboard page
Styling (Login.css):
Modern login form with gradient background.
Input fields and buttons styled for better UX.

*Key Learnings*
Managing component state with React hooks (useState).
Handling form events and validations.
Navigating between components using React Router DOM.
Creating modular and reusable components.
Styling React components with CSS.





