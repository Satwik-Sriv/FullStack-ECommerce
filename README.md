<h1 align="center">E-Commerce Store 🛒</h1>

This project provides exposure to:

- An exposure towards the set-up, creating the frontend with react and design with tailwind as well as setting up the backend environment
- MongoDB & Redis Integration, connecting the databse
- Payment Setup (Stripe)
- Usage of JWT with Refresh/Access Tokens
- Data modelling as well as writing controllers for User Signup & Login
- E-Commerce Fundamental functionalities like product and category management, shopping cart functionality
- Additional functionalities such as Coupon system, Analytics, Admin dashboard
- Security and data protection methods

### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
