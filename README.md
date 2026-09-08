# Charmlings App Store site

Public GitHub Pages site for Apple App Store **Support URL** and **Privacy Policy URL**.

## Live URLs (after Pages is enabled)

Replace `YOUR_GITHUB_USER` with your GitHub username:

| App Store Connect field | URL |
| --- | --- |
| Support URL | `https://YOUR_GITHUB_USER.github.io/charmlings-site/support.html` |
| Privacy Policy URL | `https://YOUR_GITHUB_USER.github.io/charmlings-site/privacy.html` |

Optional Marketing URL: `https://YOUR_GITHUB_USER.github.io/charmlings-site/`

## Before you publish

1. Replace every `SUPPORT_EMAIL_PLACEHOLDER` in `support.html` and `privacy.html` with a real inbox you monitor.
2. Create a **public** GitHub repository named `charmlings-site` (or update the URLs above to match).
3. Push `main`, then enable **Settings → Pages → Deploy from a branch → `main` / root**.
4. Confirm both pages load over HTTPS on a phone (no login wall).

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## App Store Connect checklist

- [ ] Privacy Policy URL set under **App Information**
- [ ] Support URL set under the iOS version’s **Version Information**
- [ ] App Privacy “nutrition labels” match this policy (local device storage; purchases via Apple; no tracking SDKs)
