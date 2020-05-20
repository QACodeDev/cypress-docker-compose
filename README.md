# cypress-docker-compose 
[![Build status](https://dev.azure.com/QADevCode/DevOpsPOC/_apis/build/status/Cypress-Docker-Pipeline)](https://dev.azure.com/QADevCode/DevOpsPOC/_build/latest?definitionId=6)

See [docker-compose.yml](docker-compose.yml) file

## Use

```shell
# run tests using built-in Electron browser
docker-compose run e2e-electron

# run tests using Chrome browser pre-installed in cypress/included image
docker-compose run e2e-chrome

# run tests using Firefox browser (also pre-installed)
docker-compose run e2e-firefox
```

The tests work against [https://example.cypress.io/](https://example.cypress.io/) and use specs from [cypress-example-kitchensink](https://github.com/cypress-io/cypress-example-kitchensink)

[included]: https://github.com/cypress-io/cypress-docker-images/tree/master/included#cypressincluded

## Examples

Find more Docker + Cypress examples in [Cypress Docker docs](https://on.cypress.io/docker)
