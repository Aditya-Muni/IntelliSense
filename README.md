# IntelliSense
(Always updated link: https://intelli-sense.vercel.app)

[![Project Image](https://raw.githubusercontent.com/Aditya-Muni/IntelliSense/master/public/thumbnail.png)](https://intelli-sense.vercel.app)

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

KINDE_CLIENT_ID=<br />
KINDE_CLIENT_SECRET=<br />
KINDE_ISSUER_URL=<br />
KINDE_SITE_URL=<br />
KINDE_POST_LOGOUT_REDIRECT_URL=<br />
KINDE_POST_LOGIN_REDIRECT_URL=<br />
DATABASE_URL=<br />
UPLOADTHING_SECRET=<br />
UPLOADTHING_APP_ID=<br />
PINECONE_API_KEY=<br />
OPENAI_API_KEY=<br />
STRIPE_SECRET_KEY=<br />
STRIPE_WEBHOOK_SECRET=<br />



## Live Project

https://intelli-sense.vercel.app
