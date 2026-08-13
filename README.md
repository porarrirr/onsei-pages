# Onsei Pages

English | [日本語](README.ja.md)

The public website for Onsei, an iOS app for on-device Japanese speech synthesis. The site introduces the app and publishes the support, privacy, and legal information required for App Store distribution.

Because synthesis is designed to run on the device, the app can generate Japanese speech without relying on a project-operated synthesis server after the required local resources are available.

## Published pages

- `index.html` — product introduction
- `support.html` — support information
- `privacy.html` — privacy policy
- `terms.html` — terms of use

## Local preview

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765/.
