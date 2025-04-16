# cs4220_2_kmer

RANDOM FOREST MODELS 2, 4, AND GROUPINGS WONT UPLOAD


getgroupings_pathocommensal: notebook that creates the groupings for second layer
groups8.csv: csv that contains the groupings, used in the other files getgroupings doesn't have to be ran.
training_models_RF: where the trained happens! go here if joblib is not working, using train_raw_reads
notrain_findingthreshold: used the trained, just iterated through different thresholds to find the ideal

final_input/output: use this one! insert the file path in the cell with the CS4220 dataset. Make sure to have the same paths/edit the paths in the code. It's easiest if the paths for files look like the example jupyter notebook, plus with the files from this github in the same folder, NOT separated in its own folder. 

Input data should go through class CS4220 and become a dataframe in later cells. 8-mers are used so be sure to have that file to create the canonical k-mer dictionary.
