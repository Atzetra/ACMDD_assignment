# CBR_teaching
Repo for the CBR teaching lab, contains data, images and 

# Setup mamba environement
Kopiëer plak dit gewoon:
```sh
curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-$(uname)-$(uname -m).sh"
bash Mambaforge-$(uname)-$(uname -m).sh
mamba init bash
```

En maak daarna de environement met:
```sh
mamba env create -f environment.yml
```