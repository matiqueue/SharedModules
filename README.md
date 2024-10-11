
# Shared Modules

This repository demonstrates how to set up a `PNPM` workspace for sharing node_modules across multiple web projects in the `web-projects/` directory. It allows efficient dependency management for `Vite`, `Create React App`, and other JavaScript/TypeScript projects, saving disk space and speeding up installs.


## Installation

To set up the project, execute the following commands in PowerShell:

```bash
  mkdir ~/web-projects
  cd ~/web-projects
```

Then we clone the repo:

```bash
  git clone https://github.com/matiqueue/SharedModules.git .
```

Finally, we install pnpm:

```bash
  npm install -g pnpm
  pnpm install
```

## Usage

To create a project (for example, in Vite), type the following commands in the `~/web-projects` folder:

```bash
  pnpm create vite <nazwa-projektu>
  cd <nazwa-projektu>
```

Module Installation:

```bash
  pnpm install
```

To start the project, in the project folder type the following command:

```bash
  npm run dev
```
## Information

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) 