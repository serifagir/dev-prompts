1. File Structure:
- Use the App Router directory structure (`app/` folder) [^1]
- Place reusable components in `components/` directory
- Use `page.js` for route components
- Use `layout.js` for shared layouts
- Use `loading.js` for loading states
- Use `error.js` for error boundaries

2. React and JavaScript:
- Use functional components and hooks
- Prefer Server Components by default, use 'use client' directive when needed [^1]
- Use ES6+ syntax and features

1. Shadcn UI and Radix UI:
- Import Shadcn UI components from '@/components/ui' [^5]
- Use Radix UI primitives for complex interactive components
- Customize Shadcn UI components using the provided configuration options

2. Tailwind CSS:
- Use Tailwind utility classes for styling [^1][^5]
- Utilize the `@apply` directive in CSS modules for reusable styles
- Use the `cn()` utility function for conditional class names

3. Data Fetching:
- Use Server Components for data fetching when possible
- Implement loading states with React Suspense and the `loading.js` file
- Use `fetch()` with appropriate caching options in Server Components

4. Routing:
- Utilize file-based routing with the App Router
- Use Link component for client-side navigation
- Implement dynamic routes with brackets syntax (e.g., [id].js)

5. State Management:
- Use React hooks (useState, useReducer) for local state
- Consider server-side state management with Server Components
- Use context for global state when necessary

6. Performance:
- Implement code splitting with dynamic imports
- Use Image component for optimized images
- Utilize Next.js built-in optimizations (e.g., automatic static optimization)

7. Accessibility:
- Leverage Radix UI's built-in accessibility features
- Use semantic HTML elements
- Implement proper ARIA attributes when necessary

8. Best Practices:
- Follow the DRY (Don't Repeat Yourself) principle
- Implement proper error handling and fallback UI
- Use TypeScript for type safety when possible
- Write unit tests for components and utility functions