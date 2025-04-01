# 🚀 Vanilla TS + Vite

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Vite](https://img.shields.io/badge/vite-4.x-646CFF.svg?logo=vite)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-3178C6.svg?logo=typescript)
![ESLint](https://img.shields.io/badge/ESLint-8.x-4B32C3.svg?logo=eslint)

Un moderno boilerplate per applicazioni web TypeScript con bundler Vite. Combina la potenza della tipizzazione statica con la velocità di sviluppo di Vite, supportando funzionalità 100% offline e operazioni locali senza API.

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Setup & Development](#-setup--development)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 🔒 TypeScript per codice tipizzato e sicuro
- 🔄 Hot Module Replacement (HMR) per sviluppo rapido
- ⚡ Vite per un bundling ultra-veloce
- 💾 Supporto completo per funzionalità offline (localStorage)
- 📤 Funzionalità di import/export e backup
- 📊 Supporto per dashboard e visualizzazioni statistiche
- 🗓️ Possibilità di implementare timeline e viste calendario
- 🔍 Configurazione ESLint con type-checking
- 🌐 Web application ottimizzata per la distribuzione

## 🗂️ Project Structure

```
bl-vitejs-typescript/
├── public/             # Risorse statiche
├── src/
│   ├── assets/         # Immagini, font e risorse varie
│   ├── modules/        # Moduli TypeScript
│   ├── utils/          # Funzioni di utilità
│   ├── types/          # Definizione di tipi TypeScript
│   ├── index.html      # Template HTML
│   ├── style.css       # Stili globali
│   └── main.ts         # Entry point dell'applicazione
├── .eslintrc.cjs       # Configurazione ESLint
├── tsconfig.json       # Configurazione TypeScript
├── tsconfig.node.json  # Configurazione TypeScript per Node
├── index.html          # Template HTML root
├── package.json        # Dipendenze e script
└── vite.config.ts      # Configurazione Vite
```

## 🚀 Setup & Development

### 📥 Installazione

```bash
# Utilizzando NPM
$ npm install

# Utilizzando Yarn
$ yarn

# Utilizzando PNPM
$ pnpm install
```

### 🔧 Sviluppo

```bash
# Utilizzando NPM
$ npm run dev

# Utilizzando Yarn
$ yarn dev

# Utilizzando PNPM
$ pnpm dev
```

### 📦 Build

```bash
# Utilizzando NPM
$ npm run build

# Utilizzando Yarn
$ yarn build

# Utilizzando PNPM
$ pnpm build
```

### 🔍 Preview

```bash
# Utilizzando NPM
$ npm run preview

# Utilizzando Yarn
$ yarn preview

# Utilizzando PNPM
$ pnpm preview
```

## 📦 Package Managers

Questo progetto supporta diversi package manager. Ecco le caratteristiche di ciascuno:

### NPM

NPM è il package manager predefinito per Node.js.

**Installazione NPM:**
```bash
# Incluso con l'installazione di Node.js
```

**Caratteristiche principali:**
- 📚 Vasto ecosistema di pacchetti
- 🔒 Struttura gerarchica di node_modules
- 📋 Package.json per la gestione delle dipendenze

### Yarn

Yarn è un'alternativa rapida, affidabile e sicura a NPM.

**Installazione Yarn:**
```bash
# Installazione tramite NPM
$ npm install -g yarn
```

**Caratteristiche principali:**
- ⚡ Velocità di installazione superiore
- 📦 Caching offline
- 🔒 Maggiore sicurezza con checksum
- 📋 yarn.lock per installazioni deterministiche

### PNPM

PNPM è un package manager efficiente in termini di spazio su disco.

**Installazione PNPM:**
```bash
# Installazione tramite NPM
$ npm install -g pnpm
```

**Caratteristiche principali:**
- 💾 Risparmio di spazio su disco tramite symlink
- 🚀 Velocità di installazione elevata
- 🔄 Storage con indirizzamento basato sul contenuto
- 📋 pnpm-lock.yaml per blocco delle dipendenze

### Confronto

| Funzionalità          | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Utilizzo disco        | Alto    | Alto    | Basso   |
| Velocità installazione| Lenta   | Veloce  | Velocissima |
| Installazioni parallele| Limitato| Sì      | Sì      |
| Supporto workspaces   | Limitato| Buono   | Ottimo  |
| Modalità offline      | Limitato| Buono   | Buono   |
| Sicurezza             | Buona   | Migliore| Migliore|

## 📚 Resources

- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Vite Documentation](https://vitejs.dev/guide/)
- [JavaScript MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [ESLint Documentation](https://eslint.org/docs/user-guide/)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
