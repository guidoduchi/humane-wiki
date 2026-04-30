# HUMANE Wiki

Welcome to the public-facing canon and development wiki for **HUMANE**.

This repository exists to help build, verify, and maintain the narrative universe of *HUMANE* without mixing wiki material with the manuscript itself.

> The book is the artifact. This wiki is the living workshop around it.

## Start Here

- [Canon Source of Truth](docs/canon/canon.md)
- [Narrative Development Guide](docs/project/narrative-development.md)
- [Wiki Workflow](docs/project/wiki-workflow.md)
- [Page Template](docs/project/page-template.md)
- [License](LICENSE.md)

## Repository Purpose

This wiki is for:

- canon rules,
- timeline tracking,
- character profiles,
- cultural/worldbuilding notes,
- fictional systems,
- chapter continuity support,
- project collaboration,
- narrative development decisions.

The actual manuscript prose belongs in the separate manuscript repository.

## GitHub Pages

This repository is prepared to run as a GitHub Pages single-page wiki using Docsify.

After GitHub Pages is enabled, the expected project site URL will be:

```text
https://guidoduchi.github.io/humane-wiki/
```

## Local Preview

You can preview the wiki locally with any static file server.

Using Python:

```bash
python -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

Using Docsify CLI:

```bash
npm i docsify-cli -g
docsify serve .
```

## License

This repository is published for viewing and reference only. The intellectual material of **HUMANE** remains reserved by Guido Duchi.

See [LICENSE.md](LICENSE.md).
