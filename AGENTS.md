# Repository Engineering Instructions

## Java standards

- Use Java 17 and the package root `io.github.gamaeldinwol.javaengineering`.
- Write idiomatic Java without preview features.
- Do not introduce Lombok.
- Keep dependencies minimal and add them only when their value is clear.
- Prefer standard-library solutions when they are reasonable.
- Favor clarity over cleverness.

## Architecture principles

- Design cohesive classes with descriptive names and deliberate encapsulation.
- Prefer immutability where it improves correctness and readability.
- Avoid premature abstractions and unnecessary design patterns.
- Keep methods focused on a clear responsibility.
- Handle invalid inputs explicitly and deliberately.

## Testing

- Use JUnit 5.
- Test meaningful behavior and important edge cases.
- Keep tests readable, deterministic, and independent.
- Never delete, disable, or weaken a valid test merely to make a build pass.

## Learning guardrail

This repository is also used to refresh Java knowledge. Do not automatically solve Java learning exercises.

When reviewing a learning implementation written by the repository owner:

1. Review the submitted implementation first.
2. Explain the important issues.
3. Give hints before replacing the implementation.
4. Prefer teaching and code review over completing the exercise.
5. Provide a complete solution only when explicitly requested.

Do not reproduce proprietary course material, instructor solutions, or tutorial exercise solutions.

## Repository safety

- Never commit without explicit instruction.
- Never push without explicit instruction.
- Never expose secrets or credentials.
- Never commit generated build output.
- Do not add application code merely to make the repository appear populated.
- Inspect the Git diff before declaring work complete.
- Report build and test failures honestly instead of hiding them.
- Preserve valid configuration unless a demonstrated problem justifies changing it.

## Completion requirements

For implementation tasks:

1. Compile the project.
2. Run the tests.
3. Run Maven verification.
4. Inspect build warnings.
5. Inspect the Git diff.
6. Report unresolved problems.

Use the Maven Wrapper as the authoritative build entry point.

On Windows:

```powershell
.\mvnw.cmd clean verify
```

On Linux and macOS:

```bash
./mvnw clean verify
```
