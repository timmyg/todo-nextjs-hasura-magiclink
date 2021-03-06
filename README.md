<p align="center">
    <img width="460" src="./public/poopasaurus.png">
</p>

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

This is meant to be a boilerplate for new apps using the following:
* [nextjs](https://nextjs.org/) with serverless api routes
* [hasura](https://hasura.io/) (postgres/graphql) for database
* [magic link](https://magic.link) for passwordless authentication

The following are also recommended for easy deployment:
* [vercel](https://vercel.com) for deployment and hosting of nextjs frontend and backend
* [heroku 1-click install](https://hasura.io/) for hosting hasura/postgres graphql database

The demo app being built is poopasaurus - a way to log a baby's poops, pees, feedings, naps, etc.

To see the full poopasaurus app, go to [https://github.com/timmyg/poopasaurus](https://github.com/timmyg/poopasaurus)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Copy `.env.template` to `.env.local` and fill in environment variables. You will need to create a hasura graphql database. You can import the activities and babies schemas via `db/schema.graphql` with the graphqurl npm package. You will need to manually create a baby with id 1 via the hasura UI. Baby id 1 is currently hardcoded in the frontend.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

<p align="center">
    <img width="960" src="./public/screenshot.png">
</p>

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Notes
- /login is not fully implemented but you can get started with it.

> Dinorsaur and poops icons made by [Freepik](https://www.flaticon.com/authors/freepik) from [www.flaticon.com](www.flaticon.com)

