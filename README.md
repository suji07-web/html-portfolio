# InnoBridge Frontend

A responsive React + Vite frontend prototype for the InnoBridge student innovation platform.

## Included screens
- Overview dashboard and activity statistics
- Explore ideas with text search and topic filters
- Create/publish an idea (stored in React state for this demo session)
- My ideas, saved ideas, appreciation buttons, and idea details
- Find teammates
- Mentor directory
- Interactive demo messaging screen
- Settings preferences

## Requirements
- Node.js 20.19+ or 22.12+ recommended
- npm

## Run locally
1. Extract the ZIP file.
2. Open the extracted `InnoBridge-Frontend` folder in VS Code.
3. Open Terminal → New Terminal.
4. Run:
   ```bash
   npm install
   npm run dev
   ```
5. Open the local URL printed by Vite, usually `http://localhost:5173`.

## Production build
```bash
npm run build
npm run preview
```

## Connect to your backend
This is currently a frontend-only prototype and uses sample data in `src/main.jsx`. The demo interactions work in the browser, but created ideas/messages/settings are not persisted after refreshing, and sign-in/API calls are not yet connected. To connect your team's Express backend, replace the sample-data handlers with `fetch()` calls to your actual API routes and configure the API base URL. Do not assume endpoint names until you inspect the backend routes.
