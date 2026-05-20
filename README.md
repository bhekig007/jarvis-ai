# Jarvis AI

Jarvis AI is an agentic content command center for turning founder strategy topics into short-form posts, a weekly publishing queue, and exportable content plans.

## Live site

The app is configured for GitHub Pages through the workflow in `.github/workflows/pages.yml`.

Expected Pages URL after deployment:

https://bhekig007.github.io/jarvis-ai/

Connect X page:

https://bhekig007.github.io/jarvis-ai/x.html

## Deployment

GitHub Pages should use **GitHub Actions** as the source. Leave the custom domain field blank unless you own a separate domain such as `example.com`.

## X setup

In the X Developer app, use OAuth 2.0 with PKCE and set the app type to **Single Page App**.

Callback / Redirect URL:

https://bhekig007.github.io/jarvis-ai/callback.html

Website URL:

https://bhekig007.github.io/jarvis-ai/

Scopes:

- `tweet.read`
- `tweet.write`
- `users.read`
- `offline.access`

Jarvis stores the X Client ID and OAuth token in the browser. Do not paste X passwords or client secrets into the app.

## What it does

- Generates conversion-aware founder content drafts
- Scores drafts for clarity and intent
- Moves selected posts into a weekly plan
- Saves the queue in the browser
- Connects to X through OAuth 2.0 PKCE
- Publishes approved posts to X manually
- Exports the plan as CSV or JSON