# Upgrade package versions to fix vulnerabilities

Snyk will always recommend the smallest upgrade of a dependency to resolve the vulnerability. To resolve a vulnerability in a transitive dependency Snyk will calculate the dependency tree for your project and determine the minimum upgrade to the direct dependency which will result in a vulnerability free version of the indirect dependency.

Some fixes may require a major upgrade of a dependency. In this situation, we indicate on the Fix PR screen if we suspect a major change causing breakage.

See [Upgrading dependencies with automatic PRs](../../../scan-application-code/snyk-open-source/open-source-basics/upgrading-dependencies-with-automatic-prs.md) for more details.