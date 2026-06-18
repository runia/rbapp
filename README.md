# RBApp

The studio site for **RBApp** — an independent iOS studio building focused, offline-first
reference and utility apps for iPhone and iPad. No accounts, no servers, no tracking.

The whole site — the hub **and** every app's pages — is served from the [`docs/`](docs/)
folder via GitHub Pages and lives at **rbstack.com**. Each app has its own subfolder with an
`index.html` and a `privacy.html`; all links are relative, so it is one self-contained repo.

## The catalog

| # | App | Path | Privacy URL |
|---|-----|------|-------------|
| RB-01 | Recapio | [`docs/recapio/`](docs/recapio/) | rbstack.com/recapio/privacy.html |
| RB-02 | Car Parts | [`docs/carparts/`](docs/carparts/) | rbstack.com/carparts/privacy.html |
| RB-03 | OBD Connector | [`docs/obd/`](docs/obd/) | rbstack.com/obd/privacy.html |
| RB-04 | Traffic & DMV | [`docs/traffic-dmv/`](docs/traffic-dmv/) | rbstack.com/traffic-dmv/privacy.html |
| RB-05 | Bußgeldkatalog | [`docs/bussgeldkatalog/`](docs/bussgeldkatalog/) | rbstack.com/bussgeldkatalog/privacy.html |
| RB-06 | Памятка ГИБДД | [`docs/pamyatka-gibdd/`](docs/pamyatka-gibdd/) | rbstack.com/pamyatka-gibdd/privacy.html |

> When the old per-app repos are removed, update each app's **App Store privacy-policy URL**
> to the matching `rbstack.com/<app>/privacy.html` above.

## Design

Single self-contained `index.html` (inline CSS/JS), no build step.
Design system — "field-grade precision": Bricolage Grotesque (display), Hanken Grotesk (body),
Space Mono (utility), engineered grid-paper neutrals with a signal-vermilion accent.

Contact: the **Contact us** button (mailto).
