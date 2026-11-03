# Immo237

Kostenloses Immobilienportal für Yaoundé und Douala (Kamerun).

## Bereits implementiert
- Französisch und Englisch (Grundoberfläche)
- Suche nach Stadt, Immobilientyp und Kauf/Miete
- Supabase-Anmeldung und Registrierung
- Inserate werden zur Moderation eingereicht (`pending`)
- Nur freigegebene Angebote sind öffentlich sichtbar
- WhatsApp-Kontakt zu veröffentlichten Inseraten

## Infrastruktur
Frontend: GitHub Pages (`index.html`). Backend: separates Supabase-Projekt `scmtxejtcmbtiqppwyge`. Datenbank: `public.properties` mit Row-Level-Security.

## Nächste Aufgaben
- Moderationsdashboard (Freigeben/Ablehnen)
- Foto-Upload
- End-to-End-Tests, rechtliche Seiten und Meldemechanismus

## GitHub Pages aktivieren
Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
Danach voraussichtlich unter https://lucien49237.github.io/Immo237/ erreichbar. In Supabase unter Authentication → URL Configuration die Site URL und Redirect URLs ergänzen.

Pilotversion ohne Zahlungsabwicklung und ohne Eigentumsprüfung.
