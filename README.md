# Penderrin-Projects

Org-wide defaults and workflow templates.

## Workflow Templates

### Discord Release Notification
Automatically posts to Discord when any repo publishes a release. Uses the org-level `DISCORD_WEBHOOK_URL` secret.

Already deployed to all repos. For new repos, copy `.github/workflows/discord-notify.yml` from any existing repo, or use the template in `workflow-templates/`.
