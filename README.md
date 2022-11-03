# ACMDD_assignment (CDK2)
## Team members
- Enzo Sastrokarijo (s1993895)
- Donald van Pinxteren
- Rosalie Drinkwaard

# Setup mamba environement

## Linux

Kopiëer plak dit gewoon:
```sh
curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-$(uname)-$(uname -m).sh"
bash Mambaforge-$(uname)-$(uname -m).sh
mamba init bash
```

En maak daarna de environment met:
```sh
mamba env create -f environment.yml
```
## Mac
**Niet alle packages zijn beschikbaar voor MacOS dus dit is eigenlijk vrij nutteloos.**

Installeer mambaforge via de officiële documentatie.

En maak nu je environment met:
```sh
mamba env create -f environment_mac.yml
```
