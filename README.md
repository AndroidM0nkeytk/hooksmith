# hooksmith

A handful of React hooks I keep copy-pasting between projects

## Highlights

- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization
- Tiny: no dependencies besides React
- useDebounce with leading/trailing options

## Installation

```bash
npm install
npm test
```

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── package.json
```

## License

MIT licensed, see LICENSE.
