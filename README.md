# Action Repo

This is a dummy GitHub repository to trigger webhook events.

## How It Works

This repo is connected to a webhook (in `webhook-repo`) via GitHub Webhooks.

When you:

- Push a commit
- Create a pull request
- Merge a PR

...it sends events to the webhook receiver (`webhook-repo` Flask server).

---

## How to Use This Repo

You can test by:

1. Adding a file or editing a file
2. Creating a branch and opening a PR
3. Merging a PR

Each of these will trigger a webhook event.

