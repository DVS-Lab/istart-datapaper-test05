All custom code goes into this directory. All scripts should be written such
that they can be executed from the root of the dataset, and are only using
relative paths for portability.

convert2bids_ugdg.m: To generate tsv files in the BIDS directory for UGDG, use convert2bids_ugdg.m
This code extracts the information needed to generate three column  files for UGDG. 
Open Matlab and hit run to make the TSV files.

run_convertSharedReward2BIDSevents.m: To generate tsv files in the BIDS directory for SharedReward task, open run_convertSharedReward2BIDSevents.m in MATLAB from the code directory.
Once in MATLAB, hit run to make the TSV files.
This code is a wrapper to execute the convertSharedReward2BIDSevents.m base script for all subjects with behavioral data from the 59 included in this data set.
The script extracts the information needed to generate three column  files for Shared Reward.

gen_phentoypes.py: To generate phenotype files in the BIDS directory for all measures, run gen_phenotypes.py in the code directory. 
This code converts the .txt files within sourcedata/redcap/ to BIDS compliant phenotype files. Subjects of interest can be defined withtin the usable_subs.txt file, which comes standard with the 59 subjects who have brain data. 
Command: python gen_phenotypes.py