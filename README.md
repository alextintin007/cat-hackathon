# DPOA work in CAT hackathon

Working material for DPOA in Common Analysis Tools (CAT) hackathon (April 2023)

## Repository structure

### data
An example PF-enriched NanoAOD file `doubleeg_nanoaod_eg.root`.
- 10 events
- parent file: 00387F48-342F-E611-AB5D-0CC47A4D76AC.root from `root://eospublic.cern.ch//eos/opendata/cms/Run2015D/DoubleEG/MINIAOD/08Jun2016-v1/10000/00387F48-342F-E611-AB5D-0CC47A4D76AC.root`

### production

The code area for the production step in the workflow. 
Subdirectory: pfnano

### analysis

The code area for the analysis step in the workflow. 
Subdirectories: rdataframe and coffea

## Contributing

Get the code:

```
git clone git@github.com:cms-dpoa/cat-hackathon.git
cd cat-hackathon
```

Develop the code in the respective subdirectories
- `analysis/rdataframe`
- `analysis/coffea`
- `production/pfnano`

Make your code development (including the documentation of the `README.md` file in the directory!), create a development branch (start the branch name with your name) and push your branch to the repository, and make a pull request in the GitHub web interface. Use `analysis-rdf:`, `analysis-coffea:` or `production-pfnano` in your commit messages.

```
git checkout -b <yourname-branchname>
git add <files to be added>
git commit -m "dir-subdir: short description"
git push origin <yourname-branchname>
```

Once your new code is pushed and merged to the main branch, for the next developments, remember to start your next development branch from the `main` branch and pull the updates to your local area.

```
git checkout main
git pull
git checkout -b <yourname-nextbranchname>
```




