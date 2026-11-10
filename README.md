# Learn by R&M — tutor marketplace frontend

An original, responsive language-tutor marketplace concept inspired by common tutor-platform workflows. It is not a copy of Preply branding or proprietary assets.

## Run it
- Open `index.html` in a modern browser, or serve this folder with any static web server.
- No build step or dependencies are required.

## Included in this demo
- Responsive landing page and navigation
- Language filters and tutor cards
- Search by language
- Tutor booking modal with date/time selection and basic form validation
- Sign-up / log-in demo form

## Important: demo limitations
This is a frontend prototype. Booking requests are not sent anywhere, authentication is not connected, tutor data is sample data, and there is no payment processing, video classroom, messaging, reviews backend, or admin panel.

## Suggested production stack
- Frontend: Next.js + TypeScript
- Backend: Node.js/NestJS or Next.js API routes
- Database: PostgreSQL (users, tutors, availability, bookings, reviews)
- Authentication: Auth.js, Clerk, or equivalent
- Payments: Stripe or a locally supported payment provider
- Video lessons: Daily, Agora, or Zoom SDK
- Storage: S3-compatible object storage

Before launch, add server-side validation, role-based access (student/tutor/admin), timezone-safe availability, booking conflict prevention, payment webhooks, privacy controls, moderation, and automated tests.
