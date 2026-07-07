# obt-demo — White-Label-Landingpage OBT AG

Demo-Landingpage für OBT AG (Arvut-Partnerprogramm), live unter **https://obt.arvut.ch** (noindex).

- **Quelle/Master:** `index.html` (= `index.src.html`), einsprachig DE, self-contained (lokale Fonts, keine externen Assets).
- **Marke:** OBT-Rot `#af191e`. Logo + Teamfotos in `assets/img/`, Manrope/Inter in `assets/fonts/`.
- **Deploy (Update nach Änderung):** Statik nach `/srv/abm/obt-demo/` auf 51.15 kopieren (Container `obt-demo`, nginx:alpine, ro-Mount → sofort aktiv, kein Restart). GCP-Proxy 35.216.135.137 + Let's Encrypt.
- Mehrsprachigkeit (FR/IT/EN) folgt bei Bedarf (Muster: tbo-demo `build.py`).

Interne Redaktions-/Kanon-Hinweise: siehe privates `arvut-team-memory`.
