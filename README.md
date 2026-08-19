# Jira Clone

A Jira-style project management web application built with Next.js, React, TypeScript, and Tailwind CSS.

## Overview

The repository provides a frontend application structured around the Next.js App Router. It uses reusable UI components, Tailwind CSS for styling, TypeScript for type safety, and the Radix/Lucide ecosystem for interface icons.

## Technology Stack

- Next.js 14.2
- React 18
- TypeScript 5
- Tailwind CSS 3
- Radix UI icons
- Lucide React
- ESLint / Next.js linting

## Architecture

```text
Browser
   |
   v
Next.js App Router
   |
   +--> Pages / Routes
   +--> Reusable UI Components
   +--> Project Management Views
   |
   v
Client-side application state / server boundaries
```

## Repository Structure

```text
.
├── src/                # Application source code
├── components.json     # UI component configuration
├── next.config.mjs     # Next.js configuration
├── tailwind.config.ts  # Tailwind configuration
├── package.json        # Dependencies and scripts
└── tsconfig.json       # TypeScript configuration
```

## Development

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
npm run start
```

Run linting:

```bash
npm run lint
```

The application is normally available at `http://localhost:3000`.

## UI & Styling

Tailwind CSS provides utility-first styling. `tailwind-merge`, `clsx`, and `class-variance-authority` support composable component styling, while Radix UI and Lucide provide icon primitives.

## Project Status

The repository is a Next.js-based Jira-style application foundation. The source under `src/` contains the application implementation, while the root configuration files define the framework, styling, linting, and TypeScript setup.
