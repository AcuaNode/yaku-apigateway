# API Gateway

Spring Cloud Gateway (WebFlux) service for the Yaku microservices platform.

## Prerequisites

- Java 17 (use [mise](https://mise.jdx.dev) or your preferred toolchain manager)
- Maven (via the included wrapper — no manual install needed)

## Quick start

```bash
./mvnw spring-boot:run
```

The gateway starts on port 8080 by default.

## Build

```bash
./mvnw clean package
```

Produces `target/gateway-0.0.1-SNAPSHOT.jar`.

## Test

```bash
./mvnw test
```

## OCI image

```bash
./mvnw spring-boot:build-image
```

Uses Cloud Native Buildpacks (no Dockerfile required).

## Tech stack

| Component              | Version     |
|------------------------|-------------|
| Java                   | 17          |
| Spring Boot            | 3.5.14      |
| Spring Cloud Gateway   | 2025.0.2    |
| Spring Cloud           | 2025.0.2    |
| Maven                  | 3.9.16      |
| Lombok                 | latest      |
| JUnit                  | 5           |
| Reactor Test           | latest      |
