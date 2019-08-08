# Example Spring Boot app with Log4j2 using Sentry

Add your DSN to `src/main/resources/sentry.properties`

To run:

> mvn sprint-boot:run


You can optionally specify the DSN via environment variable:

> SENTRY_DSN="https://abc@sentry.io/123" mvn spring-boot:run

Even if `sentry.properties` have a DSN, the environment variable value will override it.