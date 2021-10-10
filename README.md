This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) and set up to [deploy with Docker](https://nextjs.org/docs/deployment#docker-image).

See the default Readme.md packaged with Next.js projects [here](https://github.com/vercel/next.js/blob/canary/packages/create-next-app/templates/default/README-template.md).

## Getting Started

First, build the Docker container:

```bash
docker build . -t treadmill-activities
```

Then run the container:

```bash
docker-compose run --service-ports treadmill-activities npm run dev
```

Remember to cleanup once your are done (optional):

```bash
docker-compose down
```