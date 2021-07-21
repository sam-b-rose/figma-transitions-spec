# Transitions Spec

Generate specs to describe and visualized transitions.

The main plugin code is in `src/code.ts`. The HTML for the UI is in
`src/ui.html`, while the embedded JavaScript is in `src/ui.tsx`.

These are compiled to files in `dist/`, which are what Figma will use to run
your plugin.

To build:

```shell
npm install
npm run build
```

To develop in watch mode:

```shell
npm run dev
```
