This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

// ABOUT ALL THE NEW LIBRARY AND FUNCTIONALITY

1. UploadThings => UploadThing is the easiest way to add file uploads to your full stack TypeScript application. Many services have tried to build a "better S3", but in our opinion, none found the right compromise of ownership, flexibility and safety.
   => In UploadThings there is one utility class withUT => To leverage the best developer experience, we strongly recommend wrapping your Tailwind config with our utility function withUt. This utility function adds additional classes and variants used to style our components. In addition, it also automatically sets the content option to include all the necessary classes that the components use. This allows you to avoid having duplicated styles in your bundle. Therefore, when using withUt, you should not import our stylesheet into your app. If you choose not to use withUt, you have to import the default stylesheet to make the components look right.

2. Clerk => Clerk is a powerful authentication and user management platform designed to simplify authentication in Next.js and Reactjs applications, offering an exceptional developer experience and robust user security.
   => You can do the following using Clerk:
   Allow people to check in using their existing Google, GitHub, or other social network accounts.
   Allow users to log in without a password by utilizing a one-time passcode (OTP) sent to their phone.
   Control user accounts, responsibilities, and permissions from just one dashboard.
