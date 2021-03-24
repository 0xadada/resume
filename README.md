# Resume

A simple resume.

## Requirements

- Pandoc
- Prince XML
- Computer Modern typeface

on macOS:

```bash
# install Pandoc and libs
brew install pandoc
# install Prince XML
brew install --cask --no-quarantine prince
# install font
brew install --cask font-computer-modern
```

## Generating Resume

```bash
# build all formats
pandoc -d config/html
pandoc -d config/pdf
```
