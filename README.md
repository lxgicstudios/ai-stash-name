# ai-stash-name

[![npm version](https://img.shields.io/npm/v/ai-stash-name.svg)](https://www.npmjs.com/package/ai-stash-name)
[![npm downloads](https://img.shields.io/npm/dm/ai-stash-name.svg)](https://www.npmjs.com/package/ai-stash-name)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-stash-name)](https://github.com/lxgic-studios/ai-stash-name/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Stop naming stashes "WIP" or leaving them unnamed. Get meaningful stash names from your actual changes.

## Install

```bash
npm install -g ai-stash-name
```

## Usage

```bash
npx ai-stash-name
# → Stashed as: refactor auth middleware error handling

npx ai-stash-name --dry-run
# → Suggested name: add user avatar upload endpoint
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-d, --dry-run` - Show the suggested name without actually stashing

## License

MIT


---

Built by [LXGIC Studios](https://github.com/LXGIC-Studios)

🔗 [GitHub](https://github.com/LXGIC-Studios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
