# bubbleflow-status

Uptime monitor for https://bubbleflow.live, run by GitHub Actions every 5 minutes
(`.github/workflows/uptime.yml`): it checks the home page and `/healthz` (app running and receiving HyperLiquid
data). On failure it opens an issue labelled `incident` assigned to the owner (GitHub emails the owner), and closes
it when the site is back. Test the alert: Actions → "Uptime bubbleflow.live" → Run workflow → tick "Simulate an outage".
