# Order Book

This is a simple order book to view recent  trades. For optimal frontend performance, it uses web workers to process the huge volume of updates from the websocket server. Orders are throttled before being sent to the frontend UI which handles painting the orders.

# To run it locally:

```
$ npm run start
```

and then visit `localhost:3000/index.html`