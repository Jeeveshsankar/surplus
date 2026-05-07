# Surplus: From Waste to Wonder

Surplus is an AI-driven, real-time food redistribution platform engineered to eliminate food waste and fight hunger. By bridging the gap between food donors, distribution centers, and logistics providers, Surplus ensures that perfectly good food is redirected to those in need before it spoils.

## The Mission

Globally, 1.3 billion tons of food are wasted annually while 800 million people face hunger. Traditional redistribution systems fail due to information asymmetry and logistical friction, particularly with cooked meals that have a tight "3-hour window." 

Surplus solves the "Spoilage Gap" by applying intelligence at the edge—matching supply to demand instantaneously.

## Core Ecosystem

The platform is divided into three seamlessly integrated experiences designed for frontline operators:

- **Donor Dashboard:** Designed for food providers (restaurants, grocers). Features one-click "Kitchen Drops" and automates compliance and tax receipt generation.
- **Receiver Application:** Built for shelters and food banks. Provides smart inventory feeds and "Urgency Boosts" to quickly secure fast-expiring, nutrient-dense items.
- **Logistics Module:** Empowers drivers with autonomous dispatching and real-time, turn-by-turn navigation optimized for perishable transit.

## Technical Architecture

Surplus utilizes a modern, high-performance tech stack:

- **Framework:** Next.js with React 19
- **Database & Auth:** Supabase for real-time data synchronization
- **Geospatial Engine:** Mapbox GL & Turf.js for Expiry-Aware Routing (prioritizing matches based on time-to-spoilage and distance)
- **State Management:** Zustand & React Query
- **UI/UX:** Tailwind CSS, Framer Motion, and Radix UI primitives for a highly responsive interface

## Installation & Setup

1. Clone the repository and install dependencies:
```bash
npm install
```

2. Configure your environment variables in a `.env.local` file (requires Supabase and Mapbox API keys).

3. Start the development server:
```bash
npm run dev
```

4. Navigate to `http://localhost:3000` to access the application.

## Development Commands

- `npm run build`: Create an optimized production build
- `npm run start`: Start the production server
- `npm run lint`: Execute ESLint for code quality checks

## The Impact

Surplus operates on a triple bottom line:
- **Environmental:** Prevents CO2 emissions by keeping organic waste out of landfills.
- **Social:** Delivers nutrient-dense meals to vulnerable communities.
- **Economic:** Provides tax savings for donors through automated compliance.

## License

This project is private and proprietary.
