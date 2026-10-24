# @x12i/docify-core usage example

Schemas and helpers for x12i docify libraries (catalog, use-cases, site pages, manifests).

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `1.6.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- A consumer needs the following capability: Schemas and helpers for x12i docify libraries (catalog, use-cases, site pages, manifests).
- A Docify integration needs to reuse the capabilities of @x12i/docify-core inside a larger application.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/docify-core)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
