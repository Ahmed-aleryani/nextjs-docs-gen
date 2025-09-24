# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Next.js 15.5.3 application with App Router architecture, TypeScript, and Tailwind CSS v4. The project appears to be intended for documentation generation purposes.

## Commands

### Development
```bash
npm run dev        # Start development server with Turbopack (http://localhost:3000)
npm run build      # Build for production with Turbopack
npm run start      # Start production server
npm run lint       # Run ESLint
```

## Architecture

### Tech Stack
- **Framework**: Next.js 15.5.3 with App Router
- **Language**: TypeScript with strict configuration
- **Styling**: Tailwind CSS v4 with PostCSS
- **Build Tool**: Turbopack enabled for faster builds
- **Fonts**: Optimized Geist Sans and Geist Mono fonts

### Project Structure
- `/app/` - Next.js App Router pages and layouts
  - `layout.tsx` - Root layout with font configuration
  - `page.tsx` - Homepage component
  - `globals.css` - Global styles and Tailwind imports
- `/public/` - Static assets (SVG icons, images)

### Key Configuration
- **TypeScript**: Strict mode enabled with Next.js plugin
- **Path Aliases**: `@/*` maps to project root
- **ESLint**: Configured with Next.js core web vitals rules
- **Tailwind**: v4 with inline theme configuration in globals.css

## Development Notes

- The project uses modern Next.js App Router patterns (not Pages Router)
- Turbopack is enabled for improved development performance
- CSS theming uses CSS custom properties for light/dark mode support
- No testing framework is currently configured