# Surplus

Surplus is a modern web application built with Next.js that leverages geospatial mapping and real-time database capabilities. The application features interactive maps, dynamic routing, and data visualization.

## Technologies

This project is built using a robust stack of modern web technologies:

- Framework: Next.js with React 19
- Styling: Tailwind CSS
- State Management: Zustand and React Query
- Database & Authentication: Supabase
- Mapping & Geospatial Analysis: Mapbox GL and Turf.js
- Animations: Framer Motion
- UI Components: Radix UI primitives (via CMDK, Sonner)

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 20 or higher recommended)
- npm, yarn, pnpm, or bun

## Installation

Clone the repository and install the dependencies:

```bash
npm install
```

## Configuration

Set up your environment variables by creating a `.env.local` file in the root directory. You will need to provide keys for Supabase and Mapbox. Refer to the existing configuration files or documentation for the specific keys required.

## Development

Start the local development server:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:3000` to view the application.

## Building for Production

To create an optimized production build, run:

```bash
npm run build
```

Then, you can start the production server:

```bash
npm run start
```

## Code Quality

This project uses ESLint for code linting. To check the code quality, run:

```bash
npm run lint
```

## Architecture and Structure

- `src/`: Contains the primary source code, including pages, components, hooks, and utility functions.
- `public/`: Stores static assets such as images and icons.
- `tests/`: Contains Playwright tests for end-to-end testing.

## License

This project is private and proprietary.
