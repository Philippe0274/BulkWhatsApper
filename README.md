# 📱 WhatsApp Verzend Tool

Snel WhatsApp-berichten versturen naar meerdere contacten via Excel!

## ✨ Features

- 📊 **Excel importeren** - Voeg contacten in bulk toe
- 🌍 **Tweetalig** - Nederlands & Frans support
- 🟢 **WhatsApp integatie** - Verzend direct naar contacten
- 📱 **Installeerbaar** - Zet op desktop/mobile als app
- 💾 **Offline werkend** - Gegevens opgeslagen in browser
- ⚡ **Snel & Simpel** - Geen registratie nodig!

## 🚀 Quick Start

### Online gebruiken
1. Open: https://jouw-username.github.io/externe-lijst/
2. Importeer je Excel-bestand
3. Schrijf je bericht
4. Klik [🟢 WhatsApp] per contact

### Als App installeren (PC/Mobile)
1. Open de website
2. Klik **"⬇️ Installeer als App"**
3. Bevestig installatie
4. App verschijnt op je desktop/telefoon!

## 📋 Excel Format

Nodig:
- **First Name** of **Voornaam**
- **Mobile Phone Number** of **GSM** of **Telefoon** (met +32 of 0032)
- **Preferred language** of **Taal** (NL of FR) - optioneel

```
| First Name | Last Name | Mobile Phone Number | Preferred language |
|------------|-----------|---------------------|-------------------|
| Jan        | Jansen    | +32 456 45 90 44    | NL                |
| Marie      | Dupont    | +32 456 08 30 30    | FR                |
```

## 💬 Bericht Placeholders

- `{firstName}` - Voornaam van contactpersoon
- `{lastName}` - Achternaam
- `{phone}` - Telefoonnummer

## 🔧 Technologie

- HTML5 + JavaScript
- XLSX library voor Excel import
- Progressive Web App (PWA)
- LocalStorage voor data
- WhatsApp wa.me API

## 📂 Bestanden

- `index.html` - Hoofdapp
- `manifest.json` - PWA configuratie
- `sw.js` - Service Worker (offline)
- `README.md` - Dit bestand

## 🛠 GitHub Setup

1. Fork of clone deze repo
2. Push naar `main` branch
3. Ga naar Settings → Pages
4. Selecteer **"Deploy from a branch"**
5. Kies **main** branch
6. App is live op `https://jouw-username.github.io/externe-lijst/`

## 📝 Licentie

Gratis & open source! Gebruik het zoals je wil.

## 💡 Tips

- Nummers kunnen spaties hebben (+32 456 45 90 44 werkt!)
- Bericht wordt opgeslagen - je kan het later aanpassen
- Status ✓ toont welke contacten al zijn verzonden
- Alles gebeurt lokaal in je browser - niets wordt geupload!

---

**Veel succes met je WhatsApp-campagne! 🚀**

