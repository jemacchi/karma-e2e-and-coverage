karma-e2e-and-coverage
======================

Full sample of a configuration for karma e2e &amp; tdd-like tests, with Junit report and Coverage report included (ready for Continuous Integration)

This sample project it's based on 

 - [karma-e2e-dsl] (https://github.com/winsonwq/karma-e2e-dsl)
 - [coverage-mocha-istanbul-karma] (https://github.com/ariya/coverage-mocha-istanbul-karma)

While first project shows how to use Mocha+e2e tests on Karma, the second one shows an example of Coverage output using Mocha tests (with Chai).
Our example integrates some Mocha TDD tests (no Chai) & e2e tests, with Coverage and JUnit output (for both testing approachs).

## Installation & Run

Simply execute following commands:
 
 - npm install
 - npm install -g grunt-cli (optional, if you dont have grunt-cli installed globally)
 - npm test
 
## Version

Following [Semantic Versioning Specs] (http://semver.org/)

Current Version > 1.0.0

## Author

[Jose Macchi](https://github.com/jemacchi)

Special thanks to 

- [Wang Qiu] (https://github.com/winsonwq)
- [Ariya Hidayat] (https://github.com/ariya) 

since they allowed me -sharing their examples- to reduce time & effort developing this sample project.