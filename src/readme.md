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

 - Open evaluation file and upload files into the structure described in the file.
	 - These files have all been pre-created and can be taken from the [JSON Resized folder](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/processed/json_resized). This contains the algorithms results on the [5025 resized dataset](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/dataset5025/5025%20Dataset%20Resized).

To run the algorithms and evalute your own results
 - Open the 4 algorithms implementations in Google Collab
 - Run through each algorithms notebook using the file structure described at the top of each notebook
	 - This will involve uploading the [5025 resized dataset](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/dataset5025/5025%20Dataset%20Resized)  
	 - Running the detectors and predictors
	 - Outputting the resulting coordinates in JSON files
 - Open the evaluation notebook in Google Collab and follow the file structure described at the top of the notebook	
	 - This will involve uploading the 4 JSON files which contain the results of the algorithms as well, as the [ground truth coordinate file](https://github.com/zeerakmo/Level4IndividualProject/blob/master/data/processed/json_resized/faces_annotated_resized.json)
 - Run through the notebook to generate each figure and experiment.

For more detailed instructions on how to run the notebooks look towards the [manual.md](https://github.com/zeerakmo/Level4IndividualProject/blob/master/src/manual.md) file.
