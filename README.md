# Vela — legal pages

The Privacy Policy, Terms of Use and support page for the Vela iPhone app, in Turkish and English, served with
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
| Destek | `/support-tr.html` |
| Support | `/support-en.html` |

The earlier address, https://velasystemss.github.io/astro-legal/, stays online with short notices
that point here.

## Changing the name, the contact, who is responsible or the date

`_config.yml` holds them once, and every page reads from it. GitHub Pages rebuilds on push.

The support page answers what the App Store requires a support URL to answer: cancelling,
restoring purchases, changing birth details, the notifications and their time, adding and styling
the widget, changing the language, and deleting data. **It describes screens in the app by their
real names. If a screen or a control is renamed, the support page changes in the same commit.**

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
