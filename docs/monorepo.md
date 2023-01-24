### Monorepo

- move pnpm to yarn [tutorial](https://blog.logrocket.com/build-monorepo-next-js/), [docs](https://turbo.build/repo/docs/getting-started/existing-monorepo)
- search youtube - turborepo yarn
- use this example [vercel/turbo/examples/with-yarn](https://github.com/vercel/turbo/tree/main/examples/with-yarn)

### Migrate from pnpm to yarn

- [docs](https://turbo.build/repo/docs/handbook/workspaces)

```ts
// services/client/apps/app/package.json.

// from pnpm syntax
"dependencies": {
    "@acme/ui": "workspace:*",
    "@acme/utils": "workspace:*",
},

// to yarn syntax
"dependencies": {
    "@acme/ui": "*",
    "@acme/utils": "*",
},
```

