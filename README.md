# Meyer Gartenglanz – Website

Statische Website für Meyer Gartenglanz (Gartengestaltung, Gartenbau & Gartenpflege im Thurgau).

## Struktur

- `index.html` – Startseite
- `leistungen.html` – Leistungen
- `projekte.html` – Referenzprojekte
- `kontakt.html` – Kontakt
- `assets/favicon.svg` – Favicon

Reines HTML/Tailwind (CDN) – kein Build-Schritt nötig. Einfach die Dateien öffnen oder deployen.

## Bekannte offene Punkte

- **Kontaktformular:** Aktuell ohne funktionierenden Versand (statische Seite = kein Server-Backend).
  Um E-Mails wirklich zu verschicken, bei [Formspree](https://formspree.io) oder [Web3Forms](https://web3forms.com)
  einen kostenlosen Account anlegen und die Formular-`action`-URL in `kontakt.html` eintragen.
- **Bilder:** Die aktuellen Fotos stammen aus dem ursprünglichen Design-Export (temporäre Google-Vorschau-Links).
  Für den Live-Betrieb empfiehlt es sich, eigene Fotos der tatsächlichen Projekte einzusetzen.
- **Adresse/Telefon:** Platzhalterwerte (Musterstraße 12, +41 52 000 00 00) – bitte durch echte Angaben ersetzen.

## Deployment via GitHub Pages

1. Repo auf GitHub pushen (Branch `main`).
2. In den Repo-Einstellungen unter „Pages" als Quelle den Branch `main` / Ordner `/ (root)` wählen.
3. Die Seite ist danach unter `https://<username>.github.io/<repo-name>/` erreichbar.
