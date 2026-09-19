# How this showcase relates to the private app

1. Keep **funfunpayer/SamNPlayer** (application) **private**.
2. Keep **funfunpayer/SamNPlayer-site** (this repo) **public** for Anna and others.
3. Add teammates as collaborators on the private app repo only.
4. Copy screenshots into `docs/media/` when the UI changes.

Owner action (one-time) if the app is still public:

```bash
gh repo edit funfunpayer/SamNPlayer --visibility private --accept-visibility-change-consequences
```

Then invite only the core team as collaborators on `SamNPlayer`.
