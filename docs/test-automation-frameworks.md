## Code Quality Integrations
Template repo contains basic unit tests framework with code coverage.
To run tests execute next command:
- npm test
Once test run is completed you will see next table:
  ----------|---------|----------|---------|---------|-------------------
  File      | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s
  ----------|---------|----------|---------|---------|-------------------
  All files |     100 |      100 |     100 |     100 |                   
  App.js    |     100 |      100 |     100 |     100 |                   
  ----------|---------|----------|---------|---------|-------------------

To check HTML report you need to open coverage/lcov-report/index.html in browser. Report will show local code coverage.

To configure code coverage for Sonar Cloud you can use sonar-project.properties or 'coveragePathIgnorePatterns' section 
of package.json for local.
Sonar Cloud Quality Gate rule demands at least 85% code coverage.
