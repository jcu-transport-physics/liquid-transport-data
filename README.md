# Liquid-Transport-Data

This repository hosts the electron-liquid swarm transport data collected for the
paper:
```
G. J. Boyle, N. A. Garland, D. L. Muccignat, I. Simonovic, D. Boˇsnjakovi, S. Dujko and R. D. White, Review of the experimental and theoretical landscape of electron transport in noble liquids
```
The data was collected for comparison purposes and to enable researchers to easily utilise the data in a standardised form.

If you wish to use any of the data in this database, please ensure that the appropriate original source is referenced along with the reference for this version of the database. The original reference can be found at the top of each data file.

We have made our best attempt at ensuring that the data is accurate and true to the source material but errors may be present. We encourage anyone to fix these errors by contributing or creating an issue so that we may correct it. We have included all the files neccesary to load the digitisation in [webplotdigitizer](https://apps.automeris.io/wpd4/) so that the data can be checked and corrected at any time.

If there are any missing data sources that should be included, we welcome contributions.

## How to contribute

1. Create a [fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) of the repository.
2. Create a [git branch](https://www.atlassian.com/git/tutorials/using-branches) with a title like "JDoe2015" in line with the first author and year.
4. Create a new folder that contains:

```
JDoe2015/JDoe2015.csv
```

where the csv follows the template:

```
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
Reference: J. Doe, 2015, An example title
DOI: 10.123412.1241
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

SPECIES: e / Xe
Density: 1e23 m^-3
Pressure: 1 Torr
Temperature: 293 K
Phase: Liquid
Field: NaN
PROCESS: Characteristic energy (DT/mu)
UPDATED: 2012-11-13 13:32:53
COLUMNS: Reduced electric field (Td) | Energy (eV)
-----------------------------
 7.648000e-2,1.718160e+0
 1.017500e-1,2.241050e+0
 1.282300e-1,2.568680e+0
 1.927400e-1,3.369870e+0
 2.586300e-1,4.032510e+0
 3.862400e-1,4.893200e+0
 5.143600e-1,5.390100e+0
 6.419700e-1,6.089800e+0
 7.681600e-1,6.321710e+0
-----------------------------
```

4. Retrieve the data using [webplotdigitiser](https://automeris.io/), or other software. Include the project data to replicate the digitisation where possible.
5. Fill out the template file according to the paper, include all appropriate references.
7. Commit the files to the git branch
8. Mark the pull request ready for review

## Contributors

Dale Muccignat, Nathan Garland, Gregory Boyle

## How to cite

Citation information can be found at DOI: 10.5281/zenodo.15233314
