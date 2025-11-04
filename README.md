# iptables

Automatic fork of https://git.netfilter.org/iptables/tree/ kept up to date by GitHub Actions on a regular scheduled workflow.

## Automatic Syncing

This repository is automatically synchronized with the upstream iptables repository daily at 2:00 AM UTC via a GitHub Actions workflow. The workflow:

- Fetches the latest changes from https://git.netfilter.org/iptables
- Syncs all branches and tags
- Ensures the fork stays up-to-date with minimal manual intervention

The sync can also be triggered manually from the Actions tab in the GitHub repository.
