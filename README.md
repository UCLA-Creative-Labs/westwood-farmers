# NextJS + Supabase Starter
Based off of [Supabase Docs](https://supabase.com/docs/guides/getting-started/tutorials/with-nextjs).

### Notes:
- Uses non-strict [TypeScript](https://www.typescriptlang.org/docs/) for beginner-friendliness. To set it to strict, modify `tsconfig.json`.
- Uses [App Router](https://nextjs.org/docs/app) version of NextJS.
- Use [TailwindCSS](https://tailwindcss.com/docs/installation) for utility CSS classes
- `@supabase/auth-helpers-nextjs @supabase/supabase-js` are pre-installed packages.

## Getting Started

1. Create a new Supabase project
2. Save your Supabase `URL`, `anon`, and `service_role` keys.
3. Click on `SQL Editor` on the left navigation.
4. Click on `Quickstarts`.
5. Click and run `User Management Starter`.

### Clone/fork this repository
1. Run: `git clone https://github.com/UCLA-Creative-Labs/nextjs-supabase`
2. Change your working directory into the repo: `cd nextjs-supabase`
3. Install Node.js packages: `npm i` or `yarn add`

### Set up your Supabase Environmental Variables
1. Create a new file in the repo called `.env.local`.
2. Write your `URL` and `anon` keys to this file:
```
NEXT_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
```

### To run development server:
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

### Now start developing!

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
