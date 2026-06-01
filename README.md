# Reality Check AI Legal Pages

These static pages are ready for GitHub Pages:

- `privacy.html`
- `terms.html`

In GitHub, go to **Settings -> Pages** and publish from the `docs` folder on your main branch.

The Flutter app defaults to:

- `https://ovidiu.github.io/reality_check/privacy.html`
- `https://ovidiu.github.io/reality_check/terms.html`

If your GitHub Pages URL is different, build the app with:

```bash
flutter build ios --dart-define=LEGAL_BASE_URL=https://your-user.github.io/your-repo
```

Have a qualified legal professional review these pages before launch.
