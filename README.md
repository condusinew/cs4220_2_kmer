# cs4220_2_kmer

RANDOM FOREST MODELS 2, 4, AND GROUPINGS WONT UPLOAD


getgroupings_pathocommensal: notebook that creates the groupings for second layer
groups8.csv: csv that contains the groupings, used in the other files getgroupings doesn't have to be ran.
training_models_RF: where the trained happens! go here if joblib is not working, using train_raw_reads
notrain_findingthreshold: used the trained, just iterated through different thresholds to find the ideal

final_input/output: use this one! insert the file path in the last cell. We're using the 8-mer profile only. Make sure to have the same paths/edit the paths in the code. It's easiest if the paths for files look like the example jupyter notebook, plus with the files from this github in the same folder, NOT separated in its own folder. 8-mer profile for canonical dict, 8 mer profile of patient, groups8.csv, train_labels.csv, all_species.csv are files that are read

Note that they wouldn't let me upload some models onto Github but GDrive worked: https://drive.google.com/drive/folders/1tU2JoUKg_7KcmJ3v2NtqVOZPTMUv1QhR?usp=sharing for the models missing here (there should be 3 in the drive (2, 4, groups), so 7 models in total including the Github uploaded ones!
