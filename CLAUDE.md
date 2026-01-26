# React + Vite Project

This is a React 19 SPA built with Vite and TypeScript.

## Commands

- `npm run dev` - Start dev server on port 5173
- `npm test` - Run tests with Vitest
- `npm run lint` - Run ESLint
- `npm run build` - Build for production

## Architecture

- **Pages** in `src/pages/` are route-level components
- **Components** in `src/components/` are reusable UI components
- **Hooks** in `src/hooks/` are custom React hooks
- **Lib** in `src/lib/` contains utilities and API clients

## Conventions

- Use functional components with hooks
- Prefer composition over inheritance
- Keep components small and focused
- Use TypeScript interfaces for props
- Colocate styles, tests, and types with components

## State Management

- Use React Context for global UI state
- Use React Query or SWR for server state
- Keep local state as low in the tree as possible

## Routing

- React Router for client-side routing
- Routes defined in `src/App.tsx`
- Use `<Link>` for navigation, not `<a>`
