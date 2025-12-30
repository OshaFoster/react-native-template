# React Native Template

Personal React Native template with Expo Router pre-configured for quick project starts.

## What's Included

- **Expo Router** - File-based routing with typed routes enabled
- **TypeScript** - Fully configured with path aliases (`@/*`)
- **React Native Reanimated** - For smooth animations
- **Theming** - Light/dark mode support built-in
- **Tab Navigation** - Pre-configured bottom tabs layout
- **Prettier** - Code formatting ready to go
- **ESLint** - Expo lint configuration
- **React Compiler** - Enabled for optimizations

## Quick Start

```bash
npm install
npm start
```

Then press:
- `i` for iOS simulator
- `a` for Android emulator
- `w` for web

## Available Scripts

- `npm start` - Start Expo dev server
- `npm run ios` - Start on iOS
- `npm run android` - Start on Android
- `npm run web` - Start on web
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier
- `npm run format:check` - Check code formatting

## Project Structure

- `app/` - File-based routing (Expo Router)
  - `(tabs)/` - Tab navigation screens
  - `_layout.tsx` - Root layout
- `components/` - Reusable components
- `constants/` - Theme and constants
- `hooks/` - Custom React hooks

## Notes

- Path aliases configured: use `@/` to import from root
- Typed routes enabled - get autocomplete for navigation
- New Arch enabled by default
