# Stripe Checkout. Node Express Stripe

A Simple stripe checkout implementation.
Installation

```sh
npm init -y
npm i express stripe dotenv
npm i --save-dev nodemon
```
Open `package.json` in the `scripts` section add the following line:
`"devStart": "nodemon server.js"`

Create `.env` file and add 
`SERVER_URL=<yourserverurl>`
`STRIPE_PRIVATE_KEY=<yourstripeprivatekey>`

```sh
npm run devStart
```

Based in tutorial video: https://www.youtube.com/watch?v=1r-F3FIONl8