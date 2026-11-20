<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Football%20Stats%20Desktop&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=App%20di%20raccolta%20e%20analisi%20dei%20dati%20delle%20partite&descSize=18&descAlignY=58" alt="Football Stats Desktop" width="100%" />
</p>

<p align="center"><a href="README.md">🇬🇧 English</a> · <b>🇮🇹 Italiano</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/codice-privato-555555?style=for-the-badge&logo=github" alt="Codice privato" />
  <img src="https://img.shields.io/badge/vetrina-progetto-36BCF7?style=for-the-badge" alt="Vetrina del progetto" />
</p>

> [!NOTE]
> Questo repository è una **vetrina del progetto**: il codice sorgente è privato. Una demo è disponibile su richiesta.

## 🧭 Panoramica

Un'**applicazione desktop e web** che raccoglie i dati delle partite di calcio (calendari, precedenti e statistiche dettagliate) per le competizioni principali e li trasforma in tabelle, grafici e report Excel pronti per l'analisi.

Distribuita ai clienti come app Windows autonoma, con attivazione della licenza da remoto.

## ✨ Funzionalità principali

- ⚽ **Dashboard delle competizioni**: Mondiali, Serie A, Champions League, Premier League, Liga e altre
- 📅 **Calendario** → **precedenti** → **statistiche dettagliate**, in pochi clic
- 🤖 **Raccolta dati automatica tramite browser**, con avanzamento visibile e checkpoint per riprendere le scansioni lunghe dopo un'interruzione
- 📊 **Grafici integrati** per statistiche e tendenze
- 📁 **Esportazione in Excel** di ogni insieme di dati
- 🌐 **Due modalità**: interfaccia desktop nativa e companion web servito in locale
- 🔑 **Sistema di licenze** con attivazione remota
- 📦 **Pacchettizzata come eseguibile Windows** per utenti non tecnici

## 🏗️ Come funziona

```mermaid
flowchart LR
    U([L'utente sceglie una competizione]) --> C[Raccolta<br/>browser headless]
    C --> P[Parser<br/>calendario · precedenti · statistiche]
    P --> S[(Archivio locale<br/>+ checkpoint)]
    S --> G[Interfaccia desktop<br/>tabelle · grafici]
    S --> W[Companion web]
    S --> X[Esportazione Excel]
```

## 🧰 Tecnologie

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat)
![Qt](https://img.shields.io/badge/PyQt6-41CD52?style=flat&logo=qt&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Excel](https://img.shields.io/badge/Export_Excel-217346?style=flat)

## 📬 Contatti

Realizzato da **Salvatore Cutaia**, ingegnere informatico specializzato in agenti AI e automazioni.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
[![Website](https://img.shields.io/badge/Website-neuralform.it-111111?style=flat&logo=googlechrome&logoColor=white)](https://neuralform.it/)
