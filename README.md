# Credit Card Fraud Detector

A Spring Boot-based application for detecting suspicious credit card transactions in real-time.

## Features
- Transaction processing API
- Fraud detection rules engine
- Configurable fraud rules
- Feature toggles for advanced fraud detection
- Optional admin UI for configuration

## Tech Stack
- Backend: Spring Boot
- Database: MongoDB/H2
- DevOps: Docker, GitHub Actions, Argo CD
- Testing: k6, Selenium (optional)

## Project Structure
```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── creditcard/
│   │           └── frauddetector/
│   │               ├── application/
│   │               ├── config/
│   │               ├── controller/
│   │               ├── model/
│   │               ├── repository/
│   │               ├── service/
│   │               └── utils/
│   └── resources/
│       ├── application.properties
│       ├── application-test.properties
│       └── data/
└── test/
    └── java/
        └── com/
            └── creditcard/
                └── frauddetector/
```

## Getting Started
1. Clone the repository
2. Install dependencies
3. Configure database
4. Run the application

## Development
- Feature branches: `feature/*`
- Development branch: `develop`
- Main branch: `main`

## Testing
- Unit tests: JUnit 5
- Integration tests: TestContainers
- Performance tests: k6
- UI tests: Selenium (optional)

## Deployment
- CI/CD: GitHub Actions
- Kubernetes: Argo CD
- Container: Docker
