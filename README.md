# Kozlowski Financial

Marketing site for Kozlowski Financial. Static HTML + Tailwind (CDN), deployed on Netlify.

## Pages

- `index.html` — home
- `services.html` — services & pricing
- `book.html` — consultation form
- `thanks.html` — post-submission page

## Form

The consultation form on `book.html` uses [Netlify Forms](https://docs.netlify.com/forms/setup/). Submissions are captured automatically once deployed to Netlify — no third-party service. View them in the Netlify dashboard under **Forms → booking**.

Email notifications: Netlify site settings → **Forms → Form notifications → Add notification**.

## Local preview

Just open `index.html` in a browser. No build step.

## Deploy

Push to `main` → Netlify auto-deploys. Domain is managed in the Netlify dashboard.
