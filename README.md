# neomutt_config

Configuration for neomutt mail client

Config should be in `~./config/neomutt`

# Prerequisites

Make sure the following are installed:

- `w3m`

```shell
brew install w3m
```

- `zathura`

```shell
brew tap zegervdv/zathura
brew install zathura

brew install zathura-pdf-mupdf
mkdir -p $(brew --prefix zathura)/lib/zathura
ln -s $(brew --prefix zathura-pdf-mupdf)/libpdf-mupdf.dylib $(brew --prefix zathura)/lib/zathura/libpdf-mupdf.dylib
```
