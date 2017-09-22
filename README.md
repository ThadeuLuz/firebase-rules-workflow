# firebase-rules-workflow

An example project of a workflow for firebase-rules with [bolt](https://github.com/firebase/bolt) and [targaryen](https://github.com/goldibex/targaryen).

This was used on a presentation on [Maceió DevFest 2017](https://devfest.gdgmaceio.org/)

Task | Description
---|---
`build` | compiles `src/rules.bolt` to `dist/rules.json`
`test` | uses targaryen to tests `dist/rules.json` with `src/rules.spec.js`
`test:watch` | Watches `rules.bolt` and `rules.spec.json` for changes and runst `test`
