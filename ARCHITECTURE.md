# Architecture

Client (React/Vite) -> REST API (Express) -> PostgreSQL/Prisma (production).

MVP routes:
- GET /api/products
- GET /api/products/:id
- POST /api/products
- POST /api/bookings/quote
- POST /api/bookings
- POST /api/payments/razorpay/order
- POST /api/payments/razorpay/verify

Production controls: server-side price calculation, database transaction for booking creation, unique payment/order IDs, webhook verification, idempotency keys, owner verification, file storage, rate limiting, audit logs, GST invoices, refunds, and background reminders.
