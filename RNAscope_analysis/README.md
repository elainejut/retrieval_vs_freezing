# RNAscope analysis

This folder contains the code used for data analysis of positive cell detection results from QuPath.

Folder organization

1) TRAP(retrieval)-specific code
	a) registered --> data exported from QuPath
	b) fig_outputs --> output directory for figures/csv files from code
	c) retrieval_analysis_streamline.ipynb --> main analysis of TRAP(retrieval) data	 (per mouse)
	d) retrieval_all_brains.ipynb --> combining analysis results from each mouse to summarize for all
2) TRAP(freezing)-specific code
	a) registered --> data exported from QuPath
	b) fig_outputs --> output directory for figures/csv files from code
	c) freezing_analysis_streamline.ipynb --> main analysis of TRAP(freezing) data	 (per mouse)
	d) freezing_all_brains.ipynb --> combining analysis results from each mouse to summarize for all; includes TRAP(freezing)_vs_cfos(retrieval); also includes TRAP(retrieval)_vs_TRAP(freezing)

## File organization

Important variables to note are shown in **bold**. 

### TRAP(retrieval)-specific file organization

#### retrieval_analysis_streamline.ipynb

1) Set up 
	a) imports
	b) **define "brain_id" =  [brain id of interest]** (ie. JKAY11.1g)
2) Analysis
	a) main analysis --> puts data into corresponding dataframes based on what we're interested in
3) Plot results
	a) individual brain slices (anterior to posterior)
	b) averaged brain slices
4) Enrichment ratios
	a) individual brain slices (anterior to posterior)
	b) averaged brain slices

#### retrieval_all_brains.ipynb

1) Enrichment ratios (aligned per slice)
2) Vgat_alsoTRAP/Vglut_alsoTRAP

### TRAP(freezing)-specific file organization

#### freezing_analysis_streamline.ipynb

1) Set up 
	a) imports
	b) **define "brain_id" =  [brain id of interest]** (ie. JKAY22.3g)
2) Analysis
	a) main analysis --> puts data into corresponding dataframes based on what we're interested in
3) Plot results
	a) individual brain slices (anterior to posterior)
	b) averaged brain slices
4) Enrichment ratios
	a) individual brain slices (anterior to posterior)
	b) averaged brain slices
5) TRAP(freezing) vs cfos(retrieval) comparison

#### freezing_all_brains.ipynb

1) Enrichment ratios (aligned per slice)
2) Vgat_alsoTRAP/Vglut_alsoTRAP
	a) freezing only data
	b) **combining with TRAP(retrieval) data to create graph with data from both experiments**
3) TRAP vs cfos 

*For any questions, feel free to contact ej24@ic.ac.uk
	