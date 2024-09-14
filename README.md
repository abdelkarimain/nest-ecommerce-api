# nest-ecommerce-api

This is a NestJS backend for an e-commerce platform.

## Features

- User management: registration, login, profile management, role management
- Product management: product creation, listing, details, update/delete, category management, and inventory management
- Order management: order placement, order history, order tracking, order cancellation/returns, payment integration, and invoice generation
- Wishlist management: add/remove products to/from wishlist
- Search and filtering: search for products by name, category, and price range
- Notifications: send email and SMS notifications to customers and admins
- Sales reports and analytics: generate sales reports and analytics for admins

## Installation

1. Clone the project
2. Run `npm install` to install dependencies
3. Run `npm run start:dev` to start the application in development mode
4. Run `npm run build` to build the application for production

## Environment variables

The application uses the following environment variables:

- `DATABASE_URL`: the URL of the database
- `SECRET_KEY`: the secret key for JWT authentication
- `STRIPE_SECRET_KEY`: the secret key for Stripe payment integration
- `PAYPAL_CLIENT_ID`: the client ID for PayPal payment integration
- `PAYPAL_CLIENT_SECRET`: the client secret for PayPal payment integration

## Technologies used

- NestJS
- TypeORM
- SQLite
- Stripe
- PayPal
- Nodemailer
- Twilio

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.