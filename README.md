# Personal Portfolio

This repository contains the source code for a personal portfolio website built with **React**, **TypeScript**, and **Vite**. Styling is provided by **Tailwind CSS** and animations use **Framer Motion**.

## Features
- Responsive layout with Tailwind CSS
- Hero, About, Projects, Bootcamp, Testimonials, Resume and Contact sections
- Routing handled by React Router
- GitHub Pages deployment via a GitHub Actions workflow

## Getting Started
1. Install Node.js (version 18 or later).
2. Install dependencies:
   ```bash
   cd project
   npm install
   ```
3. Launch the development server:
   ```bash
   npm run dev
   ```
4. Create a production build:
   ```bash
   npm run build
   ```
5. Preview the production build locally:
   ```bash
   npm run preview
   ```

## Project Structure
- `index.html` – HTML entry point.
- `src/` – React components, pages and assets.
- `public/` – Static files copied as-is during build.
- `dist/` – Output directory generated after running `npm run build`.

## Deployment
The `.github/workflows/deploy.yml` workflow builds the project and publishes the contents of `dist/` to GitHub Pages when triggered.
