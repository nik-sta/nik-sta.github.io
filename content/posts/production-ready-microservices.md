---
title: Production-ready microservice with Spring Boot written in Java
description: description
tags: ["java", "spring boot", "kubernetes", "microservice", "devsecops"]
series: ["Production-ready microservices"]
date: 2021-02-26T00:30:00+01:00
keywords: java, spring boot, kubernetes, microservice, devsecops
featuredImage: image-1.jpeg
draft: true
---

Scope: Java, spring boot, micro-service

**In this blog article, I want to explain how to get easily started with a microservice written in Java with Spring Boot. Aiming to show what is needed to have this service ready for production on a Kubernetes environment. Covering the DevSecOps best practices.**

This is the first post of my "fully automated production-ready microservices" series.

This article includes my experience of building stable (code quality, maintainability) software intended to provide a solid start point for your next greenfield project.

Feel free to jump directly into my quick-starter-template on GitHub to start right away with your new production-ready microservice: [springboot-java-microservice-quickstarter](https://github.com/botscripter/springboot-java-microservice-quickstarter)

* Versioning, snapshots, nightly-builds, rc ...
* data migration f.e. liquibase
* i18n support
* understand gradle
* OpenApi Docs
* javadoc, comments in code
* error handling, global handlers
* Logging, Tracing, APM
* JRE, JDK, Dockerfile
* Decentralized deployment
* Security (OAuth2)
* Remote Debugging
* HTTPS Only
* Rate Limiting
* Enable JVM Runtime Metrics
* vulnerability detection
* actuator
* performance visualization tweaks
* publishing
* license checking
* linting
* mocks & stages
* spring boot docker layering
* messaging
* gRPC (inter-service communication)
* multi-threading (nonblocking, spring reactor)
* databses
* use of spring and not only partly ... extend spring! it's not magic.
* configuratiuon
* credentials, secrets, encryption
* signing artefacts (docker, commits, releases)

organizational:

* define company default dependencies