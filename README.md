# Full-Screen Exam Platform with Timer and Exit Restriction

This is a simple exam app built with React.

## Local Development Setup

This project is using [Vite 5](https://vitejs.dev/blog/announcing-vite5.html). Node.js `>= 18.x` is required and setup with [pnpm](https://pnpm.io/) is recommended.

```sh
# Install all dependencies
pnpm install

# Serve
pnpm dev

# Build for production
pnpm build

# Run test
pnpm test
```
#### Bonus Features as included-

### Authentication

This app is using dummy / fake authentication. You can change it at [src/providers/auth.ts#L18](src/providers/auth.ts#L18).

### Exam lists

You can change the exam data at [src/\_data/exams.ts](src/_data/exams.ts).

### Question lists

You can change the question data at [src/\_data/questions.ts](src/_data/questions.ts).
