# Java-Standard

[![Build Status](https://travis-ci.org/codecov/java-Standard.svg?branch=master)](https://travis-ci.org/codecov/java-Standard) [![codecov](https://codecov.io/gh/codecov/java-Standard/branch/master/graph/badge.svg)](https://codecov.io/gh/codecov/java-Standard)

### Last Updated: 01/25/20 17:59:39

## What is this?

This is a **Java/Gradle** application, with basic unit tests, for which coverage is uploaded to Codecov on a daily basis. It can also serve as an example for how to integrate Codecov into your Java project. If the build is passing for this project, then Codecov's Java report processing is functional and correct on codecov.io.

## Configuration

This project is written in `Java` and is built using `Gradle`. Unit test are written using the `Junit` framework and coverage reports are generated using `Jacoco` plugin.

## Usage

### The Docker Way

Run unit tests inside a Docker container
```bash
docker-compose up
```

### The Local Way

Build the project
```
./gradlew build
```

Run tests
```
./gradlew test
```

## Reporting Issues

If you've discovered an issue with this repository or with Java processing in general, it is recommended to email support@codecov.io rather than post an issue here. This repository will not be checked regularly for open issues.

## Contributing

Contributions are welcome! If you'd like to contribute to this repository, feel free to open a pull request or flag an issue. If you would like to contribute a new lanaguage standard, [you can get more information here](https://github.com/codecov/standards-scripts/blob/master/README.md#contributing). 
