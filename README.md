# CI/CD Pipeline for Mule Application Deployment
This repository contains the GitHub Actions workflow used to build, test, and deploy MuleSoft applications to CloudHub 2.0. The pipeline automates build validation, MUnit execution, artifact versioning, and deployment to the target environment.

### Triggering the Workflow
The pipeline can be triggered manually from the Actions tab using the workflow_dispatch event. Select the environment, Java version, and commit message to start deployment.

### Local MUnit Validation
Before pushing changes, ensure all MUnit tests pass locally: mvn clean test
