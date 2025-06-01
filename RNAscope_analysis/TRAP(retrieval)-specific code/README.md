# TRAP(retrieval)-specific code

Folder organization

1) TRAP(retrieval)-specific code
	a) registered --> data exported from QuPath
	b) fig_outputs --> output directory for figures/csv files from code
	c) retrieval_analysis_streamline.ipynb --> main analysis of TRAP(retrieval) data	 (per mouse)
	d) retrieval_all_brains.ipynb --> combining analysis results from each mouse to summarize for all

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

*For any questions, feel free to contact ej24@ic.ac.uk
	