# Spring WebFlux

Spring WebFlux is a fully non-blocking, reactive-stack web framework built into Spring Framework 5.0+. It enables building highly scalable, asynchronous web applications using the Reactive Streams API with Project Reactor. WebFlux supports annotated controllers, functional routing endpoints, WebSocket communication, RSocket protocol, and a powerful reactive HTTP client (WebClient) for consuming APIs.

**Type:** Open Source Framework
**Language:** Java
**License:** Apache 2.0
**GitHub:** [spring-projects/spring-framework](https://github.com/spring-projects/spring-framework)
**Documentation:** [Spring WebFlux Reference](https://docs.spring.io/spring-framework/reference/web/webflux.html)

## APIs

| API | Description |
|-----|-------------|
| [Spring WebFlux Core](https://docs.spring.io/spring-framework/reference/web/webflux.html) | Reactive web framework with annotated controllers and functional endpoints |
| [WebClient](https://docs.spring.io/spring-framework/reference/web/webflux-webclient.html) | Non-blocking reactive HTTP client |
| [Router Functions](https://docs.spring.io/spring-framework/reference/web/webflux-functional.html) | Functional routing and handler programming model |
| [WebSocket](https://docs.spring.io/spring-framework/reference/web/webflux-websocket.html) | Reactive full-duplex WebSocket support |
| [RSocket](https://docs.spring.io/spring-framework/reference/rsocket.html) | Reactive binary protocol integration |
| [Reactor Core](https://projectreactor.io/) | Project Reactor Mono/Flux publisher types |
| [HTTP Service Client](https://docs.spring.io/spring-framework/reference/integration/rest-clients.html#rest-http-interface) | Declarative @HttpExchange client interfaces |
| [Testing / WebTestClient](https://docs.spring.io/spring-framework/reference/testing/webtestclient.html) | WebTestClient for reactive integration testing |

## Artifacts

### AsyncAPI Specifications
- [webflux-websocket-asyncapi.yml](asyncapi/webflux-websocket-asyncapi.yml) — WebSocket communication channels and STOMP messaging

### JSON Schemas
- [webflux-webclient-request-schema.json](json-schema/webflux-webclient-request-schema.json) — WebClient HTTP request configuration
- [webflux-webclient-response-schema.json](json-schema/webflux-webclient-response-schema.json) — WebClient HTTP response
- [webflux-router-function-schema.json](json-schema/webflux-router-function-schema.json) — RouterFunction route configuration

### JSON Structures
- [webflux-webclient-request-structure.json](json-structure/webflux-webclient-request-structure.json) — WebClient request field documentation

### JSON-LD Contexts
- [webflux-context.jsonld](json-ld/webflux-context.jsonld) — Linked data context for WebFlux concepts

### Examples
- [webflux-webclient-get-example.json](examples/webflux-webclient-get-example.json) — WebClient GET request example
- [webflux-webclient-post-example.json](examples/webflux-webclient-post-example.json) — WebClient POST request example

### Vocabulary
- [webflux-vocabulary.yml](vocabulary/webflux-vocabulary.yml) — Spring WebFlux terminology and concepts

## Key Concepts

- **Reactive Programming** — Non-blocking I/O with Reactive Streams backpressure
- **Mono / Flux** — Project Reactor publisher types for 0-1 and 0-N async values
- **WebClient** — Reactive replacement for RestTemplate
- **Functional Endpoints** — RouterFunction + HandlerFunction as alternative to @Controller
- **Server-Sent Events** — Streaming push with Flux<ServerSentEvent>
- **WebSocket** — Full-duplex reactive WebSocket sessions
- **RSocket** — Reactive binary protocol for microservice communication

## Use Cases

- Reactive REST APIs handling high concurrency
- Real-time streaming with Server-Sent Events
- WebSocket-based chat and collaboration apps
- Microservice communication with reactive HTTP clients
- Non-blocking data pipelines with reactive databases (R2DBC)

## Common Properties

- [Blog](https://spring.io/blog/category/engineering)
- [Support](https://spring.io/support)
- [Community](https://spring.io/community)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-webflux)
- [GitHub Organization](https://github.com/spring-projects)
- [Twitter](https://twitter.com/springcentral)
- [YouTube](https://www.youtube.com/user/SpringSourceDev)
- [Maven Central](https://mvnrepository.com/artifact/org.springframework/spring-webflux)
- [Releases](https://github.com/spring-projects/spring-framework/releases)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
