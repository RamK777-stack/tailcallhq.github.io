---
title: "Operators"
---

Tailcall DSL builds on your existing GraphQL knowledge by allowing the addition of some custom operators. These operators provide powerful compile time guarantees to ensure your API composition is tight and robust. The system automatically generates highly optimized resolver logic for your types using the operator information.

Here is a list of all the custom operators supported by Tailcall:

Certainly! Here's the table with hyperlinks added back to the operator names:

<!-- SORT OPERATOR BY NAME -->

| Operator                  | Description                                                                                                  |
| ------------------------- | ------------------------------------------------------------------------------------------------------------ |
| [@addField](add-field.md) | Simplifies data structures and queries by adding, inlining, or flattening fields or nodes within the schema. |
| [@cache](cache.md)        | Enables caching for the query, field or type applied to.                                                     |
| [@const](const.md)        | Allows embedding of a constant response within the schema.                                                   |
| [@graphQL](graphql.md)    | Resolves a field or node by a GraphQL API.                                                                   |
| [@grpc](grpc.md)          | Resolves a field or node by a gRPC API.                                                                      |
| [@http](http.md)          | Resolves a field or node by a REST API.                                                                      |
| [@modify](modify.md)      | Enables changes to attributes of fields or nodes in the schema.                                              |
| [@omit](omit.md)          | Excludes fields or nodes from the generated schema, making them inaccessible through the GraphQL API.        |
| [@server](server.md)      | Provides server configurations for behavior tuning and tailcall optimization in specific use-cases.          |
| [@upstream](upstream.md)  | Controls aspects of the upstream server connection, including timeouts and keep-alive settings.              |
