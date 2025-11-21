# Biome Config

> Personal Biome configuration --- standardized formatting, linting, and
> editor settings following my preferred setup.

## 🚀 Overview

This repository contains my personal configuration for **Biome**, a fast
and lightweight toolchain that combines formatting and linting for
modern web projects.

The goal is simple: keep my TypeScript/JavaScript projects clean,
consistent, and easy to maintain with minimal setup.

This configuration includes:

-   Formatter rules
-   Linting rules
-   VS Code integration
-   Useful CLI scripts

## 📦 What's Included

-   **`biome.json`** -- Main Biome configuration (formatter + linter)
-   **`.vscode/`** -- VS Code settings for auto-formatting on save
-   **`package.json`** -- Scripts for formatting and linting
-   Lockfiles depending on the package manager (pnpm, npm, etc.)

## 🛠️ How to Use

### 1. Install Biome

    npm install -D -E @biomejs/biome

### 2. Copy the configuration

Bring over `biome.json` and, if desired, the `.vscode` folder.

### 3. Add scripts to your `package.json`

    "scripts": {
      "format": "biome check --write src"
    }

### 4. Run Biome

Format and fix:

    npm run format

### 5. VS Code integration

With the included `.vscode/settings.json`, Biome will:

-   Format on save\
-   Organize imports automatically\
-   Apply lint fixes where possible

## ✨ Highlights

-   Format on Save\
-   Automatic Import Organization\
-   Fix All on Save\
-   Handy script to format all files under `src`
