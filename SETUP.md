# Owner: public downloads + private source

From a private `SamNPlayer` checkout (as **funfunpayer**):

```bash
./scripts/sync-public-site.sh          # media + website/ → this repo
./scripts/publish-public-release.sh v0.5.10   # after private tag builds
```

Then enable **GitHub Pages** (`main` / root) so `index.html` is the landing.

Do **not** point images at `raw.githubusercontent.com/.../SamNPlayer/...` —
the app repo is private and those URLs 404 for visitors.
