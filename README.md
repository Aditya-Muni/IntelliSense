# IntelliSense

[![Project Image](https://raw.githubusercontent.com/Aditya-Muni/IntelliSense/master/public/thumbnail.png)](https://intellisense-omega.vercel.app/)

### What it does ?
IntelliSense lets you upload your pdf file and talk to it with ease. Comes with 2 plans basic (size < 4mb and pages < 5 ) and a pro plan (size < 16mb and pages < 40 ).
Built with the Next.js 13.5 App Router, tRPC, TypeScript, Prisma & Tailwind.

Visit link: https://intellisense-omega.vercel.app

## Features

- Subscription model using Stripe
- Authentication Using Kinde
- Data Fetching Using tRPC & Zod
- LangChain for Infinite AI Memory
- Pinecone as our Vector Storage
- Prisma as our ORM
- TypeScript



## How to  run locally
1.Clone the Repository:
```bash
  git clone https://github.com/Aditya-Muni/IntelliSense
```

2.Navigate to the Project Directory:
```bash
cd IntelliSense
```

3.Open console and run
```bash
  npm install
``` 
4.Create a .env file (example .env)

KINDE_CLIENT_ID=
KINDE_CLIENT_SECRET=
KINDE_ISSUER_URL=
KINDE_SITE_URL=
KINDE_POST_LOGOUT_REDIRECT_URL=
KINDE_POST_LOGIN_REDIRECT_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

PINECONE_API_KEY=
OPENAI_API_KEY=

STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=



## Live Project

https://intellisense-omega.vercel.app
