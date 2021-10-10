This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) and set up to [deploy with Docker](https://nextjs.org/docs/deployment#docker-image).

See the default Readme.md packaged with Next.js projects [here](https://github.com/vercel/next.js/blob/canary/packages/create-next-app/templates/default/README-template.md).

## Getting Started

First, build the Docker container:

```bash
docker build . -t my-next-js-app
```

Then run the container:

```bash
docker run -it -p 3000:3000 my-next-js-app
```