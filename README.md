This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Stacks

### Core

- typescript
- react
- React framework: nextjs
- CSS Framework: react-bootstrap
- Additional styles: style-components
- State management: react context/hooks
- Managing calling API: react-query
- Showcase: story-book

### Test/Lint

- eslint/prettier
- Jest/React Testing library
- Cypress
- husky

### CI

- CircleCI/Jenkins/Github Action... (will pick one)

### CD

- Vercel(for dev/staging deployment)
- AWS(prod)

## Installation

Use yarn to install dependencies.

```bash
yarn
```

## Getting Started

First, run the development server:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Testing

### Run Tests with watch mode

```bash
yarn test
```

### Run tests for coverage

```bash
yarn coverage
```

## Lint

```bash
yarn lint
```

## Story book

```bash
yarn storybook
```
