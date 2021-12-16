![example workflow](https://github.com/Betarena/scores/actions/workflows/docker-image.yml/badge.svg)

# scores
### Betarena Scores Platform

### About

We are building the first open-source live results and statistics platform with community involvement features for data insertion. The project includes a blockchain component that will allow participants to receive rewards based on their participation and also to stake the future Token of the platform.

### Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

### Building

Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

```bash
npm run build
```

> You can preview the built app with `npm run preview`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.

### SEO Optimization

https://github.com/artiebits/svelte-seo#svelte-seo-options

### Svelte Appollo

For the ability to use `GraphQL` for the Widget in Svelte, `svelte-appollo` was used: ![svelte-apollo](https://github.com/timhall/svelte-apollo), paired with the docuemntation from ![`Hasura`](https://hasura.io/learn/graphql/svelte-apollo/queries/2-create-query/) to have the widget working correctly.

![npm-package](https://www.npmjs.com/package/svelte-apollo)

Future expansion: https://dev.to/lucis/update-apollo-cache-after-a-mutation-and-get-instant-benefits-on-your-ui-1c3b

❌ - `@apollo-client` sveltekit issues - ![1](https://github.com/timhall/svelte-apollo/issues/97)
✔ - solution ![hasura-db-example](https://rodneylab.com/use-apollo-client-sveltekit/)

### localStorage()

The widget stores the users `one-off` voting using the `.localStorage()` for the ability to give the user a history of past votings.

### using .env with sveltekit-vite:

https://dev.to/danawoodman/storing-environment-variables-in-sveltekit-2of3

### Getting started with `sveltekit`:

https://www.sitepoint.com/a-beginners-guide-to-sveltekit/
https://www.reddit.com/r/sveltejs/comments/p28oht/how_to_redirect_to_a_url_in_svelte_kit/
https://stackoverflow.com/questions/67135169/how-to-initialize-apolloclient-in-sveltekit-to-work-on-both-ssr-and-client-side
https://www.npmjs.com/package/graphql-request

https://www.sitepoint.com/a-beginners-guide-to-sveltekit/

https://coderoad.ru/62950447/NPM-%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%B8%D1%82%D1%8C-%D1%87%D1%82%D0%BE-%D1%82%D0%BE-%D0%B8%D0%B7-github-%D0%B2-%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80-docker-%D0%BD%D0%B5-%D1%83%D0%B4%D0%B0%D0%B5%D1%82%D1%81%D1%8F

Fixing DOCKER /ENONT issue...

Using `GitHub Actions` | [link-solution](https://stackoverflow.com/questions/66247264/github-actions-how-can-i-make-my-env-variablestored-in-env-file-available-i) | [link-solution-2](https://stackoverflow.com/questions/61117865/how-to-set-environment-variable-in-node-js-process-when-deploying-with-github-ac)