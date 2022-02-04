# shopify-oauth-with-node.js
Implementing Shopify OAuth with Node.js


## Usage
Clone the repo and npm install!

```
npm install
node index.js
```

Word to the wise: don't include the scheme (https://) in your host URL in .env - it will bork the redirect from Shopify back to your app.  That's 20 minutes I'll never get back.

### Credit
This is based on the very clear and concise video provided by the ShopifyDevs (Liz)

[![Implementing Shopify OAuth with Node.js](https://img.youtube.com/vi/oKGR9RVCUDs/0.jpg)](https://www.youtube.com/watch?v=oKGR9RVCUDs)