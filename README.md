# shopify-oauth-with-node.js
Implementing Shopify OAuth with Node.js


## Usage
Clone the repo and npm install!

```
npm install
node index.js
```

Word to the wise: don't include the scheme (https://) in your host URL in .env - it will bork the redirect from Shopify back to your app.  That's 20 minutes I'll never get back.