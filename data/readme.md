
# Data
## dataset5025
This file contains the novel 5025 dataset, with its original and resized version. It also contains the plan to allow for user annotation of the dataset

 - 5025 Dataset
	 - This contains the original images collated from the internet for the dataset
 - 5025 Dataset Resized
	 - This contains the resized images that were use for the experiments
 - Altered Contrast Images
	 - This contains the subset of images that were altered in contrast for the MTCNN experiments
 - Instructions.pdf
	 - This contains instructions on how to manually annotate the dataset
 - labels5025.txt
	 - This is supplementary content describing the labels for the annotation process

## notebooks
Contains supplementary notebooks that were used to process the images and raw data

 - Resize.ipynb
	 - Notebook used to resize every image in the dataset
 - create_annotation_dict.ipynb
	 - Notebook used to put raw ground truth into standard form for the Evaluation notebook

## processed
Contains the JSON annotation files outputted by the algorithms as well as the ground truth annotations in the JSON format

 - json
	 - Contains the results for each algorithm on the original dataset
 - json_resized, along with the ground truth
	 - Contains the results for each algorithm on the resized dataset, along with the ground truth

## raw
Contains the raw CSV data produced when creating the ground truth annotations

