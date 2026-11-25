# eng-lab

Hands-on practice for my engineering learning: small labs and experiments in TypeScript, Node.js, React, NestJS, databases and infrastructure. Each lab turns a concept into working code, and its commit history shows the path from prediction to conclusion.

## Structure
```
js/          JavaScript core: scope, closures, event loop, async
ts/          TypeScript: narrowing, generics, utility types
react/       React: rendering, effects, keys, forms
next/        Next.js App Router experiments
node/        Node.js runtime: event loop, streams, modules
nest/        NestJS: modules, DI, guards, pipes, testing
db/          SQL / PostgreSQL, indexes, transactions, ORMs
docker/      Dockerfiles, compose, CI pipelines
algorithms/  Problem solutions grouped by pattern
```

Each lab lives in `<area>/<nn>-<slug>/` with its own README: **Goal → How to run → What I learned**.

## Workflow
- One branch per lab: `lab/<area>-<nn>-<slug>`.
- For experiments, the prediction is committed before the code.
- Conventional Commits; each lab ends with a PR describing what I built and learned.

## Labs
| Lab | Topic | Status |
|---|---|---|
| — | first lab coming with JS core | — |
