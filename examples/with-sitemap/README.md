# With Sitemap example

This example shows how to generate Sitemap for static [Next.js](https://nextjs.org/) paths.
Every time, you try to start a development server or make a build, you get an updated `sitemap.xml` file in the `public` directory(`http://localhost:3000/sitemap.xml`).

The website URL can be changed from `.env` file in the project root.

```
# Used to add the domain to sitemap.xml, replace it with a real domain in production
WEBSITE_URL=http://localhost:3000
```

**Note**: Every time you add or remove a page from the `pages` directory, you need to restart the server, to update your `pages/sitemap.xml` file.

## Deploy your own

Deploy the example using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/next.js/tree/canary/examples/hello-world)

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-sitemap with-sitemap-app
# or
yarn create next-app --example with-sitemap with-sitemap-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/vercel/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-sitemap
cd with-sitemap
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/import?filter=next.js&utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).