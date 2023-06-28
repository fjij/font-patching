# Font Patching

Using [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts/tree/master#font-patcher)

## Requirements

### FontForge

```
brew install fontforge
```

### font-patcher

```
wget https://github.com/ryanoasis/nerd-fonts/releases/latest/download/FontPatcher.zip
unzip FontPatcher.zip -d FontPatcher
```

## Conversion

Put input fonts in `./input-fonts/`
Fonts come out in `./output-fonts/`

```
./patch
```
