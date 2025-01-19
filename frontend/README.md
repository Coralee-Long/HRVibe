# HRVibe Frontend

## 1. Overview

The frontend for HRVibe is a React + TypeScript application designed to provide
a clean and interactive user interface for visualizing health and activity data.
It communicates with the backend API to fetch data and displays key metrics such
as HRV, sleep, and activity trends.

## 2. Structure

The project follows a modular structure for scalability and maintainability:

- `src/components`: Reusable UI components (e.g., charts, cards, forms).
- `src/pages`: Page-level components for specific views (e.g., Dashboard,
  Insights).
- `src/styles`: Global styles and theme settings.
- `src/utils`: Utility functions for data formatting and API integration.

## 3. Tech Stack

- **Frameworks and Libraries:** React, TypeScript
- **Build Tool:** Vite
- **Styling:** CSS (or a preferred styling library, if applicable)
- **Code Quality:** ESLint, Prettier

## 4. Setup

```bash
  npm install
  npm run dev
```

### **Available Commands**

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the app for production.
- `npm run preview`: Serves the production build locally.
- `npm run lint`: Runs ESLint for code quality checks.

## 5. Development Notes

- **Styling Conventions:** Use consistent class naming and CSS practices for
  scalability.
- **Code Quality:** Run `npm run lint` before committing changes to ensure
  consistency.
- **Future Additions:** Expand on folder structure and component descriptions as
  features are added.
