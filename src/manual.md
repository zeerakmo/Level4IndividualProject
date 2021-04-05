
# User manual 

## Viola-Jones.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the [5025 dataset](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/dataset5025/5025%20Dataset%20Resized) into the "content/" directory
 - Run each cell in notebook

This will result in a JSON file containing the algorithms results. 

## DLIB.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the [5025 dataset](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/dataset5025/5025%20Dataset%20Resized) into the "content/" directory
 - Run each cell in notebook	

This will result in a JSON file containing the algorithms results. 

## MTCNN.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the [5025 dataset](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/dataset5025/5025%20Dataset%20Resized) into the "content/dataset/1/" directory
 - Run each cell in notebook	

This will result in a JSON file containing the algorithms results. 

## RetinaFace.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the [5025 dataset](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/dataset5025/5025%20Dataset%20Resized) into the "content/" directory
 - Run each cell in notebook	

This will result in a JSON file containing the algorithms results. 

## evaluation.ipynb
To run the evaluation file against the results generated:

 - take the JSON files outputted by the algorithms and [ground truth
   coordinate file (https://github.com/zeerakmo/Level4IndividualProject/blob/master/data/processed/json_resized/faces_annotated_resized.json).
 - Upload these 5 JSON files in the "content/" directory.
 - Next upload the [5025 dataset](https://github.com/zeerakmo/Level4IndividualProject/tree/master/data/dataset5025/5025%20Dataset%20Resized) into the "content/dataset/" directory. 
 - Run each cell in the notebook to generate figures and run experiments


## Notes

 - The RetinaFace algorithm will require the runtime to be restarted once after running the first cell to download the correct packages
 - The Resized Dataset must be used as it contains the correct images required for consistent performance across the algorithms
 - Each algorithm will also show the resulting predictions imposed onto each face within its output
