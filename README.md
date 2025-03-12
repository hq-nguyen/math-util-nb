# Software Development Practices in Java

## Test-Driven Development (TDD)
TDD is a development approach where tests are written **before** writing the actual code. The cycle follows:  
1. **Write a failing test**  
2. **Write the minimal code to pass the test**  
3. **Refactor the code**  
Popular frameworks: **JUnit, TestNG, Mockito**.

## Data-Driven Testing (DDT)
DDT involves running tests with multiple sets of input data to validate functionality across different scenarios.  
- Data sources: CSV, JSON  
- Common tools: **JUnit with @ParameterizedTest**  

## Continuous Integration & Continuous Deployment (CI/CD)
CI/CD automates building, testing, and deploying applications, ensuring smooth and fast delivery.  
- **CI (Continuous Integration)**: Code changes are automatically tested and merged frequently.  
- **CD (Continuous Deployment/Delivery)**: Automates deployment to staging/production.  
- Popular tools: **GitHub Actions, Docker**.
