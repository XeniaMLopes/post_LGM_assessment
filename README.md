# post_LGM_assessment

## Supplementary data
# Strong and lasting impacts of past global warming on baleen whales and their prey


Folders
A. Samples_MtDNA_sequences_information
	This folder contains a .xlm file with the sample ID, mitochondrial DNA sequence, ocean basin and source for each species included included in this study
B. Migrate-BaleenWhale_Input
	For each baleen whale species, the input file for MIGRATE-N and the paramter file of one of the replicates is presented
	1. Input file
	Contain information
	Line 1. Total number of populations and loci
	Line 2. Number of base pairs in the mtDNA sequences
	Line 3. Number of sequences for population 1
	Line 4-?. MtDNA sequences per sample individual
	Line ?. Number of sequences for population 2

	2. Parfile
	Parameters employed to for the specific MCMC estimate in MIGRATE-N. The parameter file of one of the replicates is included. 
	The other replicates varied only in the nubmer of random seed.

C. Migrate-Prey_Input
	Same information as Folder A but for the prey species 
	
D. Migrate-ComparisonMtgenes_Input
	Same information as Folder A but for different mtDNA genes and species, employed for the comparison of temporal trends of different mtDNA genes.

E. Stariway-BaleenWhales_Input
	For each of the baleen whale species, the files named "blueprint" are used as both the input and the configuration file for running 
	the "STAIRWAY PLOT v2". The files employed for the plot with minimum coverage of 2x and 10x are included. 
	It contains the total number of sites, including the monomorphic sites (line 5) and the folded site frequency spectrum (line 7).
	Additional configuration information are also included, like the used mutation rate (line 16) and generation time (line 17).

F. Correlation
	The cvs files with the data points employed to estimate the pearson correlation every 1,000, 2,000, and 5,000 years.

G. Migrate-BaleenWhale_Output
	Output parameters and skyline data from MIGRATE-N for each baleen whale species
