1. Install dependencies for both the client and server:

```sh
# Install client dependencies
cd client && npm install

# Install server dependencies
cd ../ && npm install
```

2. Set up environment variables by creating a .env file in the root of the project with the following keys:

```sh
MONGO_URI=<your_mongo_uri>
JWT_SECRET=<your_jwt_secret>
BRAINTREE_MERCHANT_ID=<your_braintree_merchant_id>
BRAINTREE_PUBLIC_KEY=<your_braintree_public_key>
BRAINTREE_PRIVATE_KEY=<your_braintree_private_key>
EMAIL_FROM=<your_email_address>
```

3. Start the server: (cd ../)

```sh
npm run start
```

4. Start the client: (cd client)

```sh
npm run start 
```
