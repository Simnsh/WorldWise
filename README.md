# WorldWise

**WorldWise** is a React application built with Vite that helps you track cities and countries you’ve visited. 
The app includes a sidebar navigation, interactive map placeholder, and pages for product info, pricing, login, and tracking your adventures.

## Features
- Fetches city data from a JSON server running locally, as configured through a `BASE_URL` pointing to `http://localhost:9000`.
- Manage lists of visited cities and the derived list of countries.
- Add new entries via a form (city name, country, visit date, notes).
- React Router-based navigation (homepage, product, pricing, login, app layout).

## Tech Stack
- React 18
- React Router DOM
- Vite
- JSON Server
- ESLint for linting

## Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Start the development servers
- **Start the JSON Server:**
```bash
npm run server
```
- **In another terminal, start the Vite dev server:**
```bash
npm run dev
```

> The React app expects the API at `http://localhost:9000` by default.

### 3. Build for production
```bash
npm run build
```

### 4. Preview production build
```bash
npm run preview
```

## Available Scripts
- `npm run dev` – Start Vite development server.
- `npm run build` – Build the app for production.
- `npm run lint` – Run ESLint.
- `npm run preview` – Preview the production build.
- `npm run server` – Run JSON Server on port 9000.

## Project Structure
```
src/                # React source code
  components/       # UI components like CityList, Map, Sidebar, etc.
  pages/            # Pages such as Homepage, Product, Pricing, Login, and AppLayout

data/cities.json    # Initial dataset for the JSON Server API
public/             # Static assets (images used by pages)
```

---

**License:** MIT  
**Author:** Your Name
