# Technical rules [TechStacks has been used in this project, and you are an expert in these tech stacks(with best practice cases and LTS version)]:
- TypeScript
- React
- React Router
- Ant Design
- Tailwind
- Apollo Client
- GraphQL
- Vite
- Redux Toolkit
- Chart.js
- Other libraries in `package.json`

# Key Principles
- Write concise, technical TypeScript code with accurate examples.
- Use functional and declarative programming patterns; avoid classes components.
- Prefer iteration and modularization over code duplication.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError).
- Avoid comments, magic numbers, strings, and variables when generating code.

# Naming Conventions
- Use Uppercase with dashes for directories (e.g., components/AuthWizard).
- Favor named exports for components, hooks, and types. Pages component should be export default.

# TypeScript Usage
- Use TypeScript for all code; prefer interfaces over types.
- Avoid enums; use maps instead.
- Use functional components with TypeScript interfaces.

# Syntax and Formatting
- Use the "function" keyword for pure functions.
- Avoid unnecessary curly braces in conditionals; use concise syntax for simple statements.
- Use declarative JSX.
- Follow ESLint and Prettier rules config in root directory.

# UI and Styling
- Use Tailwind for components and styling to prefer pure CSS.
- Implement responsive design with Tailwind CSS; use a mobile-first approach.

# Performance Optimization
- Use `useMemo` and `useCallback` to ensure performance and avoid unnecessary re-renders in custom hooks.

# Rules review codebase after generating code
- Avoid infinite loops, infinite re-renders vulnerabilities in React components.
- Avoid using `useEffect` to fetch data in React components.
- Avoid string template to handle conditional logic in className attribute. Use `classNames`, `clsx` if available library instead.

# Step by step when get requirement
- Read the task description carefully. Split the task into smaller parts.
- Read the codebase to find related files and tech stacks. use `@website` command to search the docs of the tech stacks.
- Implement the task step by step.
- Review the code and make sure it meets all the requirements and fit with `Rules review codebase after generating code`.

# Commit generated format
- [type of task] include chore, fix, feat, refactor, docs, style, test, ci, build, perf, revert, revert:
- Commit message: [type of task]: [summary of the task]. Ex: feat: add new feature to the task.
- Commit message should be in English.
- Description format: `fileName: lineNumber: what change detail in lineNumber`. Ex: `src/pages/Home.tsx: 10: add props type to the component.
