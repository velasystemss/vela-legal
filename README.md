# Vela — legal pages

The Privacy Policy and Terms of Use for the Vela iPhone app, in Turkish and English, served with
GitHub Pages at https://velasystemss.github.io/vela-legal/. This repository is public because App
Store Connect and the app itself need reachable URLs. It holds nothing else: no app code, no keys,
no user data.

| Page | URL |
|---|---|
| Index | `/` |
| Gizlilik Politikası | `/privacy-tr.html` |
| Privacy Policy | `/privacy-en.html` |
| Kullanım Koşulları | `/terms-tr.html` |
| Terms of Use | `/terms-en.html` |

The earlier address, https://velasystemss.github.io/astro-legal/, stays online with short notices
that point here.

## Changing the name, the contact, who is responsible or the date

`_config.yml` holds them once, and every page reads from it. GitHub Pages rebuilds on push.

## Keeping this true

These pages describe how the app actually behaves: everything the person enters stays on the
phone; no account, no server, no analytics, no tracking, no third-party SDKs; the only things that
leave the phone go to Apple (place search to Apple Maps, purchases through the App Store and
StoreKit). **If the app changes so that any of that stops being true, these pages change in the
same commit as the app.**

The app bundles the privacy policy in both languages (`App/Resources/Legal/privacy-policy-tr.md`,
`privacy-policy-en.md` in the app repository). Update them together with `privacy-tr.html` and
`privacy-en.html`.

## Contact

velalabss@gmail.com
