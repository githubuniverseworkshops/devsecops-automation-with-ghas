<h1 align="center">DevSecOps Automation with GitHub Advanced Security</h1>
<h5 align="center">@johnlugton @mario-campos @cmboling</h3>

<p align="center">
  <a href="#mega-prerequisites">Prerequisites</a> •  
  <a href="#books-resources">Resources</a>
</p>

> This workshop is designed to get you familiar with GitHub Advanced Security (GHAS) so that you can better understand how to use it in your own repositories. You'll use GitHub Advanced Security features like code scanning and secret scanning to detect vulnerabilities, and see how to use automation to detect these issues before they reach production.

## :mega: Prerequisites

To participate in the workshop you need a GitHub account and need to be invited to the workshop organization [githubuniverseworkshops](https://github.com/devsecops-automation-with-ghas). If your repository hasn't been automatically created in the the workshop organization, create a new project and push a copy of the `devsecops-automation-with-ghas` project.

```bash
git clone https://github.com/githubuniverseworkshops/devsecops-automation-with-ghas.git
cd devsecops-automation-with-ghas
git remote set-url origin https://github.com/githubuniverseworkshops/<your project>.git
```

## :books: Resources
- [About code scanning](https://docs.github.com/en/github/finding-security-vulnerabilities-and-errors-in-your-code/about-code-scanning)
- [About dependency scanning](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies)
- [About secret scanning](https://docs.github.com/en/github/administering-a-repository/about-secret-scanning)
- [Action events that trigger workflows](https://docs.github.com/en/free-pro-team@latest/actions/reference/events-that-trigger-workflows)
- [Configuring builds for compiled languages](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-the-codeql-workflow-for-compiled-languages)
- [Configuring code scanning](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning)
- [Configuring notifications for dependabot alerts](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/configuring-notifications-for-vulnerable-dependencies#configuring-notifications-for-dependabot-alerts)
- [Customizing dependency updates](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/customizing-dependency-updates)
- [Dependency update configuration options](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/configuration-options-for-dependency-updates)
- [Filter pattern cheat sheet](https://docs.github.com/en/free-pro-team@latest/actions/reference/workflow-syntax-for-github-actions#filter-pattern-cheat-sheet)
- [Running additional queries](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning#running-additional-queries)
- [Troubleshooting code scanning workflow](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/troubleshooting-the-codeql-workflow)
- [Code scanning API](https://docs.github.com/en/free-pro-team@latest/rest/reference/code-scanning)
- [GraphQL API](https://docs.github.com/en/free-pro-team@latest/graphql)
  - [RepositoryVulnerabilityAlert](https://docs.github.com/en/free-pro-team@latest/graphql/reference/objects#repositoryvulnerabilityalert)
- [REST API](https://docs.github.com/en/free-pro-team@latest/rest)
