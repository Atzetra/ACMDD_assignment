# CBR_teaching
Repo for the CBR teaching lab, contains data, images and 

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
Installeer mambaforge via de officiële documentatie.

En maak nu je environement met:
```sh
mamba env create -f environment_mac.yml
```