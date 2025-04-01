# 🚀 Vanilla TS + Vite

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Vite](https://img.shields.io/badge/vite-4.x-646CFF.svg?logo=vite)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-3178C6.svg?logo=typescript)
![ESLint](https://img.shields.io/badge/ESLint-8.x-4B32C3.svg?logo=eslint)

A modern boilerplate for TypeScript web applications with Vite bundler. Combines the power of static typing with Vite's speed, supporting 100% offline functionality and local operations without API.

**Topics:** `typescript` `vite` `web-app` `spa` `offline-first` `type-safety` `local-storage` `minimal` `esm`

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Setup & Development](#-setup--development)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 🔒 Type safety with TypeScript
- 🔄 Hot Module Replacement (HMR) during development
- ⚡ Ultra-fast build with Vite bundler
- 💾 Support for offline data storage
- 📤 Import/export capability for data
- 🔍 TypeScript linting with ESLint
- 📊 Support for dashboard and statistical visualizations
- 🗓️ Possibility to implement timeline and calendar views
- 🔒 Strict type checking
- 📦 ES Module support

## 🗂️ Project Structure

```
bl-vitejs-typescript/
├── public/             # Static assets
├── src/
│   ├── assets/         # Project assets (images, fonts, etc.)
│   ├── modules/        # TypeScript modules
│   ├── utils/          # Utility functions
│   ├── types/          # TypeScript type definitions
│   ├── index.html      # HTML template
│   ├── style.css       # Global styles
│   └── main.ts         # Application entry point
├── .eslintrc.cjs       # ESLint configuration
├── tsconfig.json       # TypeScript configuration
├── tsconfig.node.json  # TypeScript configuration for Node
├── index.html          # HTML template root
├── package.json        # Project dependencies and scripts
└── vite.config.ts      # Vite configuration
```

## 🚀 Setup & Development

### 📥 Install

```bash
# Using NPM
$ npm install

# Using Yarn
$ yarn

# Using PNPM
$ pnpm install
```

### 🔧 Development

```bash
# Using NPM
$ npm run dev

# Using Yarn
$ yarn dev

# Using PNPM
$ pnpm dev
```

### 📦 Build

```bash
# Using NPM
$ npm run build

# Using Yarn
$ yarn build

# Using PNPM
$ pnpm build
```

### 🔍 Preview

```bash
# Using NPM
$ npm run preview

# Using Yarn
$ yarn preview

# Using PNPM
$ pnpm preview
```

## 📦 Package Managers

This project supports multiple package managers. Here's how to use each one:

### NPM

NPM is the default package manager for Node.js.

**Install NPM:**
```bash
# Included with Node.js installation
```

**Key features:**
- 📚 Vast package ecosystem
- 🔒 Hierarchical node_modules structure
- 📋 Package.json for dependency management

### Yarn

Yarn is a fast, reliable, and secure alternative to NPM.

**Install Yarn:**
```bash
# Install using NPM
$ npm install -g yarn
```

**Key features:**
- ⚡ Faster installation speeds
- 📦 Offline caching
- 🔒 Better security with checksums
- 📋 yarn.lock for deterministic installations

### PNPM

PNPM is a disk-space efficient package manager.

**Install PNPM:**
```bash
# Install using NPM
$ npm install -g pnpm
```

**Key features:**
- 💾 Disk space savings through symlinks
- 🚀 Fast installation speeds
- 🔄 Content-addressable storage
- 📋 pnpm-lock.yaml for dependency lock

### Comparison

| Feature               | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Disk usage            | High    | High    | Low     |
| Installation speed    | Slow    | Fast    | Fastest |
| Parallel installations| Limited | Yes     | Yes     |
| Workspace support     | Limited | Good    | Best    |
| Offline mode          | Limited | Good    | Good    |
| Security              | Good    | Better  | Better  |

## 📚 Resources

- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Vite Documentation](https://vitejs.dev/guide/)
- [JavaScript MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [ESLint Documentation](https://eslint.org/docs/user-guide/)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
