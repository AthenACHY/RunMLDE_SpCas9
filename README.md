# "Machine learning-assisted engineering of activity-enhanced Staphylococcus aureus Cas9’s KKH variant for genome editing"
This repository contains the analysis source code used running MLDE for **SpCas9** in the paper "Machine learning-assisted engineering of activity-enhanced Staphylococcus aureus Cas9’s KKH variant for genome editing" by Dawn Thean et al.

## Prerequisite
Please go to the MLDE github page [https://github.com/fhalab/MLDE](https://github.com/fhalab/MLDE) to install and run MLDE according to user's instruction.
Also R 4.0.2 is used for running the R code with packages: tidyverse, ggplot2, seqnir, readxl, and stringdist.

## Overview
Here is the step by step break down of how to use the codes.


**Step 1:** use prepare_MLDE_fasta_file_for_encoding.R to generate the customized fasta file for MLDE encoding.

**Step 2:** use prepare_MLDE_fitness_input.R to generate customized fitness file for MLDE fitness prediction.

**Step 3:** Run_MLDE.sh and the parameter files in ./RUN MLDE to run MLDE.

**Step 4:** Use Organise_MLDE_output.sh to prepare the MLDE results for analyses in R.

**Step 5:** Use Evaluate_MLDE_Results.R to perform analyses and plot figures.
