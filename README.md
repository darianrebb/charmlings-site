# Charmlings App Store site

Public GitHub Pages site for Apple App Store **Support URL** and **Privacy Policy URL**.

## Live URLs

| App Store Connect field | URL |
| --- | --- |
| Support URL | `https://darianrebb.github.io/charmlings-site/support.html` |
| Privacy Policy URL | `https://darianrebb.github.io/charmlings-site/privacy.html` |

Optional Marketing URL: `https://darianrebb.github.io/charmlings-site/`

## Publish checklist

1. Confirm support email (`support@charmlings.app`) is an inbox you monitor.
2. Keep the repo **public**, with Pages set to **Deploy from a branch → `main` / root**.
3. Confirm both pages load over HTTPS on a phone (no login wall).

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## App Store Connect checklist

- [ ] Privacy Policy URL set under **App Information**
- [ ] Support URL set under the iOS version’s **Version Information**
- [ ] App Privacy “nutrition labels” match this policy (local device storage; purchases via Apple; no tracking SDKs)
