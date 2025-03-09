# Chronolex

A modern Next.js application with TypeScript, Tailwind CSS, and ESLint configuration.

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Features

- **Next.js 14** - The React framework with server-side rendering and static site generation
- **TypeScript** - Static type checking for JavaScript
- **Tailwind CSS** - A utility-first CSS framework
- **ESLint** - Linting for JavaScript and TypeScript
- **Modern Project Structure** - App Router with organized directories

## Project Structure

```
├── src/
│   ├── app/            # App router pages and layouts
│   │   ├── api/        # API routes
│   │   ├── globals.css # Global styles
│   │   ├── layout.tsx  # Root layout
│   │   └── page.tsx    # Home page
│   ├── components/     # Reusable UI components
│   └── lib/           # Utility functions, hooks, etc.
├── public/            # Static assets
├── next.config.mjs    # Next.js configuration
├── tailwind.config.js # Tailwind configuration
├── postcss.config.js  # PostCSS configuration
└── tsconfig.json      # TypeScript configuration
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

## Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.