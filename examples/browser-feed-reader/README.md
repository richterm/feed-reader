# browser-feed-reader

This demo shows how to use `feed-extractor` at client side, with or without proxy.

To install:

```bash
npm i

# or pnpm, yarn
```

Start server:

```bash
npm start
```

Open `http://localhost:3103/` to test.

Basically `feed-extractor` only works at server side.

However there are some noble publishers those enable `Access-Control-Allow-Origin` on their service.
For example with feed resource from [FeedBlitz](https://feeds.feedblitz.com/baeldung/cs&x=1) we can read from browser.

Another ideal environment to run `feed-extractor` directly is browser extensions.

With the remaining cases, we need a proxy layer to bypass CORS policy.

---
