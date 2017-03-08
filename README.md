# subsetOfBedmap2Data

- This repository contains a compressed subset of the [BEDMAP2](https://www.bas.ac.uk/project/bedmap-2/) data set.
- The compressed file size is ~50MB, and so is an optional part of the [ANITA software](https://github.com/anitaNeutrino).
- The data is *NOT* automatically installed by [anitaBuildTool](https://github.com/anitaNeutrino/anitaBuildTool)
- The data is installed directy to
```bash
${ANITA_UTIL_INSTALL_DIR}/share/anitaCalib
```
- i.e. it does not get redownloaded with each build.

## Recommended way to install ##

Get the latest release of the [anitaEventCorrelator library](https://github.com/anitaNeutrino/anitaEventCorrelator) and run the script downloadBEDMAP2subset.sh.


## Manual install ##

If you're on the ice downloading 50MB will be no fun for anyone.
Copy the data files from someone who already installed them.
Make sure the bedmap2_bin directory is in

```bash
$ANITA_UTIL_INSTALL_DIR/share/anitaCalib
```
