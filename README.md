# Swasth Mumbai

Swasth Mumbai is a comprehensive health and safety web application for Mumbai residents and visitors. It provides real-time health alerts, a dashboard for weather and air quality, a map of hospitals and pharmacies, emergency contacts, and a health toolkit with first aid, disease symptoms, and prevention tips. The app is built with React, Vite, TailwindCSS, and integrates various APIs for a complete experience.

## Features

- **Dashboard:**
  - Real-time weather and air quality updates for your location.
  - Health alerts for outbreaks, high AQI, and more.

- **Health Map:**
  - Interactive map showing major hospitals and pharmacies in Mumbai (static and live from Google Places).
  - Outbreak locations and health-related incidents.
  - Custom markers for hospitals and pharmacies.

- **Emergency Contacts:**
  - One-tap calling for all major Mumbai and national emergency numbers (police, fire, ambulance, disaster, women/child helplines, etc.).

- **Health Toolkit:**
  - First aid instructions with images for common emergencies.
  - Disease symptoms guide and prevention tips.
  - Official health resources.

- **Localization:**
  - Supports English, Hindi, and Marathi.
  - Language selector integrated into the UI.

- **Accessibility:**
  - High-contrast UI, large touch targets, and readable fonts.

## Project Structure

- `public/` — Static files like index.html
- `src/`
  - `api/` — API utilities
  - `components/` — Reusable UI components
  - `contexts/` — React Context providers
  - `hooks/` — Custom React hooks
  - `lib/` — Utility libraries and helpers
  - `pages/` — Main app pages (Dashboard, Map, Toolkit, etc.)
- `supabase/` — Database and authentication configuration
- `index.html` — App root HTML file
- `vite-env.d.ts` — TypeScript Vite environment declarations
- `tailwind.config.ts` — Tailwind CSS configuration
- `tsconfig.json` — TypeScript configuration

## Dependencies

The following major dependencies are required to run this app:

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [Supabase](https://supabase.com/)
- [React Router DOM](https://reactrouter.com/)
- [React-i18next](https://react.i18next.com/) (for localization)
- [Google Maps Platform](https://cloud.google.com/maps-platform/)
- [Axios](https://axios-http.com/)

### Install all dependencies:

```bash
npm install
# or
yarn install

```

### If you need to install specific packages manually:

```bash
npm install react react-dom vite tailwindcss react-router-dom react-i18next axios

```

## Setup Instructions

Clone the repository:

```bash
git clone <repo-url>
cd <project-directory>
```

Install dependencies:

```bash
npm install
# or
yarn install
```

Set up environment variables:

Create a .env file and add the following:

```env
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

Run the app:

```bash
npm run dev
```


## License
This project is intended for educational and non-commercial use.
For questions or contributions, feel free to open an issue or a pull request.

