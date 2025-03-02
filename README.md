### File structure
```
/software-engineering-project-team-27
├── backend/                # Backend code (Node.js / Express)
│   ├── controllers/       # Handles business logic (Controllers)
│   ├── models/            # Database models (Schemas)
│   ├── routes/            # API routes definitions
│   ├── server.js          # Server entry point
│
├── frontend/               # Frontend code (Vue.js)
│   ├── dist/              # Built files for production
│   ├── public/            # Static assets (HTML, favicon)
│   ├── src/               # Source code (components, views)
│
├── node_modules/          # Installed dependencies (`npm install` generates this)
├── .gitignore             # Git ignore file (prevents unnecessary files from being tracked)
├── babel.config.js        # Babel configuration (JavaScript compatibility)
├── jsconfig.json          # JavaScript configuration (for TypeScript or VSCode IntelliSense)
├── package-lock.json      # Dependency lock file (ensures same dependency versions across team)
├── package.json           # Project management file (defines dependencies & scripts)
├── README.md              # Project documentation (setup instructions)
├── vue.config.js          # Vue configuration file (e.g., proxy settings, build options)
```