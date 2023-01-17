# Playwright CI/CD Demo

## Run Tests in CI/CD:
Tests are setup to run automatically in CI/CD via GitHub actions upon pushing to the repository. To view the CI/CD test results, navigate to the Actions tab.

## Run Tests Locally:

Install NPM Dependencies:
```
npm install
```

Run the Test Suite:
```
npx playwright test
```

The tests run in headless mode by default. If you want to run in headed mode, add the `--headed` flag like so:
```
npx playwright test --headed
```

Show HTML Report:
```
npx playwright show-report
```
