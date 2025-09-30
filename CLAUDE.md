# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Japanese task management application built with Next.js 15 and React 19. The project is located in the `task-manager-test/` directory and implements a modern task manager with priority levels, filtering, and local storage persistence.

## Development Commands

All commands should be run from the `task-manager-test/` directory:

```bash
# Install dependencies
npm install

# Start development server with Turbopack
npm run dev

# Build for production with Turbopack
npm run build

# Start production server
npm start

# Run ESLint
npm run lint
```

## Architecture

- **Framework**: Next.js 15 with App Router and Turbopack
- **UI**: React 19 with TypeScript, Tailwind CSS 4
- **State Management**: Local React state with localStorage persistence
- **Main Component**: `src/app/page.tsx` contains the complete TaskManager component
- **Styling**: Tailwind CSS with custom gradient backgrounds and modern UI components

## Key Features

- Task creation with priority levels (high/medium/low)
- Task completion toggling and deletion
- Filtering by status (all/completed/pending)
- Progress tracking with completion percentage
- Local storage persistence
- Responsive design with Japanese text content

## Tech Stack

- Next.js 15.5.4 with Turbopack
- React 19.1.0
- TypeScript 5
- Tailwind CSS 4
- ESLint with Next.js config

## File Structure

- `src/app/page.tsx` - Main task manager component (client-side)
- `src/app/layout.tsx` - Root layout with Geist fonts
- `src/app/globals.css` - Global styles and Tailwind directives
- TypeScript and ESLint configuration files in root