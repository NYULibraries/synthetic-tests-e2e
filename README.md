# Synthetic Tests E2E
Runs a series of E2E (end-to-end) tests against NYU Libraries Web Services applications and vendor applications.

## Adding tests
Create a .js file with the application's name inside of /cypress/integration. Then, write [cypress](https://docs.cypress.io/) tests.

## Running the tests
Run the containerized cypress tests.

```
docker compose run e2e
```
