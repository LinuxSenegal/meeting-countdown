# Meeting countdown

This is a [Next.js](https://nextjs.org/) project

## Getting Started

First, run the development server:

```bash
git clone https://github.com/Linux-Senegal/meeting-countdown
cd meeting-countdown
npm install
npm run dev

```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Change date

You can start editing the event date by modifying `postcss.config.js`.

```javascript
module.exports = {
    env: {
        eventDate: '2121-03-27 10:00:00 UTC',
    },
}
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.