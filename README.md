# remix-tutorial

A user contacts CRUD app built with Remix and React

NOTE: Need to migrate the in-memory data to a database. Currently, the data is lost when Vercel's Function instances are recycled, leading to seamingly random 404 errors.

- [Production app on Vercel](https://remix-tutorial-ryansobol.vercel.app/)

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `remix build`

- `build/server`
- `build/client`
