# Docs

This is project to store all the Markdown files and compile them into PDF using Pandoc.

## Installation on Ubuntu

To install Pandoc on Ubuntu, run the following command:

```bash
sudo apt install pandoc
sudo apt install texlive-latex-base texlive-recommended
```

## Usage

To compile the Markdown files into PDF, run the following command:

```bash
pandoc -o out/README.pdf README.md
```
