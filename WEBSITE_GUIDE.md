# Website guide

## Preview and edit

From the repository root:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`. This previews the static pages. The `/api/` handlers need a Vercel-compatible environment and do not run through Python's static server.

To update the team directory, edit `assets/team-data.js`. [The team editing guide](TEAM_EDITING_GUIDE.txt) explains the profile and chapter fields.

For form delivery, configure `CONTACT_WEBHOOK_URL` and `CHAPTER_APPLICATION_WEBHOOK_URL` in the deployment environment. The current handlers log submissions and return success even when no webhook is configured, so a successful form response alone does not confirm delivery.

