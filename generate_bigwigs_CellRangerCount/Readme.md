# Generate bigwigs for cell ranger count output   

From the output files of cell ranger count, it splits the bam file (possorted) in *N* sub-bamfiles for each *N* original cluster (each cluster has several barcodes). Then intersect that with the peaks (bed) and creates a bigwig for each cluster to see the coverage per track.  

## Requirements before running  

1) Install [Conda] (https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)  

2) Get the conda environment:   
* this is the first level of bullet points, made up of <space><space>*<space>