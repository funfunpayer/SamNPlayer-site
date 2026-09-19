# Owner: public downloads + private source

1. Make `funfunpayer/SamNPlayer` **private** (source + CI).
2. Keep **this** repo (`SamNPlayer-site`) **public**.
3. After each private app release, publish the same binaries here:

```bash
# from the private app checkout, as owner:
./scripts/publish-public-release.sh v0.5.8
```

4. Mirror `docs/media/*.png` into this repo after going private so images
   keep working without raw URLs to the private app.

Full write-up: in the private app repo, `docs/CLOSED_SOURCE.md`.
