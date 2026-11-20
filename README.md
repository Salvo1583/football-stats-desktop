<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Football%20Stats%20Desktop&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Match%20data%20collection%20%26amp%3B%20analysis%20app&descSize=18&descAlignY=58" alt="Football Stats Desktop" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/source-private-555555?style=for-the-badge&logo=github" alt="Source private" />
  <img src="https://img.shields.io/badge/project-showcase-36BCF7?style=for-the-badge" alt="Project showcase" />
</p>

> [!NOTE]
> This repository is a **project showcase**: the source code is private. A demo is available on request.

## 🧭 Overview

A **desktop and web application** that collects football match data (fixtures, head-to-head records and detailed match statistics) for the main competitions, and turns it into tables, charts and Excel reports ready for analysis.

Distributed to clients as a standalone Windows app with remote license activation.

## ✨ Key features

- ⚽ **Competitions dashboard**: World Cup, Serie A, Champions League, Premier League, La Liga and more
- 📅 **Calendar view** → **head-to-head view** → **detailed stats**, in a few clicks
- 🤖 **Automated browser-based data collection** with progress tracking and checkpoints, so long scans can resume after an interruption
- 📊 **Built-in charts** for stats and trends
- 📁 **Excel export** of every dataset
- 🌐 **Two modes**: native desktop GUI and a web companion served locally
- 🔑 **Licensing system** with remote activation
- 📦 **Packaged as a Windows executable** for non-technical users

## 🏗️ How it works

```mermaid
flowchart LR
    U([User picks a competition]) --> C[Collector<br/>headless browser]
    C --> P[Parsers<br/>fixtures · H2H · stats]
    P --> S[(Local storage<br/>+ checkpoints)]
    S --> G[Desktop GUI<br/>tables · charts]
    S --> W[Web companion]
    S --> X[Excel export]
```

## 🧰 Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat)
![Qt](https://img.shields.io/badge/PyQt6-41CD52?style=flat&logo=qt&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Excel](https://img.shields.io/badge/Excel_export-217346?style=flat)

## 📬 Contact

Built by **Salvatore Cutaia**, Computer Engineer specialized in AI agents & automations.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
