# Readme

The code created for this project was created on the Google collab enviroment. It mainly consists of the 4 face detection algorithms and a single evaluation file used for the experiments and to create the figures.

 - ViolaJones.ipynb
	 - contains the Viola-Jones algorithm implementation
 - DLIB.ipynb
	 - contains the HOG face detector and 68 point landmark predictor implementation
 - MTCNN.ipynb
	 - contains the MTCNN implementation
 - RetinaFace.ipynb
	 - contains the RetinaFace implementation
 - Evaluation.ipynb
	 - aggregates the output of the 4 algorithms
	 - generates figures and runs experiments	
 - manual.md
 	 - contains more detailed instructions

## Instructions


### Requirements

The project was created using the cloud based Python notebook through Google Collab. Each notebook is intended to be used in this environment. Therefore to run any of the notebook files, open them in Google Collab.

### How to run
To run evaluation file on pre-existing results then:

 - Open evaluation file and upload files according to the structure described in the notebook. The files required to upload are the:
	 - 5 annoation files from the json_resized folder
	 - The 5025 resized dataset images from the 5025 Dataset Resized folder
 - Run the cells in the evaluation notebook with these files to generate the results

To run the algorithms and evalute your own results
 - Open the 4 algorithms implementations in Google Collab
 - Run through each algorithms notebook using the file structure described at the top of each notebook, this will involve:
	 - Uploading the 5025 resized dataset  
	 - Running the cells in the notebook
	 - Saving the resulting JSON file that contains the results
 - Open the evaluation notebook in Google Collab and follow the file structure described at the top of the notebook	
	 - This will involve uploading the 4 JSON files created which contain the results of the algorithms as well as the ground truth annotations file from the json_resized folder
 - Run the cells in the evaluation notebook with these files to generate the results

For more detailed instructions on how to run the notebooks look towards the manual.md file.
