---

# .windsurfrules

## Project Overview
- **Type:** Derived from `windsurf_file`
- **Description:** AI Prompt for Developing a Mobile & Web Application for a Fitness Card Game
- **Primary Goal:** Making workouts more enjoyable and interactive through gamification and progress tracking.

## Project Structure
### Framework-Specific Routing
- **Directory Rules:**  
  - "Next.js 14 (App Router)" → Use `app/[route]/page.tsx` for web components
  - "React Native" → Utilize components in `src/components` with `expo` for mobile
  - Example: "React.js" → Follow component-based structure under `src`

### Core Directories
- **Versioned Structure:**  
  - `src/components`: "React 17 functional components for web"
  - `src/views`: "React Native screens following Expo's standards for mobile"
  - Example: `app/api` → "Next.js 14 API routes using App Router patterns"

### Key Files
- **Stack-Versioned Patterns:**  
  - `app/layout.tsx`: "Next.js 14 layout file for consistent page structure"
  - `pages/index.js`: "Next.js main entry point when using Pages Router"
  - `src/App.js`: "Entry file for React Native project with Expo support"

## Tech Stack Rules
- **Version Enforcement:**  
  - `next@14`: "Ensure App Router usage for server-side rendering"
  - `react-native@0.68`: "Adhere to functional components and hooks"
  - Firebase Authentication should be leveraged for secure user sessions.

## PRD Compliance
- **Non-Negotiable:**  
  - "Develop a cross-platform mobile and web app offering" must use Next.js and React Native" for supporting web and mobile interfaces.

## App Flow Integration
- **Stack-Aligned Flow:**  
  - Example: "Next.js 14 Auth Flow → `app/auth/login/page.tsx` employs server actions for user login"

---