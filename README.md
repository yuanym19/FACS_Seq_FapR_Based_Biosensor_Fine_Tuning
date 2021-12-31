# FACS_seq_FapR_Based_Biosensor_Fine_Tuning
Scripts for 'Encoding genetic circuits with DNA barcodes paves the way for machine learning-assisted metabolite biosensor response curve profiling in yeast'

These repositories contain the scripts used for the analysis of FACS-seq and relevant figures. Data analysis was performed by Python 3. The following packages were used: pandas v0.24.2, matplotlib v3.0.3, numpy v1.16.5, scipy v1.3.1, scikit-learn v0.21.2, sys v3.7.4. Some raw data files are very large and users should download them from NCBI and then run the notebooks.

read_counts.ipynb is used to count the total read counts for each concentration, the tables in the folder 'Sequence_Result1' and 'Sequence_Result2' are used. The output results are saved in the folder 'ExportResults'.

Sorting_Analysis_boundary.ipynb is used to analyze the sorting boundary. For this script, there are too many input files to upload in one folder, so they are splited into the folders named 'FACS sorting file0'~'FACS sorting file8' and uploaded. Please put this script and these input files into one directory to run. The output data has been saved in the folder 'FACS_sorting_Data'.

FACS_seq Data Process.ipynb is used to analyze the FACS_seq NGS data. Characterized_results_0708.xlsx and the files in the folder 'Bin_info' are used in this script. The output results are saved in the folder 'ExportResults'.

Machine Learning from FACS_seq_Data.ipynb is used for machine learning in this work. related files are in the folder 'Machine_learning' and 'ExportResults'.
