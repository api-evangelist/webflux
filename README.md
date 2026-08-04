# Spring WebFlux

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
