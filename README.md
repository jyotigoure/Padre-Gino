# Padre Gino's

A complete pizza-ordering application built with React.

## Features

- Pizza menu and pizza of the day
- Cart and checkout
- Past-order history
- Contact form
- Client-side routing with TanStack Router
- Data fetching and caching with TanStack Query
- Error boundaries and automated tests

## Local Development

Use Node.js 20, then install dependencies and start Vite:

```bash
npm install
npm run dev
```

The development server proxies requests to the hosted course API. A separate backend process is not required.

## Commands

```bash
npm run dev      # start the development server
npm run build    # create a production build
npm run preview  # preview the production build
npm run lint     # run ESLint
npm test         # run tests in watch mode
```

## Deploy to Vercel

Import the repository into Vercel and keep the root directory set to the repository root. Vercel detects Vite and runs `npm run build`. The included `vercel.json` supports direct navigation to client-side routes.

## Maintainer

jyotigoure <rohitchouhanilu143@gmail.com>
