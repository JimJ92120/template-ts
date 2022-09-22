# template-ts

A template to use [`TypeScript`](https://www.typescriptlang.org/docs/handbook/intro.html) with [`WebPack 5`](https://webpack.js.org/concepts/) to compile.

---
---
## Requirements
|              |           |
|--------------|-----------|
| `npm`        | `^6.0`    |
| `Node.js`    | `^14.0`   |
| `TypeScript` | `^4.0`    |
  

## Project's structure

```sh
/(root)
  /src # app entrypoint (Typescript / JavaScript)
  /static # static assets (e.g index.html)
```


## How to install

```sh
npm install
```


## How to run in debug mode

```sh
# Builds the project and opens it in a new browser tab. Auto-reloads when the project changes.
npm start
```


## How to build in release mode

```sh
# Builds the project and places it into the `dist` folder.
npm run build
```
