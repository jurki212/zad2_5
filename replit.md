# Imported Java/Maven project

## Run on Replit

This project is a Java console application. Its entry point is
`src/main/java/Main.java`, which prints a greeting and then exits.

- Run the configured `Start application` workflow to execute it.
- The Run button starts that workflow. Output appears in the Console, not a web preview.
- Expected output: `Hello world JPWP2!`. The program then exits normally.
- Build and test manually with `mvn test`.
- Run the entry point directly with `javac -d . src/main/java/Main.java && java -cp . Main`.

The Java toolchain is provided by the Replit project configuration.
No secrets or external services are required. Maven resolves the dependencies
declared in `pom.xml`; currently there are no active tests.
