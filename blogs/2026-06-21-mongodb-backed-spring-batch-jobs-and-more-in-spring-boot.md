---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 introduces MongoDB support for Spring Batch's JobRepository, eliminating the need to maintain separate SQL databases alongside document stores. The post walks through an ETL example that reads from a CSV file, writes to PostgreSQL, and persists batch metadata in MongoDB using the new spring-boot-starter-batch-data-mongodb autoconfiguration starter, with GraalVM native image support and lazy DataSource connection retrieval.
