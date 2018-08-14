# typeshift

> TypeShift provides a common schema library for converting between different type systems.

[![NPM](https://img.shields.io/npm/v/typeshift.svg)](https://www.npmjs.com/package/typeshift) [![Build Status](https://travis-ci.com/hydrateio/typeshift.svg?branch=master)](https://travis-ci.com/hydrateio/typeshift) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)


## Motivation

**TODO**

## Status

**Early WIP Research**



## Packages

- [typeshift](packages/typeshift) - Main library exposing typeshift conversion and validation functionality.
- [typeshift-cli](packages/typeshift-cli) - CLI for converting between different type system adaptors.
- [typeshift-schema](packages/typeshift-schema) - Defines the common json schema format.
- [typeshift-adaptor](packages/typeshift-adaptor) - Abstract interface for source and sink adaptors.

#### Bidirectional Adaptors

These adaptors support conversions as both source and sink.

This means that for each of these adaptors, you can convert from `Source -> TypeShift` and from `TypeShift -> Sink`.

- [typeshift-adaptor-prop-types](packages/typeshift-adaptor-prop-types) - TypeShift adaptor for React PropTypes.
- [typeshift-adaptor-typescript](packages/typeshift-adaptor-typescript) - TypeShift adaptor for TypeScript.
- [typeshift-adaptor-flow](packages/typeshift-adaptor-flow) - TypeShift adaptor for Flow.
- [typeshift-adaptor-graphql](packages/typeshift-adaptor-graphql) - TypeShift adaptor for GraphQL.

#### Sink Adaptors

These adaptors only support conversion from `TypeShift -> Sink`.

- [typeshift-adaptor-markdown](packages/typeshift-adaptor-markdown) - TypeShift adaptor for Markdown (sink).
- [typeshift-adaptor-pojo](packages/typeshift-adaptor-pojo) - TypeShift adaptor for [POJO](https://spring.io/understanding/POJO) (Java).

#### Source Adaptors

These adaptors only support conversion from `Source -> TypeShift`.

**TODO**


## Related

- [json schema](http://json-schema.org) - Allows you to annotate and validate JSON documents.
- [react-docgen](https://github.com/reactjs/react-docgen) - Extracts documentation info from React component files.
- [apollo-cli](https://github.com/apollographql/apollo-cli) - CLI for managing Apollo workflows.
- [Swagger / OpenAPI](https://swagger.io/docs/specification/data-models)
- [jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo) - Generate Java types from JSON Schema.

**TODO**: needs more background research.


## License

MIT © [Hydrate](https://hydrate.io)
