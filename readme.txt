1 Overview of CBCNV
A cluster-based approach for the discovery of copy number variations from next-generation sequencing data.
In order to verify the validity of CBCNV,we use it to detect simulation data and real data compared with 
several existing methods,which proves to be a very effective and reliable tool.
2 Usage
2.1 Operating environment
Our software is running on Linux system.It is developed using R and Python language.The users 
need to install the SAMtools,R and Python to build environment before running the software.
We need to install the R package(readr,PythonInR and cghFLasso) and Python packages(pysam,numpy,numba,pandas,pyod and sklearn)
R version: 3.6.0
Python version: 3.5.2
2.2 Input
The users need to input a reference genome file, case and control samples. 
The reference genome file is a fasta format file.
The case and control samples are bam format file.
2.3 parameter settings
The parameters are saved in the input file.The users can set relevant parameters according to needs and apply 
them to different scenarios.
The structure of the input file includes five rows of data,which represent case sample, control sample, 
bin size, number of neighbors and abnormal weight, respectively.
The values given in the input file are default parameters.
2.4 Run command
sh run.sh
2.5 Output
The output is saved in the result text file.
3 Application
We provide an application example for the user to further use the software.

