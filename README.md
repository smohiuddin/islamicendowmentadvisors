# Waqf Advisory — Jekyll Site

A clean, one-page Jekyll site for GitHub Pages.

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000

## GitHub Pages Setup

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://yourusername.github.io/repo-name`

## Customization

### Org details
Edit `_config.yml` to update your organization name, email, and tagline.

### Content
All page content is in `index.html`. Each section is clearly commented:
- `hero` — main headline and intro
- `services` — the four service cards
- `about` — mission statement + stats
- `advisors` — team members
- `contact` — CTA and email

### Colors
All colors are CSS custom properties in `_layouts/default.html` under `:root`. 
Key variables:
- `--gold` — accent color (`#b8892a`)
- `--parchment` — background tone
- `--ink` — text color

### Fonts
Using **Cormorant Garamond** (display) + **DM Sans** (body) from Google Fonts.
Change the `@import` URL in the layout to swap fonts.
