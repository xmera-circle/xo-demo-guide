# xmera Omnia Demo Guide

Developer project of xmera Omnia Demo Guide

![xmera Omnia Demo Guide Version](https://img.shields.io/badge/xmera_Omnia_Demo_Guide-1.0.3-red) ![xmera Omnia Version](https://img.shields.io/badge/xmera_Omnia-v3.7.x-blue) ![Language Support](https://img.shields.io/badge/Languages-de-green) ![Version Stage](https://img.shields.io/badge/Stage-release-important)

The xmera Omnia Demo Guide is written in AsciiDoc and convertible into HTML by Antora or converitble into a pdf file.

---

## Installation

The documentation is based on AsciiDoc. The adoc-files are converted to a HTML documentation by Antora and to a PDF document by Asciidoctor PDF.

So you need to install:

- [Antora](https://docs.antora.org/antora/latest/install-and-run-quickstart/) and
- [Antora Lunr Extension](https://docs.antora.org/antora/latest/extend/supported-components/#component-matrix)
- [Asciidoctor PDF](https://asciidoctor.org/docs/asciidoctor-pdf/#install-the-published-gem)

For doing so, make sure you run the latest Node.js LTS version:

    node --version
    v18.12.1

Follow the [instructions for Linux](https://docs.antora.org/antora/latest/install/linux-requirements/#upgrade-node) in order to upgrade to the latest LTS version of node.

Install all dependencies of this project by

    npm install

## Create xmera Omnia Demo Guide via Makefile

Create the Antora HTML pages and start the guide with Firefox:

    make html_browser

Create the pages without starting the browser:

    make html

Create the pdf document and start the document in the document reader:

    make pdf

**NOTE** The PDF Creator is not working right now!

## Changelog

All notable changes to this project will be reported in the [changelog](https://circle.xmera.de/projects/xmera-omnia-guide/repository/xo_guide/revisions/develop/entry//CHANGELOG.md).

## License

xmera Omnia Demo Guide © 2022 by [xmera Solutions GmbH](https://xmera.de) is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en).
