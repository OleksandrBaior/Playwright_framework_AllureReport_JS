## Playwright-framework
Web-Site  - https://www.redmine.org/

## Setup
1. Install [node.js](https://nodejs.org/en/) and install all the dependencies for doing the full operation of the node.js.
2. Clone git repository `git clone https://github.com/OleksandrBaior/Playwright-framework.git`
3. Use installed node modules `npm install`
4. Install playwright with all dependencies `npx playwright install --with-deps`.

## Running the Tests 
Results of the tests and test logs will be shown in the terminal:
```
npx playwright test
```

Run your tests with UI Mode:
```
npx playwright test --ui
```

To open last HTML report run:
```
npx playwright show-report
```

Running a single test file:
```
npx playwright test example-page.spec.ts
```
