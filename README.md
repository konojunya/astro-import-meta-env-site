# astro-import-meta-env-site

1. `yarn create astro`
2. create project use recommend & install deps
3. edit `astro.config.mjs`

```js
export default defineConfig({
  site: "https://example.com",
});
```

4. edit `pages/index.astro`

```diff
+ <h1>{import.meta.env.SITE}</h1>
```

![](screenshot.png)
