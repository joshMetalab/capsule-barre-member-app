# Cici product report (static)

English HTML walkthrough of every live screen:

- Member app (user)
- Platform admin (HQ)
- Shop owner
- Instructor

The site is static. No build step. Push to `main` and Netlify republishes (`netlify.toml` publish directory is `.`).

```bash
npx --yes serve . -p 4173
```

The member prototype remains at `/platform-app.html`.

Screenshots live in `img/{member,admin,shop,instructor}/`. Optional recapture (apps must already be running):

```bash
# member app on :8081, desk on :8020
node capture.mjs
```
