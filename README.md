# flagtag

A minimal serverless API example built for Vercel. This project uses TypeScript and the Vercel runtime for Node.js functions.

## Requirements

- Node.js (tested with Node 20)
- The [Vercel CLI](https://vercel.com/docs/cli)

## Install dependencies

```bash
npm install
```

## Build the function

Compile the TypeScript source in `api/` to JavaScript:

```bash
npm run build
```

## Run locally

Use the Vercel CLI to start a local dev server:

```bash
npx vercel dev
```

Requests to `/api/hi` will return a JSON response.

## Deploy to Vercel

```bash
# login if you haven't already
npx vercel login

# deploy and follow the prompts
npx vercel deploy --prod
```

## License

[Apache-2.0](LICENSE)

