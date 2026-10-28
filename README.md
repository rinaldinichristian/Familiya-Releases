# 🏡 Familiya — Public Releases & OTA Distribution Hub

<p align="center">
  <img src="https://img.shields.io/badge/Latest_Release-v1.18.1%2B106-2D6A4F?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-Android_APK-3DDC84?style=for-the-badge&logo=android&logoColor=black" />
  <img src="https://img.shields.io/badge/OTA_Updates-Active-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
</p>

Benvenuto nella repository pubblica ufficiale di distribuzione di **Familiya**!

Questa repository funge da **CDN (Content Delivery Network)** e server di distribuzione per gli aggiornamenti **OTA (Over-The-Air)** dell'applicazione **Familiya** per dispositivi Android.

> 🔒 **Nota sulla Privacy del Codice:** Il codice sorgente di Familiya è custodito in una repository privata (`rinaldinichristian/Familiya`). Questa repository pubblica ospita esclusivamente i pacchetti di installazione certificati (`.apk`) e le note di rilascio delle versioni ufficiali.

---

## 📲 Scarica l'Ultima Versione (`v1.18.1+106`)

Puoi scaricare e installare l'ultima versione stabile per Android direttamente da qui:

- 👉 **[Scarica l'ultima Release (`v1.18.1+106`)](https://github.com/rinaldinichristian/Familiya-Releases/releases/latest)**
- 📦 **[Archivio di tutte le Releases](https://github.com/rinaldinichristian/Familiya-Releases/releases)**

---

## 🔄 Sistema di Aggiornamento Automatico (OTA)

Familiya integra un motore nativo di aggiornamento **Over-The-Air (`UpdateService`)**:
1. Ad ogni nuovo rilascio pubblicato tramite la pipeline CI/CD di GitHub Actions, una **Firebase Cloud Function (`notifyAppUpdate`)** invia una notifica push sul topic `updates` a tutti i dispositivi della famiglia.
2. All'apertura dell'app, **Familiya** interroga automaticamente le API di questa repository (`rinaldinichristian/Familiya-Releases`), confronta il numero di versione e build (`v1.18.1+106`) con quello installato e mostra un banner dedicato per scaricare e installare il nuovo APK direttamente dall'app.

---

## ✨ Cosa Include Familiya (`v1.18.1+106`)

| Modulo | Funzionalità Principali |
| :--- | :--- |
| **👨‍👩‍👧‍👦 Ruoli & Fasce d'Età** | Profili **Genitore** (amministratore), **Ragazzo (11–17 anni)** con autonomia in cucina e **Bambino (4–10 anni)** protetto da **Parental Gate** conforme a COPPA/GDPR-K. |
| **🍳 AI Meal Planner & Diete** | **396 ricette** strutturate passo-passo su 6 portate; supporto per dieta Mediterranea, Vegetariana, Vegana, Senza Glutine/Lattosio, **Yogica (Mitahara)** e **Ayurvedica Classica Unificata**; gestione assenze e **Modalità Schiscetta/Thermos**. |
| **⚡ Cucina al Volo** | Motore istantaneo (`QuickRecipeMatcher`) che suggerisce cosa cucinare subito con gli ingredienti già presenti in dispensa (`Pronte 100%` o `Manca 1 ingrediente`). |
| **🛒 Spesa Smart & Prezzi ISTAT** | **566 ingredienti Open Food Facts**, calcolo prezzi calibrato su **107 province italiane** e confronto carrello in tempo reale tra **6 catene GDO** (*Esselunga, Conad, Coop, Carrefour, Lidl, Eurospin*). |
| **🥗 Diario Benessere (YAZIO-style)** | Tracciamento calorie e macronutrienti scalati sulle porzioni, contatore bicchieri d'acqua e monitoraggio corporeo nella Dashboard. |
| **🎯 Gamification, Mascotte & Premi** | Missioni con prova fotografica, revisione genitori, 6 **Mascotte Interattive** sbloccabili e **Negozio Premi Segmentato** (*Tutti i Figli*, *Solo Bambini*, *Solo Ragazzi*, *Solo Genitori 🔒*). |
| **💬 Chat Familiare Sicura** | Messaggi in tempo reale, foto, note vocali, **Sticker Familiari** categorizzati e libreria GIF curata. |
| **💎 Monetizzazione Etica** | Rispetto rigoroso Google Play Families / COPPA, card **Sponsor Etico** e piano **Familiya Plus**. |

---

*Ultimo sincronismo automatico della documentazione: **2026-10-28 23:22 UTC***
