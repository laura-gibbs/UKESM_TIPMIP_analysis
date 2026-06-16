# UKESM_TIPMIP_analysis

Accompanying code and data for the manuscript:

> Zero Emissions Commitment depends on warming level

This repository contains the analysis notebook and processed datasets used to reproduce the figures and results presented in the manuscript.

## Repository contents

```text
EBM_files/
    Input files used for energy balance model calculations

data_global_stats/
    Processed global-mean data from UKESM used in the analysis

UKESM_ZEC_analysis.ipynb
    Main analysis notebook reproducing manuscript figures
```

## Running the analysis

Launch Jupyter and run:

```bash
jupyter notebook UKESM_ZEC_analysis.ipynb
```

The notebook reproduces the manuscript figures directly from the processed datasets included in this repository.

## Original simulation output

Selected CMORised output from the UKESM TIPMIP ensemble can be publicly accessed via JASMIN:

https://gws-access.jasmin.ac.uk/public/ukesm/TerraFIRMA

The full simulation outputs are archived at the UK Met Office and are available for research purposes through the JASMIN platform (www.jasmin.ac.uk) maintained by the Centre for Environmental Data Analysis (CEDA); for details please contact UM_collaboration@metoffice.gov.uk, referencing this paper.

## System details

The code was developed and tested using:
- Python 3.12.13
- Iris 3.15.0
- NumPy 2.3.5
- Matplotlib 3.10.9

Operation system used:
- Red Hat Enterprise Linux 9.7 (Plow)

No non-standard hardware is required.

### Expected run time
Less than 1 minute on a standard desktop.
