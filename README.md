# KVV's blog

This is a Hugo site wired to the `loficode-hugo-theme` theme.

Image workflow:

- `static/site-images/profile.png` is the home avatar
- `static/site-images/hero.png` is a reusable banner image
- Use the `site-image` shortcode for content images so paths stay stable

Local theme:

- `themes/loficode-hugo-theme/`

Run:

```bash
hugo server
```

Deploy:

- Copy the whole `loficode-site/` folder as the root of a new GitHub repo.
- Keep the hidden `.github/workflows/deploy-loficode-site.yml` file.
- In repo `Settings -> Pages`, set `Source` to `GitHub Actions`.
- Push to `main`.
