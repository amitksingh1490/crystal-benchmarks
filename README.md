<!-- README.md is generated from README.ecr, do not edit -->

# GraphQL server benchmarks

Graphql server benchmarks in many languages. Pull requests welcome, please read [CONTRIBUTING.md](CONTRIBUTING.md)

All servers implement a simple schema:

```graphql
type Query {
  hello: String!
}
```

The returned string is always `world`.

The API is served over HTTP using a common web server and load tested using [bombardier](https://github.com/codesenberg/bombardier).

### Results

| Name                          | Language      | Server          | Latency avg      | Requests      |
| ----------------------------  | ------------- | --------------- | ---------------- | ------------- |
| [graphql-yoga](https://github.com/dotansimha/graphql-yoga) | Node.js | http | 0.27ms | 500kps |
| [static-rust](https://actix.rs/) | Rust | Actix Web | 0.27ms | 490kps |
| [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) | Ruby | Puma | 0.27ms | 490kps |
| [graphql-jit](https://github.com/zalando-incubator/graphql-jit) | Node.js | http | 0.27ms | 490kps |
| [graphql-go](https://github.com/graphql-go/graphql) | Go | net/http | 0.26ms | 490kps |
| [async-graphql](https://github.com/async-graphql/async-graphql) | Rust | Actix Web | 0.26ms | 490kps |
| [Juniper](https://github.com/graphql-rust/juniper) | Rust | Actix Web | 0.27ms | 490kps |
| [Graphene](https://github.com/graphql-python/graphene) | Python | gunicorn | 0.26ms | 490kps |
| [Absinthe](https://github.com/absinthe-graphql/absinthe) | Elixir | Phoenix | 0.27ms | 490kps |
| [Strawberry](https://github.com/strawberry-graphql/strawberry) | Python | gunicorn | 0.26ms | 490kps |
| [Hono](https://github.com/honojs/graphql-server) | Bun | HonoJS | 0.26ms | 490kps |
| [apollo](https://github.com/apollographql/apollo-server) | Node.js | Express | 0.28ms | 490kps |
| [Sangria](https://github.com/sangria-graphql/sangria) | Scala | Akka HTTP | 0.27ms | 490kps |
| [graphql-crystal](https://github.com/graphql-crystal/graphql) | Crystal | Kemal | 0.27ms | 490kps |
| [Mercurius](https://github.com/mercurius-js/mercurius) | Node.js | Fastify | 0.27ms | 490kps |
| [graphql-js](https://github.com/graphql/graphql-js) | Node.js | http | 0.26ms | 490kps |
| [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) | C# | ASP.NET | 0.27ms | 490kps |
| [nim-graphql](https://github.com/status-im/nim-graphql) | Nim | Chronos | 0.28ms | 480kps |
| [gqlgen](https://github.com/99designs/gqlgen) | Go | net/http | 0.26ms | 480kps |
| [agoo](https://github.com/ohler55/agoo) | Ruby/C | agoo | 0.29ms | 450kps |
