# neuropixel analysis

This folder contains the code used for spike sorting analysis of neuropixel recordings.

Folder organization

1) neuropixel_analysis

	a) real_npx_data.ipynb --> file used for data from implanted mouse (noisy data; low quality recordings)
	
	b) final_npx_pipeline_ephys_test_data.ipynb --> file used for example Neuropixel 2.0 code (for setting up the initial pipeline)
	
## File organization

Important variables to note are shown in **bold**. 

### real_npx_data.ipynb 

0) Set up 

	a) imports
	
	b) **define "DATA_DIR" ** to set directory path for reading/saving data
	
1) Read recording

	a) ** "recording_data_index"  ** is used to identify which recording we are interested in 
	
2) Preprocessing
	
3) Check noise level

4) Detect and localize peaks

5) Check for drift

6) Run spike sorter

7) Create sorting analyzer + compute postprocessing and metrics

8) Export to Phy (for manual curation) 

### final_npx_pipeline_ephys_test_data.ipynb 

0) Set up 

	a) imports
	
	b) **define "DATA_DIR" ** to set directory path for reading/saving data
	
1) Read recording
	
2) Preprocessing
	
3) Check noise level

4) Detect and localize peaks

5) Check for drift

6) Run spike sorter

7) Create sorting analyzer + compute postprocessing and metrics

8) Export to Phy (for manual curation) 


*For any questions, feel free to contact ej24@ic.ac.uk
	