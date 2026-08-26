# react-utility-hooks

Small typed hooks: debounce, localStorage, media query, toggle

## What it does

- useDebounce with leading/trailing options
- Tiny: no dependencies besides React
- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe

## Getting started

```bash
npm install
npm test
```

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── config.js
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## Development

```bash
npm install
npm test
```

## License

MIT - see [LICENSE](LICENSE).
