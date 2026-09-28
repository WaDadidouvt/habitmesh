# habitmesh

Habit tracker grid built with Vue 3 composition API

Small but I use it weekly.

## Install

```bash
npm install
npm run dev
```

## Highlights

- Vite dev setup with hot reload
- Composition API + script setup
- GitHub-style contribution grid per habit
- State persisted to localStorage

## How to use

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── App.vue
│   ├── main.js
│   └── store.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── index.html
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version

## License

MIT - see [LICENSE](LICENSE).
