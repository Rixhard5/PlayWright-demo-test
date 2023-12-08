Commands:

---

--'Init playwright on project.'
- `npm init playwright@latest`

--'Runs the end-to-end tests.'
- `npx playwright test`

--'Shows the report of the tests.'
- `npx playwright show-report`

--'Runs the tests only on Desktop Chrome.'
- `npx playwright test --project=chromium`

--'Parameter headed.'
- `npx playwright test --project=chromium --headed`

--'Runs the test with parameter "has title".'
- `npx playwright test -g "has title"  --project=chromium`

--'Runs a specific file.'
- `npx playwright test example.spec.ts --project=chromium`

--'Starts the interactive UI mode.'
- `npx playwright test --ui`

--'Turns on tracing.'
- `npx playwright test --project=chromium --trace on`

-'Runs the tests in debug mode.'
- `npx playwright test --project=chromium --debug`
