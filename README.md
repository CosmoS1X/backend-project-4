# Page Loader

[![Checks](https://github.com/CosmoS1X/page-loader/actions/workflows/node.js.yml/badge.svg)](https://github.com/CosmoS1X/page-loader/actions/workflows/node.js.yml)
[![Maintainability](https://qlty.sh/gh/CosmoS1X/projects/page-loader/maintainability.svg)](https://qlty.sh/gh/CosmoS1X/projects/page-loader)
[![Code Coverage](https://qlty.sh/gh/CosmoS1X/projects/page-loader/coverage.svg)](https://qlty.sh/gh/CosmoS1X/projects/page-loader)

## Description

**Page Loader** is an application for downloading web pages from the network using a command line interface. The application allows you to download web pages with resources and save them locally.

### Main features:

- **Downloading web pages:** The application allows you to download web pages from the network using HTTP and HTTPS protocols.

- **Saving pages:** Downloaded pages are saved as HTML files on the local disk.

- **Saving resources:** Downloaded page resources (such as images, CSS, JS, JSON etc.) are saved in the `<page-name>_files` directory.

- **Checking the download status:** The application provides the ability to track the download status and show a message about the successful completion of the process or its failure.

## Requirements

- Node 18.x
- Make

## Installation

```bash
git clone git@github.com:CosmoS1X/page-loader.git
cd page-loader
make install
```

## Usage

You can use the following command to download the web page `https://example.com`:

```bash
page-loader https://example.com
```

This command will load the page from `https://example.com` and save it in the current directory.

Use the flag `-o` or `--output` to save to a specific directory. 

Use the flag `-h` or `--help` to show options.

## Demo

[![asciicast](https://asciinema.org/a/m487DSblM000lpuxYXwYSPnzF.svg)](https://asciinema.org/a/m487DSblM000lpuxYXwYSPnzF)
