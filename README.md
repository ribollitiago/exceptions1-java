# exceptions1-java

A focused Java project demonstrating custom exception handling — domain-level validation using user-defined exception classes, encapsulated business rules, and structured try/catch patterns.

---

## Highlights

- Custom `DomainException` extending `Exception` for semantic error signaling
- `Reservation` entity encapsulating date-range validation logic
- Clean `try/catch/finally` flow in the `Program` entry point
- Demonstrates checked vs. unchecked exception best practices

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Java 17+ |
| IDE | Eclipse / IntelliJ |
| Architecture | Domain-driven exception design |

---

## Project Structure

```
src/
├── model/
│   ├── Reservation.java      # Domain entity with validation
│   └── exceptions/
│       └── DomainException.java  # Custom checked exception
└── application/
    └── Program.java          # Entry point & exception handling demo
```

---

## Getting Started

### Prerequisites

- Java 17 or higher

### Run via CLI

```bash
javac -d bin src/**/*.java
java -cp bin application.Program
```

---

## Author

**Tiago Ribolli Blasquez**  
[linkedin.com/in/tiagoribolli](https://linkedin.com/in/tiago-ribolli-blasquez-060810244) · [github.com/ribollitiago](https://github.com/ribollitiago)
