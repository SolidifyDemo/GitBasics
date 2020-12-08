## ToDos

* “Restrict who can dismiss”, what is that
  * If your repository requires reviews, you can dismiss pull request reviews that are no longer valid or are unable to be approved by the reviewer.
  * https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/dismissing-a-pull-request-review
* Secrets
  * Can we use other key vaults. Yes, Azure Key vault and others
  * Can we push secrets by API, Yes: https://docs.github.com/en/free-pro-team@latest/rest/reference/actions#secrets
  * Secrets encryption strength: https://docs.github.com/en/free-pro-team@latest/actions/reference/encrypted-secrets
  * Keys Secrets for self hosted runners, same as above
* Can prio be changed on builds
  * No, you can cancel builds though 
* Is it possible to disable loggshipping to GitHub.com
  * Not that we could find. GitHub AE could be an option
* Character encoding at import, Swedish characters
  * UTF-8 seems to be the one to use

## Agenda
* Multiple or single organizations, MT
  * Single organizations is recommended for all who work together. Extra org for lab/training maybe or if you have a lot of repos.
* Repository structure, MK
  * Naming, tagging and so on
* Working with teams, MK
* Insights, MT
  * Se what is happening in the project
  * Part of GitHub One
* Connect to AAD, MT
  * How does it work with accounts (GH Handles and AAD accounts)?
  * https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/github-tutorial
  * https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/about-authentication-with-saml-single-sign-on
* Connect to Azure boards, MK
* Using the Marketplace, MK 
* Webhooks, MT
  * A way to integrate with other products
  * Example, Azure Pipelines to GitHub (adds webhooks)
  * What would you like to integrate to? Teams, Slack, Jira...?* 
* Audit log, MT
  * On org level
  * Can be reached by API to monitor
  * https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-organizations-and-teams/reviewing-the-audit-log-for-your-organization

