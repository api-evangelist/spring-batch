# Spring Batch

A lightweight, comprehensive batch framework designed to enable the development of robust batch applications vital for the daily operations of enterprise systems. Spring Batch provides reusable functions for processing large volumes of records including logging/tracing, transaction management, job processing statistics, job restart, skip, and resource management.

- **URL:** https://spring.io/projects/spring-batch
- **Type:** Open Source
- **Tags:** Batch Processing, Data Processing, Enterprise, ETL, Java, Job Scheduling, Spring Framework

## APIs

### Spring Batch Core API

Core framework API for batch processing including job configuration, execution, step management, job repository, and monitoring.

- [Documentation](https://docs.spring.io/spring-batch/docs/current/reference/html/)
- [API Documentation](https://docs.spring.io/spring-batch/docs/current/api/)
- [GitHub Repository](https://github.com/spring-projects/spring-batch)
- [Getting Started Guide](https://spring.io/guides/gs/batch-processing/)
- [Reference Guide](https://docs.spring.io/spring-batch/docs/current/reference/html/index-single.html)
- [Samples](https://github.com/spring-projects/spring-batch/tree/main/spring-batch-samples)

### Spring Batch Actuator API

Spring Boot Actuator-based REST endpoints for monitoring Spring Batch applications.

- [Documentation](https://docs.spring.io/spring-batch/docs/current/reference/html/monitoring-and-metrics.html)

### Spring Batch Infrastructure API

ItemReader, ItemWriter, and ItemProcessor implementations for various data sources.

- [Documentation](https://docs.spring.io/spring-batch/docs/current/reference/html/readersAndWriters.html)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spring Batch Actuator API | [openapi/spring-batch-openapi.yml](openapi/spring-batch-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spring Batch Rules | [rules/spring-batch-rules.yml](rules/spring-batch-rules.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Spring Batch Actuator API | [capabilities/shared/spring-batch-actuator.yaml](capabilities/shared/spring-batch-actuator.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|----------|-------------|------|
| Batch Job Monitoring | Monitor Spring Batch job executions, metrics, and health | [capabilities/batch-job-monitoring.yaml](capabilities/batch-job-monitoring.yaml) |

## JSON Schemas

| Schema | File |
|--------|------|
| Job Execution | [json-schema/spring-batch-job-execution-schema.json](json-schema/spring-batch-job-execution-schema.json) |
| Job Parameters | [json-schema/spring-batch-job-parameters-schema.json](json-schema/spring-batch-job-parameters-schema.json) |

## JSON Structures

| Structure | File |
|-----------|------|
| Job Execution Domain Model | [json-structure/spring-batch-job-execution-structure.json](json-structure/spring-batch-job-execution-structure.json) |

## JSON-LD Contexts

| Context | File |
|---------|------|
| Spring Batch | [json-ld/spring-batch-context.jsonld](json-ld/spring-batch-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Application Health | [examples/spring-batch-get-health-example.json](examples/spring-batch-get-health-example.json) |
| List Job Executions | [examples/spring-batch-list-job-executions-example.json](examples/spring-batch-list-job-executions-example.json) |
| Get Metric Value | [examples/spring-batch-get-metric-example.json](examples/spring-batch-get-metric-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spring Batch Domain Terms | [vocabulary/spring-batch-vocabulary.yml](vocabulary/spring-batch-vocabulary.yml) |

## Common Properties

- [Blog](https://spring.io/blog/category/spring-batch)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-batch)
- [Chat](https://gitter.im/spring-projects/spring-batch)
- [Issues](https://github.com/spring-projects/spring-batch/issues)
- [Roadmap](https://github.com/spring-projects/spring-batch/milestones)
- [License](https://github.com/spring-projects/spring-batch/blob/main/LICENSE)
- [Contributing Guidelines](https://github.com/spring-projects/spring-batch/blob/main/CONTRIBUTING.md)
- [Maven Central](https://search.maven.org/search?q=g:org.springframework.batch)
- [Release Notes](https://github.com/spring-projects/spring-batch/releases)
- [Security Policy](https://github.com/spring-projects/spring-batch/security/policy)

## Maintainers

- Spring Team — spring-batch@pivotal.io
