# Creamy Creations FYP Project

> platform built with the MERN stack & Redux.

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Loader
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

```
NODE_ENV = development
PORT = 6000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

```

## Build & Deploy

```

# Create frontend prod build

cd frontend
npm run build

```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Seed Database


```

# Import data

npm run data:import

# Destroy data

npm run data:destroy

```



```
