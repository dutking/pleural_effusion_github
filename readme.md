# Common information
Chosen library for medical images - [SimpleITK](https://simpleitk.org/about.html)

## Working files
- data_analysis.ipynb - dataset analysis on distribution of labels across number of slices in features
- dataset_features_and_labels_analysis.ipynb - dataset analysis on available features, labels' gaps and outliers (run locally)
- tf_dataset_creation.ipynb - dataset creation functions (currently without tf.data API) (run locally)
- radlogix_du.ipynb - 

## Ideas
1. To shrink dataset to the range of 88-136 slices - DONE
2. Pad images instead of resampling to prevent distortions - DONE
3. Save to tf.tensor to check its size - TO DO

## Issues
1. Bad dataset balance 1 effusion to 6 clean features

## Interesting links
- [What are the differences between DICOM and NIfTI?](https://encord.com/blog/whats-the-difference-between-dicom-and-nifti/)

# TODOs
1. Create tf.dataset using tf.data API
3. Find a way to balance dataset in case of bad results

