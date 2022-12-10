This is a [Next.js](https://nextjs.org/) project which allow you to use https with custom server.

## Getting Started

First, get your cert:
```bash
brew install mkcert
mkcert -install
mkdir certs 
cd certs
mkcert localhost
```

Second, run your development server:

```bash
npm run dev
# or
yarn dev
```

Open [https://localhost:3000](https://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.


