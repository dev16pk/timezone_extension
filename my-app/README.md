# My App - Piral Micro Frontend Monorepo

This is a monorepo for a Piral-based micro frontend architecture.

## Structure

- `shell-app/` - The Piral shell application (host)
- `pilets/` - All pilets (micro frontends)
  - `cart-pilet/` - Cart feature micro frontend
  - `guided-selling-pilet/` - Guided Selling feature micro frontend
- `shared/` - Shared code (utils, types, UI components)

## Getting Started

1. Install dependencies: `npm run install:all`
2. Start the shell application: `npm run start:shell`
3. Start individual pilets: `npm run start --workspace=pilet-name`

## Development

Each pilet is a separate package that can be developed independently.
The shell app serves as the host for all pilets.