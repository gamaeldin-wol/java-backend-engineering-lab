# Java Backend Engineering Lab

## Overview

`java-backend-engineering-lab` documents a deliberate refresh and continued development of professional Java backend engineering skills through original implementations and production-oriented engineering practices. It is both an honest learning laboratory and a public record of engineering progress.

## Engineering Objectives

- Strengthen Java language and object-oriented design fundamentals.
- Practice clear APIs, deliberate error handling, and maintainable code structure.
- Build meaningful automated tests alongside implemented behavior.
- Apply repeatable build, dependency-management, CI, and documentation practices.
- Develop original projects without reproducing proprietary course solutions.

## Current Technology Stack

- Oracle OpenJDK 17 for local development
- Apache Maven 3.9.12 through the Maven Wrapper
- JUnit 5 for testing
- GitHub Actions with Eclipse Temurin 17 for continuous integration

## Repository Structure

```text
.
|-- .github/               # CI and dependency-update configuration
|-- .mvn/                  # Maven Wrapper configuration
|-- docs/                  # Engineering learning log
|-- src/main/java/         # Future production Java source
|-- src/main/resources/    # Future application resources
|-- src/test/java/         # Tests accompanying meaningful behavior
|-- AGENTS.md              # Repository-specific Codex instructions
|-- README.md
`-- pom.xml                # Maven project configuration
```

Future Java source will use the package root `io.github.gamaeldinwol.javaengineering`. Empty package hierarchies and placeholder application classes are intentionally omitted.

## Engineering Practices

- Java 17 without preview features
- Standard Maven project layout and wrapper-based builds
- Minimal, deliberate dependency selection
- JUnit 5 tests focused on meaningful behavior and edge cases
- Cross-platform text and line-ending configuration
- Automated verification on pushes to `main` and pull requests
- Concise documentation of engineering decisions and learning outcomes

## Build

Windows PowerShell:

```powershell
.\mvnw.cmd clean verify
```

Linux or macOS:

```bash
./mvnw clean verify
```

## Test

Run the test phase with the Maven Wrapper:

```powershell
.\mvnw.cmd test
```

There are no application tests yet because no application behavior has been introduced. The first tests will accompany the first meaningful Java implementation.

## Roadmap

- Java language fundamentals and object-oriented design
- Interfaces, abstraction, generics, and collections
- Exception handling, lambdas, streams, and file I/O
- Concurrency and automated testing
- Clean-code, build-automation, and dependency-management practices
- Original Java backend projects
- Spring Boot in a later, explicitly separated phase

Roadmap items describe intended future work and are not claims about the current implementation.

## Current Progress

The repository currently contains its Java 17 Maven baseline, JUnit 5 test infrastructure, repository hygiene configuration, documentation structure, CI workflow, and dependency-update configuration. Application behavior has not yet been added.

Progress notes and engineering takeaways are recorded in [the learning log](docs/learning-log.md).

## Learning Resources

Work in this repository may be informed by official Java, Maven, JUnit, and related technical documentation, along with educational resources. Implementations are written independently; specific external material will be attributed when it directly influences repository content.

## Attribution and Licensing

Original repository content is authored for this engineering lab unless a file states otherwise. Third-party tools and dependencies retain their own licenses. No license has currently been granted for this repository; a license may be selected deliberately in the future.
