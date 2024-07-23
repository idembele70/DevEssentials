Playwright usefull ressources
=====================

### Running tests with specific Tags name
```bash
npx playwright test --grep @<YOUR_TAG_NAME>
npx playwright test -g @<YOUR_TAG_NAME>
```

### Running test with multiple Tags name
```bash
npx playwright test --grep "@<YOUR_FIRST_TAG_NAME>|@<YOUR_SECOND_TAG_NAME>|@<YOUR_THIRD_TAG_NAME>"
npx playwright test -g "@<YOUR_FIRST_TAG_NAME>|@<YOUR_SECOND_TAG_NAME>|@<YOUR_THIRD_TAG_NAME>"
```

## Learning and developping !
1. [Learning end-to-end testing](https://ray.run/)
2. [API Testing example](https://ray.run/blog/api-testing-using-playwright)
3. [Playwright API testing demo](https://github.com/playwrightsolutions/playwright-api-test-demo/blob/main/tests/auth/login.post.spec.ts)
4. [Playwright ressources](https://playwrightsolutions.com/playwright-resources/)

### Reference:
1. https://medium.com/@pothiwalapranav/running-playwright-tests-with-multiple-grep-patterns-c602528f6649
2. https://playwrightsolutions.com/run-a-subset-of-tests-with-grep-and-grep-invert-in-package-json/
