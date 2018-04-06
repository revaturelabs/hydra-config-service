# Hydra Config Service

The Hydra Config Service provides configuration files for all of the microservices in the Hydra API.  It uses @EnableConfigServer to indicate that it's a Config Server, and points to the GitLab repository that contains its configuration files in the application.yml file.

## Getting Started

### Prerequisites

Java JDK 1.8
Spring Tool Suite (STS)

### Installing

Either:
- Download the ZIP for the repo and unzip it
- Clone the repo
Import the existing Maven project in STS
Run it as a Spring Boot App

## Running the tests

There are none :)

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management