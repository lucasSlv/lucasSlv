```ts
import Developer from "lucasSlv";

class AboutMe extends Developer {
  name = "Lucas Silva";
  role = "Backend Software Engineer";
  location = "Sergipe, Brazil";

  summary = `
  Backend-focused engineer with strong experience in designing scalable,
  testable and event-driven systems. I work daily with distributed
  architectures, clean code, and domain-oriented solutions, always
  prioritizing maintainability, observability and business clarity.
  `;

  interests = [
    "Software Architecture",
    "Domain-Driven Design (DDD)",
    "Event-Driven Architecture",
    "Distributed Systems",
    "Test-Driven Development (TDD)",
    "Clean Code & SOLID",
    "Observability & Monitoring",
    "Technical Leadership & Mentorship"
  ];
}

class Skills extends Developer {
  languages = [
    "TypeScript",
    "JavaScript"
  ];

  backend = [
    "Node.js",
    "Express",
    "REST APIs",
    "Message-driven services"
  ];

  messaging = [
    "Kafka",
    "Async consumers & producers",
    "Event-based workflows"
  ];

  databases = [
    "MongoDB",
    "Mongoose",
    "Transactions & Indexing strategies"
  ];

  testing = [
    "Jest",
    "Unit Tests",
    "Integration Tests",
    "Testcontainers"
  ];

  architecture = [
    "Clean Architecture",
    "DDD",
    "Separation of Concerns",
    "Service & Repository patterns"
  ];

  cloudAndInfra = [
    "AWS",
    "Docker",
    "CI/CD pipelines"
  ];

  frontend = [
    "React",
    "Styled Components",
    "Vite"
  ];

  observability = [
    "Logs",
    "Metrics",
    "Grafana (monitoring & dashboards)"
  ];
}
```
