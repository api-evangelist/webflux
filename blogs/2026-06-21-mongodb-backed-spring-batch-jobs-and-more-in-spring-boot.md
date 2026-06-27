---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 introduces a dedicated starter for MongoDB-backed batch job repositories, decoupling JobRepository from JDBC so teams can store the Spring Batch JobRepository in MongoDB. The post demonstrates an ETL example that reads from CSV, tracks jobs in MongoDB, and writes to PostgreSQL, with automatic schema initialization and GraalVM native image support.
