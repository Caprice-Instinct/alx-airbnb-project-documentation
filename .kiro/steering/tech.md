# Technology Stack & Build System

## Architecture

- **Backend Type**: RESTful API
- **Database**: Relational database (PostgreSQL/MySQL recommended)
- **Authentication**: JWT-based with role-based access control
- **File Storage**: Cloud storage (AWS S3/Cloudinary) for property images

## Core Technologies

- **API Design**: RESTful endpoints with proper HTTP methods and status codes
- **Security**: Encryption, rate limiting, input validation
- **Caching**: Redis for performance optimization
- **Email Service**: Third-party integration (SendGrid/Mailgun)
- **Payment Processing**: Stripe or PayPal integration

## Database Schema

Core tables include:

- Users (guests, hosts, admins)
- Properties (listings with details and amenities)
- Bookings (reservations with status tracking)
- Reviews (ratings and feedback)
- Payments (transaction records)

## Development Standards

- Global error handling and logging
- Comprehensive testing (unit, integration, API tests)
- Modular architecture for scalability
- Multi-currency support for payments

## Common Commands

_Note: Specific build/test commands will depend on the chosen framework (Node.js/Express, Python/Django, etc.)_

```bash
# Typical development workflow
npm install          # Install dependencies
npm run dev          # Start development server
npm test            # Run test suite
npm run build       # Build for production
```
