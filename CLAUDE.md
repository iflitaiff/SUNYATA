# Guidelines for Claude

## Build, Lint & Test Commands
- Setup: `npm install`
- Dev server: `npm run dev`
- Build: `npm run build`
- Lint: `npm run lint`
- Test all: `npm run test`
- Test single file: `npm run test -- path/to/test-file.test.js`

## Code Style Guidelines
- Format: Use Prettier with project defaults
- Imports: Group in order: 1) React/frameworks 2) third-party 3) internal modules
- Typing: Use TypeScript with explicit return types on functions
- Naming: camelCase for variables/functions, PascalCase for components/classes
- Error handling: Use try/catch with specific error types, avoid generic error messages
- Comments: JSDoc for public APIs, inline comments for complex logic only
- Component structure: Props interface at top, hooks next, effects, render

Always run linting before committing changes.