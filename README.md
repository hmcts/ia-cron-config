# IA Cron Helm Chart

Helm chart for the IA kubernetes cron job. It uses the [ia-hearings-api](https://github.com/hmcts/ia-hearings-api) image to execute scheduled tasks by passing the arguments: `run [taskname]` to the jar.
