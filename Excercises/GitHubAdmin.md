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
  * Not that we could find
* Character encoding at import, Swedish characters
  * UTF-8 seems to be the one to use

## Agenda
* Multiple or single organizations, MT
* Repository structure, MK
  * Naming, tagging and so on
* Working with teams, MK
* Insights, MT
* Connect to AAD, MT
* Connect to Azure boards, MK
* Using the Marketplace, MK 
* Audit log, MT
* Webhooks, MT
