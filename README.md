# Calculator

A browser calculator, built as my solution to [The Odin Project's Calculator project](https://www.theodinproject.com/lessons/foundations-calculator).

## Tech stack

- HTML5
- CSS3
- TypeScript, compiled to ES modules with `tsc`

## Getting started

Install dependencies and compile the TypeScript sources:

```bash
npm install
npm run build   # compile src/ into dist/
```

For development, recompile on change:

```bash
npm run watch
```

## Project structure

```text
.
├── index.html        # Page entry point
├── css/
│   ├── index.css     # Stylesheet entry point
│   ├── tokens.css    # Design tokens
│   ├── elements.css  # Default styles for bare HTML elements
│   └── utilities.css # Utility classes for color, typography, box, and layout
├── src/
│   └── index.ts      # TypeScript entry point
├── dist/
├── tsconfig.json
└── package.json
```

## Status

Scaffolded from a hand-authored HTML/CSS/TypeScript starter. The calculator logic and interface have not been implemented yet.

## License

ISC
