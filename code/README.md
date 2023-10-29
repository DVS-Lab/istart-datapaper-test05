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
