# Pcloudy Sample Projects

Working examples for running your Appium, Selenium and Playwright tests on [Pcloudy](https://www.pcloudy.com)'s real device cloud. Clone a sample, add your credentials, run it.

[![Docs](https://img.shields.io/badge/docs-pcloudy.com-0b5fff)](https://www.pcloudy.com/docs/)
[![Website](https://img.shields.io/badge/website-pcloudy.com-0b5fff)](https://www.pcloudy.com)

## Pick your stack

### Mobile app testing (Appium, real Android and iOS devices)

| Language / framework | Repo | Good for |
|---|---|---|
| Java | [PC-appium-java](https://github.com/Pcloudy-Sample/PC-appium-java) | Maven project, no test framework. Simplest starting point |
| Java + TestNG | [PC-appium-java-testng](https://github.com/Pcloudy-Sample/PC-appium-java-testng) | Single and parallel runs |
| Python | [PC-appium-python](https://github.com/Pcloudy-Sample/PC-appium-python) | Android and iOS, app and web tests |
| Node.js | [PC-appium-nodejs](https://github.com/Pcloudy-Sample/PC-appium-nodejs) | Android and iOS, app and web tests |
| C# | [PC-appium-CSharp](https://github.com/Pcloudy-Sample/PC-appium-CSharp) | .NET projects |

### Browser testing (Selenium, remote grid)

| Language | Repo | Good for |
|---|---|---|
| Java | [PC-selenium-java](https://github.com/Pcloudy-Sample/PC-selenium-java) | Maven + TestNG |
| C# | [PC-selenium-CSharp](https://github.com/Pcloudy-Sample/PC-selenium-CSharp) | .NET projects |

### Pipelines and scale

| Repo | What you get |
|---|---|
| [PC-ci-cd-templates](https://github.com/Pcloudy-Sample/PC-ci-cd-templates) | Pipeline templates for GitHub Actions, Jenkins, GitLab CI and Azure DevOps |
| [PC-parallel-execution-patterns](https://github.com/Pcloudy-Sample/PC-parallel-execution-patterns) | Patterns for splitting a suite across parallel devices |

## Run a sample

1. Get a Pcloudy account and your API key from the Pcloudy dashboard.
2. Open the repo for your stack and clone it.
3. Set your credentials as environment variables. Never commit them to code.
4. Follow the run steps in that repo's README. Commands and settings differ by repo.

## Docs

- [Pcloudy documentation](https://www.pcloudy.com/docs/)
- [API reference](https://www.pcloudy.com/docs/api-reference)

## Contributing and support

- Found a bug or an outdated step in a sample? [Open an issue](https://github.com/Pcloudy-Sample) in that repo.
- Pull requests that fix or improve a sample are welcome.
- Questions about your Pcloudy account or devices: support@pcloudy.com
