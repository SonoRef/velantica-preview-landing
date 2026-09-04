# velantica-preview-landing

Static teaser page for velantica.com: black background, one emerald light, wordmark, "Setting sail."

No build step, no dependencies, no external requests. Inter Light/Regular (SIL OFL, see `fonts/LICENSE-Inter.txt`) is self-hosted so the wordmark looks the same on every OS.

## Deploy

GitHub Pages serves the `main` branch root. Every push to `main` goes live within about a minute.

- Live: https://sonoref.github.io/velantica-preview-landing/
- velantica.com: pending DNS. Once a CNAME for `velantica.com` points at `sonoref.github.io`, add the domain under Settings → Pages (or commit a `CNAME` file) and Pages issues the certificate.

## Local

    python3 -m http.server 8080
