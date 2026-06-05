# MipMap Desktop Documentation

This is the MipMap Desktop documentation site built with VitePress, with multi-language support and local search.

[View the online documentation](https://docs.mipmap3d.com/desktop)

## Install and Run

### Install Node.js

Before working on this documentation project, install Node.js first. Visit the [Node.js official website](https://nodejs.org/en/download) and install the LTS version.

### Install Project Dependencies

Open a Windows terminal and run the following command to install `yarn`:

```bash
npm install -g yarn
```

Install all required dependencies in the project root directory:

```bash
yarn
```

When you need to update the docs, run the command below to start the development server:

```bash
yarn dev
```

After the development server starts, open port 4002 in your browser to preview the docs. Any content changes in the editor will be reflected in real time.

## Build and Deploy

After editing is complete, run the following command to generate the deployment package:

```bash
yarn build
```

After the build is finished, deploy the `build/` directory to your hosting service.

## Export PDF

Before exporting PDFs, install [Pandoc](https://pandoc.org/installing.html) on your machine. Download the latest installer and follow the installation instructions.

By default, `xelatex` is used as the PDF engine. On Windows, installing MiKTeX or TeX Live is recommended. You can download MiKTeX from the [official MiKTeX website](https://miktex.org/download).

After installing the required tools above, use the following command to export documents as PDF. The `--lang` parameter specifies which language version to export.

```bash
yarn export:pdf -- --lang=fr
```

Common commands:

```bash
# Export English documentation
yarn export:pdf:en

# Export Chinese documentation
yarn export:pdf:zh
```

Optional parameters:

```bash
npm run export:pdf -- --lang=zh-Hans --engine=xelatex
```

Exported files are located in `build/pdf/`, with filenames like `mipmap-desktop-docs-cn.pdf`.
