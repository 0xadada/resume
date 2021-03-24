## Requirements

- Pandoc
- Prince XML
- Computer Modern typeface

on macOS:

```bash
# install Pandoc and libs
brew install pandoc
# install fonts
brew install --cask font-computer-modern
# install Prince XML
# brew install --cask --no-quarantine prince
```

# Generating Resume

```bash
# build all formats
pandoc -d config/html
pandoc -d config/pdf
```
