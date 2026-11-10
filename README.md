# Gravatar Checker

A static, single-page app that checks whether up to 10 email addresses have a Gravatar.

Emails are hashed (SHA-256) in the browser; only the hash is sent to Gravatar. No backend required.

## Run locally

```bash
python3 -m http.server 8765
```

Open http://localhost:8765 (hashing requires a secure context: localhost or HTTPS).

## Deploy

Import the repo into Vercel as a static site (no build command, no framework).
