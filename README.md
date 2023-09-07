# shifting-fitness-landscapes
Analysis code for manuscript titled "Competition-driven eco-evolutionary feedback reshapes bacteriophage lambda’s fitness landscape and enables speciation"

All the analyses are explained and performed in the jupyter notebook `analysis.ipynb` using the conda environment specified by `notebookenv.yml`.
For example, create the environment with `conda env create -f noteboookenv.yml` and activate the environment with `conda activate notebookenv` and start jupyter notebook with `jupyter notebook`. 

The exact versions of all software packages used in the analysis are provided in `softwareversions.txt`, as generated by `conda list`. The analysis has not been tested on other versions of these packages. There is no required non-standard hardware. 

Typical install time should not be longer than several minutes. Downloading FASTQ files can take several hours on a standard personal computer with standard internet connection. Running the entire analysis pipeline in the notebook can take several hours. Intermediate data files at various stages of the analyses are included so that individual steps in the analysis can be run without starting from the very beginning, if desired. All expected output can be found in `/output-notebook`. 

