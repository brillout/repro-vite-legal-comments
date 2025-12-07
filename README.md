Look at the [legal comment](https://esbuild.github.io/api/#legal-comments) added at [`git show HEAD~`](https://github.com/brillout/repro-vite-legal-comments/commit/8219bda36113274ba60d3072326ba062f3ebe898).

Then:

```
pnpm install
pnpm run build
```

See that the legal comment is missing in `dist/`.
