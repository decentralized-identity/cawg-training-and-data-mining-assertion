# Creator Assertions Working Group :: Training and Data Mining Assertion

This repository contains the source material for the current working draft of the [Creator Assertions Working Group](https://cawg.io/)'s training and data mining assertion. A rendered version of this specification can be found [here](https://cawg.io/training-and-data-mining/).

## Governance

This specification is subject to:

* The W3C Patent Policy (2004) as described in the [license.md](./license.md) file.
* The DIF [Code of Conduct](https://bit.ly/DIF_code_of_conduct).
* The DIF [CAWG Charter](https://github.com/decentralized-identity/org/blob/main/Org%20documents/WG%20documents/DIF_CAWG_WG_charter_v1.pdf).
* The DIF [CAWG Operating Addendum](https://github.com/decentralized-identity/org/blob/main/Org%20documents/WG%20documents/DIF_CAWG_WG_Operating_Addendum_v1.pdf).

## Site build process

The site content is built using [Antora](https://antora.org), which takes Asciidoc (.adoc) plain text files and renders them to HTML and other formats.

The primary content of this document is available in [docs/modules/ROOT/pages/index.adoc](https://github.com/decentralized-identity/cawg-training-and-data-mining-assertion/blob/main/docs/modules/ROOT/pages/index.adoc) in this repo.

## Local preview

You can render the site of this content locally if you wish to test the appearance of changes you are making. To do this:

1. Ensure that you have a current version of node.js installed. ([Installers are here.](https://nodejs.org/en/download/))
2. Install Antora and other project dependencies.

```
$ cd (root of this repo)
$ npm install
```

Each time you wish to preview content, run the following:

```
$ npx antora antora-playbook-local.yml
Site generation complete!
Open file:///(root of this repo)/build/site/index.html in a browser to view your site.
```

Antora does not have a live-preview feature, so you will need to re-run this command to ensure that the rendered site reflects any changes you have made.
