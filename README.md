# Spring Batch (spring-batch)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A lightweight, comprehensive batch framework designed to enable the development of robust batch applications vital for the daily operations of enterprise systems. Spring Batch provides reusable functions for processing large volumes of records including logging/tracing, transaction management, job processing statistics, job restart, skip, and resource management. It supports reading and writing from flat files, XML, JSON, databases (JDBC, JPA, Hibernate), message queues, and more.

**APIs.json:** [https://spring.io/projects/spring-batch](https://spring.io/projects/spring-batch)

## Tags

- Batch Processing
- Data Processing
- Enterprise
- ETL
- Java
- Job Scheduling
- Spring Framework

## Timestamps

- **Created:** Sun Jan 14 2024 19:00:00 GMT-0500 (Eastern Standard Time)
- **Modified:** 2026-05-19

## APIs

### Spring Batch Core API

Core framework API for batch processing including job configuration, execution, step management, job repository, and monitoring. Includes support for chunk-oriented processing with configurable readers, processors, and writers.

- **Human URL:** [https://spring.io/projects/spring-batch](https://spring.io/projects/spring-batch)
- **Base URL:** `https://github.com/spring-projects/spring-batch`

#### Tags

- Batch Jobs
- Chunk Processing
- Job Repository
- Step Execution

#### Properties

- [Documentation](https://docs.spring.io/spring-batch/docs/current/reference/html/)
- [A P I  Documentation](https://docs.spring.io/spring-batch/docs/current/api/)
- [GitHub Repository](https://github.com/spring-projects/spring-batch)
- [Getting  Started  Guide](https://spring.io/guides/gs/batch-processing/)
- [Reference  Guide](https://docs.spring.io/spring-batch/docs/current/reference/html/index-single.html)
- [Samples](https://github.com/spring-projects/spring-batch/tree/main/spring-batch-samples)
- [OpenAPI](openapi/spring-batch-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-batch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-batch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/spring-batch-rules.yml)

### Spring Batch Actuator API

Spring Boot Actuator-based REST endpoints for monitoring Spring Batch applications. Provides health indicators, Micrometer metrics, and job execution visibility.

- **Human URL:** [https://docs.spring.io/spring-batch/docs/current/reference/html/monitoring-and-metrics.html](https://docs.spring.io/spring-batch/docs/current/reference/html/monitoring-and-metrics.html)
- **Base URL:** `http://localhost:8080/actuator`

#### Tags

- Actuator
- Health
- Metrics
- Monitoring

#### Properties

- [Documentation](https://docs.spring.io/spring-batch/docs/current/reference/html/monitoring-and-metrics.html)
- [Postman Collection](collections/spring-batch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-batch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Batch Infrastructure API

Infrastructure components providing ItemReader, ItemWriter, and ItemProcessor implementations for various data sources and destinations.

- **Human URL:** [https://docs.spring.io/spring-batch/docs/current/reference/html/readersAndWriters.html](https://docs.spring.io/spring-batch/docs/current/reference/html/readersAndWriters.html)
- **Base URL:** `https://github.com/spring-projects/spring-batch`

#### Tags

- Item Readers
- Item Writers
- JDBC
- JPA

#### Properties

- [Documentation](https://docs.spring.io/spring-batch/docs/current/reference/html/readersAndWriters.html)
- [A P I  Documentation](https://docs.spring.io/spring-batch/docs/current/api/org/springframework/batch/item/package-summary.html)
- [Postman Collection](collections/spring-batch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-batch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Blog](https://spring.io/blog/category/spring-batch)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-batch)
- [Chat](https://gitter.im/spring-projects/spring-batch)
- [Issues](https://github.com/spring-projects/spring-batch/issues)
- [Roadmap](https://github.com/spring-projects/spring-batch/milestones)
- [License](https://github.com/spring-projects/spring-batch/blob/main/LICENSE)
- [Contributing  Guidelines](https://github.com/spring-projects/spring-batch/blob/main/CONTRIBUTING.md)
- [Maven  Central](https://search.maven.org/search?q=g:org.springframework.batch)
- [Release Notes](https://github.com/spring-projects/spring-batch/releases)
- [Security  Policy](https://github.com/spring-projects/spring-batch/security/policy)

## Maintainers

**Email:** spring-batch@pivotal.io
**URL:** https://spring.io/team
