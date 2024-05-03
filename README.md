# pax-hpc
PAX HPC


## test locally


### install micromamba

install micromamba https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html
or any other conda/python env

### clone the repo

```bash
git clone git@github.com:pax-hpc/pax-hpc.git
cd pax-hpc
```

### create environment

```bash

micromamba create -n pax-hpc
micromamba activate pax-hpc
micromamba install python  -c conda-forge

python3 -m pip install -r docs/requirements.txt
```


### build the thing locally

```bash
sphinx-build docs build
```
open in the browser or some local server

### do your work

```bash
git checkout -b mycoolbranch

```
do you changes
add them to git with git add


### push the changes

```bash
git commit -m "my cool changes"

git push -u origin mycoolbranch

```

### do a pull request to the main branch with your changes.

### important

This assumes you already added an ssh key to your github profile...



