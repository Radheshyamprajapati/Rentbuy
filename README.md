# RentBuy Marketplace Starter

A runnable MVP for owners to list products and for customers to buy or rent by date. Includes availability checks, date-based pricing, mock checkout, and Razorpay integration hooks.

## Run

1. `cd server && npm install && cp .env.example .env && npm run dev`
2. `cd client && npm install && npm run dev`
3. Open `http://localhost:5173`

For real Razorpay testing, add test keys to `server/.env`; never expose the key secret in the client. The default checkout is mock mode.
