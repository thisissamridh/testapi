This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

For phone number verification to work with twillio, follow part of [this](https://www.twilio.com/blog/phone-verification-react-native) tutorial to setup the twilio verify backend.

Add the issuer private key `NEXT_PUBLIC_ISSUER_PRIVATE_KEY` and the twilio URL `NEXT_PUBLIC_TWILIO_URL` to the .env file

Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
