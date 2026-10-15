# SN – Personal Site

A static multi-page website (HTML + CSS) for the Digital Media Technologies assignment.

**Pages:** Home · About · Education · Projects · Contact · Thank You

## Run locally
Open `index.html` in a browser, or run a tiny server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages
1. Push this repo to GitHub (branch `main`).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**, branch **main**, folder **/ (root)**.
4. Save. After a minute your site is live at `https://<username>.github.io/<repo-name>/`.

## Notes
- The contact form is static: it redirects to `thankyou.html` but does not send email. To receive messages, point the form `action` at a service such as Formspree or Netlify Forms.
