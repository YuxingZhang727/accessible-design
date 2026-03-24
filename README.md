# Accessible Design Workshop

This project is a SvelteKit CRUD demo that has been intentionally seeded with accessibility problems.

## Workshop Goal

Practice finding and fixing common accessibility problems in a web interface, including:

- missing or broken accessible names
- missing image alternative text
- broken ARIA references
- placeholder-only form fields
- duplicate form control IDs
- table headers marked up incorrectly
- skipped heading structure
- empty interactive elements
- low color contrast
- improper keyboard focus order with positive `tabindex`

## Getting Started

### Install

```bash
npm install
```

### Run the app

```bash
npm run dev
```

### Build the app

```bash
npm run build
```

## Using WAVE

1. Start the app locally.
2. Open the page in the browser.
3. Run the WAVE extension or WAVE browser tool.
4. Identify the reported accessibility errors, alerts, and structural issues.
5. Fix the problems in the Svelte files.
6. Re-run WAVE and confirm the issues are resolved.