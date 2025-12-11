# Playwright Test Commands

### Test playwright (Headed)

`npx playwright test --headed`

### Display Playwright Result

`npx playwright show-report`

### Test specific browser

`npx playwright test --project chromium`
`npx playwright test --project chro*` _(using wildcard)_

### Testing a specific file

`npx playwright test test/example.spec.ts` _(with fiile)_
`npx playwright test test/example.spec.ts:10` _(with fiile and line number)_
`npx playwright test --grep @getstarted` _(with tag)_
