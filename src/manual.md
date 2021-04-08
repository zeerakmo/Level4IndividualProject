
# User manual 

## Viola-Jones.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the 5025 Resized dataset into the "content/" directory
 - Run each cell in notebook

This will result in a JSON file containing the algorithms results. 

## DLIB.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the 5025 Resized dataset into the "content/" directory
 - Run each cell in notebook	

This will result in a JSON file containing the algorithms results. 

## MTCNN.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the 5025 Resized dataset into the "content/dataset/1/" directory
 - Run each cell in notebook	

This will result in a JSON file containing the algorithms results. 

## RetinaFace.ipynb

To run this algorithm:

 - Open the file in Google Collab
 - Upload the 5025 Resized dataset into the "content/" directory
 - Run each cell in notebook	

This will result in a JSON file containing the algorithms results. 

## evaluation.ipynb
To run the evaluation file against the results generated:

 - Upload the 4 JSON files created by running the algorithms in the "content/" directory.
 - Upload the ground truth annotations file from the json_resized folder to the "content/" directory
 - Next upload the 5025 Resized dataset into the "content/dataset/" directory. 
 - Run each cell in the notebook to generate figures and run experiments

## Notes

 - The RetinaFace algorithm will require the runtime to be restarted once after running the first cell to download the correct packages
 - The Resized Dataset must be used as it contains the correct images required for consistent performance across the algorithms
 - Each algorithm will also show the resulting predictions imposed onto each face within its output
 - The Altered Contrast Images contain the images that are used with the MTCNN algorithm to assess if a dataset bias is present
