# Contributing
We are excited that you have chosen to contribute to Accuguide! We want to ensure contributing is a smooth experience both for repository maintainers and contributors, so we have a few guidelines to follow.

1. Ensure your code is clean and well formatted - we use Prettier, and once you open a pull request, there will be a status check to check if your code follows the Prettier format. If not, you can reformat your code by running `npm run format`.
2. Make sure your code passes lint checks - this also has a status check on pull requests, but you can manually check with `npm run lint`.
3. Add appropriate tests for your code - we use Cypress component and e2e tests. You only really need to make component tests for any components you create or change. For components requiring authentication or data from a server, you can ignore writing tests. If you are feeling up to it, you can visit Cypress's documentation to learn how to mock test data.
4. Make sure all code status checks pass - Let us know if you need help resolving a failed check. Our pull request status checks include tests, formatting, linting, builds, codeql, and Netlify build checks.
5. Feel free to reach out to us if you have questions, comments, or concerns! You can reach us via replying to Github issue, opening a Github discussion, or emailing us at dev@accuguide.org.
