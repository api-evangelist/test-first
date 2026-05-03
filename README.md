# Test First (test-first)
A software development approach where tests are written before the implementation code, ensuring code quality and driving design decisions through test requirements. Test-first development is the foundational principle behind test-driven development (TDD) and behavior-driven development (BDD), where the specification of expected behavior is captured in executable tests before any production code is written.

**URL:** [Visit APIs.json URL](https://en.wikipedia.org/wiki/Test-driven_development)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Behavior-Driven Development, Best Practices, Methodology, Software Design, Software Development, Testing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### Cucumber API
REST API and tooling for Cucumber BDD framework supporting test-first development with Gherkin feature files, scenario definitions, and step implementations.

**Human URL:** [https://cucumber.io](https://cucumber.io)

#### Tags:

 - Behavior-Driven Development, Gherkin, Test Automation, Testing

#### Properties

- [Documentation](https://cucumber.io/docs/cucumber/)
- [GitHubRepository](https://github.com/cucumber/cucumber-js)

### Pact Broker API
REST API for Pact Broker contract testing service, enabling consumer-driven contract testing where consumer tests define the API contract before providers implement it.

**Human URL:** [https://docs.pact.io](https://docs.pact.io)

#### Tags:

 - Consumer-Driven Contracts, Contract Testing, Microservices, Test-First

#### Properties

- [Documentation](https://docs.pact.io)
- [GitHubRepository](https://github.com/pact-foundation/pact_broker)
- [OpenAPI](https://raw.githubusercontent.com/pact-foundation/pact_broker/master/lib/pact_broker/api/pact_broker.json)

### Stoplight API
API design-first platform enabling teams to write API specifications before implementation, supporting test-first development with mock servers, contract testing, and API style guides.

**Human URL:** [https://stoplight.io](https://stoplight.io)

#### Tags:

 - API Design, Contract Testing, Mock Servers, Test-First

#### Properties

- [Documentation](https://meta.stoplight.io/docs/platform)
- [APIReference](https://meta.stoplight.io/docs/stoplight-api)

### Microcks API
Open-source cloud-native tool for API mocking and contract testing, supporting test-first development by generating mocks from OpenAPI, Postman, and gRPC specifications.

**Human URL:** [https://microcks.io](https://microcks.io)

#### Tags:

 - API Mocking, Contract Testing, Open Source, Test-First

#### Properties

- [Documentation](https://microcks.io/documentation/)
- [GitHubRepository](https://github.com/microcks/microcks)

### Dredd API
Command-line HTTP API testing framework that validates API implementations against API Blueprint or OpenAPI descriptions, enabling test-first API development.

**Human URL:** [https://dredd.org](https://dredd.org)

#### Tags:

 - API Testing, Contract Testing, OpenAPI, Test-First

#### Properties

- [Documentation](https://dredd.readthedocs.io)
- [GitHubRepository](https://github.com/apiaryio/dredd)

## Common Properties

- [Documentation](https://en.wikipedia.org/wiki/Test-driven_development)
- [Documentation](https://www.agilealliance.org/glossary/tdd/)

## Features

| Name | Description |
|------|-------------|
| Specification Before Implementation | Write executable test specifications that define expected behavior before writing any production code. |
| API Contract Definition | Define the API contract through tests before the implementation exists, ensuring design clarity. |
| Mock-First Development | Use mock servers generated from specifications to enable parallel frontend and backend development. |
| Living Documentation | Tests serve as up-to-date documentation of how the system is expected to behave. |
| Fail Fast Feedback | Discover design issues early by specifying tests before implementation reveals constraints. |
| Consumer-Driven Contracts | Let API consumers define their expectations as tests that the API provider must satisfy. |

## Use Cases

| Name | Description |
|------|-------------|
| API-First Design | Write OpenAPI specifications and generate tests from them before building the implementation. |
| Consumer-Driven Contract Testing | API consumers publish test expectations that API providers must verify in their CI pipelines. |
| Behavior-Driven Development | Use Gherkin feature files to define expected system behavior before writing implementation. |
| Parallel Development | Enable frontend and backend teams to develop in parallel using mock servers from specifications. |
| Specification Compliance | Validate that API implementations comply with their published specifications using test-first assertions. |

## Integrations

| Name | Description |
|------|-------------|
| OpenAPI | Generate test-first stubs and mocks directly from OpenAPI specifications. |
| Cucumber | Use Gherkin scenarios as the test-first specification for behavior-driven development. |
| Pact | Apply consumer-driven contract testing where consumer tests define provider expectations. |
| Prism | Use Stoplight Prism to mock APIs from OpenAPI specs enabling test-first development. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Specification Schema](json-schema/test-first-specification-schema.json)
- [Contract Schema](json-schema/test-first-contract-schema.json)
- [Mock Server Schema](json-schema/test-first-mock-schema.json)

### JSON Structure

- [Specification Structure](json-structure/test-first-specification-structure.json)
- [Contract Structure](json-structure/test-first-contract-structure.json)
- [Mock Server Structure](json-structure/test-first-mock-structure.json)

### JSON-LD

- [Test First Context](json-ld/test-first-context.jsonld)

### Examples

- [Specification Example](examples/test-first-specification-example.json)
- [Contract Example](examples/test-first-contract-example.json)
- [Mock Server Example](examples/test-first-mock-example.json)

## Vocabulary

- [Test First Vocabulary](vocabulary/test-first-vocabulary.yml) — Unified taxonomy mapping 3 resources, 9 actions, and 3 personas across test-first development domains.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
