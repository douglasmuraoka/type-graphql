---
title: Examples
sidebar_label: List of examples
id: version-0.17.5-examples
original_id: examples
---

On the [GitHub repository](https://github.com/19majkel94/type-graphql) there are a few simple examples of how to use different TypeGraphQL features and how well they integrate with 3rd party libraries.

All examples have an `examples.gql` file with sample queries/mutations/subscriptions that we can execute.

## Basics

- [Simple usage of fields, basic types and resolvers](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/simple-usage)

## Advanced

- [Enums and unions](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/enums-and-unions)
- [Subscriptions (simple)](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/simple-subscriptions)
- [Subscriptions (using Redis)](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/redis-subscriptions)
- [Interfaces](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/interfaces-inheritance)

## Features usage

- [Dependency injection (IoC container)](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/using-container)
  - [scoped container](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/using-scoped-container)
- [Authorization](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/authorization)
- [Validation](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/automatic-validation)
- [Types inheritance](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/interfaces-inheritance)
- [Resolvers inheritance](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/resolvers-inheritance)
- [Generic types](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/generic-types)
- [Middlewares and Custom Decorators](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/middlewares-custom-decorators)

## 3rd party libs integration

- [TypeORM (manual, synchronous) \*](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/typeorm-basic-usage)
- [TypeORM (automatic, lazy relations) \*](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/typeorm-lazy-relations)
- [Typegoose](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/typegoose)
- [Apollo Engine (Apollo Cache Control) \*\*](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/apollo-engine)
- [Apollo client state](https://github.com/19majkel94/type-graphql/tree/v0.17.5/examples/apollo-client)

_\* Note that we need to edit the TypeORM example's `index.ts` with the credentials of our local database_

_\*\* Note that we need to provide an `APOLLO_ENGINE_API_KEY` env variable with our own API key_
