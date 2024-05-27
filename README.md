# DevOps Capstone

![Build Status](https://github.com/krishnaprajvin-official/devops-capstone-project/actions/workflows/ci-build.yml/badge.svg)](https://github.com/krishnaprajvin-official/devops-capstone-project/actions/workflows/ci-build.yml)

Project Completion Details:-
The capstone project began with an Agile plan to create a RESTful microservice. A GitHub repository and Zenhub kanban board were established, including a user story template. A product backlog was built, followed by a sprint plan. 

Sprint one started with configuring the project environment and developing the Customer Account microservice using test-driven development (TDD). Each story moved through the kanban from “backlog” to “Closed.”
Test cases were created for read, update, delete, and list functions for a RESTful Flask service, with enough code for tests to pass. Nosetests ensured all unit tests passed, and the coverage tool achieved at least 95% coverage.
A GitHub Actions workflow was configured to trigger on repository events like pull requests or pushes to the main branch. 

Sprint 2 included creating a workflow to build and test every push/pull request. Flake8 was used to lint the code and add quality checks to the CI pipeline, and nosetests were set up for code coverage.

Secure code practices were added by implementing Flask-Talisman for security headers and Flask-CORS for Cross-Origin Resource Sharing (CORS) policies. A test case was written for the security feature, and the failing test case passed once the code was added. 

Sprint 3 involved two user stories: creating a Docker image of the microservice and manually deploying it to an OpenShift/Kubernetes cluster. A Dockerfile was created, used to build an image called “accounts,” and pushed to the IBM Cloud Container Registry. A PostgreSQL service was created in OpenShift as the database for the application, and manifest YAML files were created for deploying the Docker image. 

Deployment to Kubernetes was automated using a Tekton pipeline, ensuring automated deployment of the accounts service to Kubernetes. A CD pipeline was created for cloning, linting, unit testing, building, and deploying the service to an OpenShift/Kubernetes cluster.The capstone project began with an Agile plan to create a RESTful microservice. A GitHub repository and Zenhub kanban board were established, including a user story template. A product backlog was built, followed by a sprint plan. Sprint one started with configuring the project environment and developing the Customer Account microservice using test-driven development (TDD). Each story moved through the kanban from “backlog” to “Closed.” Test cases were created for read, update, delete, and list functions for a RESTful Flask service, with enough code for tests to pass. Nosetests ensured all unit tests passed, and the coverage tool achieved at least 95% coverage. A GitHub Actions workflow was configured to trigger on repository events like pull requests or pushes to the main branch. Sprint 2 included creating a workflow to build and test every push/pull request. Flake8 was used to lint the code and add quality checks to the CI pipeline, and nosetests were set up for code coverage. Secure code practices were added by implementing Flask-Talisman for security headers and Flask-CORS for Cross-Origin Resource Sharing (CORS) policies. A test case was written for the security feature, and the failing test case passed once the code was added. Sprint 3 involved two user stories: creating a Docker image of the microservice and manually deploying it to an OpenShift/Kubernetes cluster. A Dockerfile was created, used to build an image called “accounts,” and pushed to the IBM Cloud Container Registry. A PostgreSQL service was created in OpenShift as the database for the application, and manifest YAML files were created for deploying the Docker image. Deployment to Kubernetes was automated using a Tekton pipeline, ensuring automated deployment of the accounts service to Kubernetes. A CD pipeline was created for cloning, linting, unit testing, building, and deploying the service to an OpenShift/Kubernetes cluster.
