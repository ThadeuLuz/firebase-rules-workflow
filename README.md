# firebase-rules-workflow

An example project of a workflow for firebase-rules with bolt, targaryen and nodemon.

Task | Description
---|---
`build` | compiles `src/rules.bolt` to `dist/rules.json`
`test` | uses targaryen to tests `dist/rules.json` with `src/rules.spec.js`
`test:watch` | Watches `rules.bolt` and `rules.spec.json` for changes and runst `test`
