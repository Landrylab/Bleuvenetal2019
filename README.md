# Bleuvenetal2019
Jupyter Notebook used for bar-seq library analysis in Bleuven et al 2019. See the manuscript and the notebook for specific program requirements.

* The raw sequencing files should first be downloaded and put in same directory as the notebook, and then renamed to "A.Dube_Cabsoil_p01_c01.fastq.gz". 

* Calls to trimmomatic and fastqc should are included in the notebook but should be run in the command line if subprocess.check_output() is not used in the notebook cell

* The script processes reads in two batches to avoid completing busting up the RAM capacity of the computer. The notebook ran on a Ubuntu machine with 32gb RAM, use lower memory at your own risk

This directory also contains a notebook that performs Simulations of relative fitness estimates from barcode sequences, which is described below:

Code for simulations in Bleuven et al. in response to reviewers who wondered if the estimates of relative fitness based on relative read counts within a sample were appropriate. We show that this is the case using exponential growth and decay as examples.wth and decay as examples.
