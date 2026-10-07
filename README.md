# Node.js Learning Modules

A collection progressing from a Node greeting to HTTP routing, an in-memory todo list, and Jest exercises.

## What is included

- `301_level_1`: greeting.
- `301_level_2`: HTTP pages.
- `301_level_3`: sample todo list.
- `301-level-4`: exported todo module and Jest tests.

## Getting started

Run `node 301_level_1/index.js` or `node 301_level_3/index.js`.

For the server, enter `301_level_2`, install `minimist`, and run `node index.js --port=3000`.

For tests:

```sh
cd 301-level-4
npm install
npm test
```

## Repository guide

- `301-level-4/`
- `301_level_1/`
- `301_level_2/`
- `301_level_3/`
- `README.md`

## Limitations and reproducibility

Modules are separate exercises. Run the HTTP server from its own directory. Tests are supplied for level 4 only; their presence does not establish that every exercise is production-ready.
