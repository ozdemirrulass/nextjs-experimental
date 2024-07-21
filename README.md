This repository is to experiment and polish NextJS basics knowledge. After working on backend systems and systems design for a long time I felt the need of re-learning NextJS basics.

## Covered Topics
- CSS Styling
- Optimizing Fonts and Images
- Creating Layouts and Pages
- Navigating Between Pages
- Database Interactions
- Fetching Data
- Static and Dynamic Rendering
- Streaming
- Partial Prerendering
- Adding Search and Pagination
- Mutating Data
- Handling Errors
- Validations and Accessibility
- Credential Authentication
- Metadata

## Setting Up
This repository uses Vercel's postgres service so you'll need `.env.local` file with the following content.

```bash
POSTGRES_URL=
POSTGRES_PRISMA_URL=
POSTGRES_URL_NO_SSL=
POSTGRES_URL_NON_POOLING=
POSTGRES_USER=
POSTGRES_HOST=
POSTGRES_PASSWORD=
POSTGRES_DATABASE=
```

Also you'll need a secret key for NextAuth. To acquire this key you may run the following command in your terminal.

```bash
openssl rand -base64 32
```
Copy the output and paste it to env with the following env variable definition.
```
AUTH_SECRET=
```

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


