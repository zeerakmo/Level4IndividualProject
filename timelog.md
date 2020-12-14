# Timelog

* The Sensitivity of Facial Analysis Algorithms to Race and Gender
* Mohammed Zeerak
* 2314940z
* Nicolas Pugeault

## Guidance

* This file contains the time log for your project. It will be submitted along with your final dissertation.
* **YOU MUST KEEP THIS UP TO DATE AND UNDER VERSION CONTROL.**
* This timelog should be filled out honestly, regularly (daily) and accurately. It is for *your* benefit.
* Follow the structure provided, grouping time by weeks.  Quantise time to the half hour.

## Week 1

### 30 Sept 2020

* *0.5 hours* 
  *  Had a meeting with advisor on project scope
* *7 hour* 
  *  Researched the different face detection algorithms avaliable
  *  Installed and played with a MTCNN algorithm
  *  Installed a python library built ontop of DLIB
  *  Started taking notes for literature review
* *0.5 hour* 
  *  Set up an empty github repo

## 01 Oct 2020

* *3 hour* 
  *  Researched more papers and completed notes for my literature review's first draft
  *  Researched into a bias existing within Datasets
  *  Looked at HOG, HAAR, MTCNN and Fast R-CNN as potential algorithms to test
           
## 03 Nov 2020

* *3 hour* 
  *  Completed literature reviews conclusion and learned about the cascading structure present in the algorithms

## 06 Nov 2020

* *2 hour* 
  *  Completed literature review references and citations to other papers

## 07 Nov 2020

* *1 hour* 
  *  Had a meeting with supervisor and showed the progress I made
  *  Went over the MTCNN paper to get a better understanding with supervisor
           
* *7 hour* 
  *  Set up a pytorch implementation of MTCNN on the Google collab enviroment
  *  Set up an implementaion of the Viola Jones algorithm on the Google Collab enviroment
  *  Carried out more research on future algorithms
         

## 11 Oct 2020

* *4 hour* 
  *  Researched about the R-CNN family of algorithms
  *  Looked into single stage algorithms like YOLO and SSD
  *  Looked into diff
  *  Researched different methods of training the models that are used for object detection or face detection
           
## 13 Oct 2020

* *4 hour* 
  *  Researched how I could train my own models and why MTCNN might allow for this
  *  Set up a 68 point facial landmark algortihm on Google collab that uses the DLIB detector
  *  Now I have 3 algorithms avaliable
           
           
## 14 Oct 2020

* *0.5 hour* 
  *  Had a meeting with advisor about progress, discussed researching more algortihms 
* *7.5 hour* 
  *  Set up a Retina Face implementation on Google Collab as my 4th algorithm
  *  Downloaded mendeley to manage my literature
  *  Changed literature review format and referencing style now using mendeley
  *  Added a section of R-CNN and FaceNet and a feasibility section to literature review
  *  Compiled V1 of the literature review
             
             
## 21 Oct 2020

* *0.5 hour* 
  *  Had a meeting with advisor about progress, agreed upon the 4 algorithms I had chosen
* *5.5 hour* 
  *  Moved literature review from word to Latex and added graphics
  *  Thought of some experiments I could run and wrote these down
                          
## 28 Oct 2020

* *0.5 hour* 
  *  Had a meeting with advisor and went over the RetinaFace paper to better understand the pyramid faeture concept
* *7.5 hour* 
  *  Collated a dataset called the 5025 dataset, its made up of creative common photos of represented and under represented people.
  *  Manually annoted the dataset to act as ground truth for my experiments
  *  Created instructions for others to generate ground truth for me
  *  Created a jupyter noteboox to create a dictionary in python that represents the grounf truth values
             
             
## 04 Nov 2020

* *7 hour* 
  *  Created methods in each algorithm to extract the data as a dictionary which I could use for comparisons
  *  Executed the 4 algorithms on the 5025 dataset and exported the resulting dictionaries to an evaluation notebook
  *  Created functions to calculate the error difference between my ground truth and the algorithms
  *  Created a function to average this error across the datasets sub groups
           
           
                       
## 05 Nov 2020

* *1.5 hour* 
  *  Created a method to display the algorthims results overlayed onto the same face (excluding the viola jones algorithm)
  *  Fixed the Retina Face and MTCNN dictionary not storing the correct values for the bounding box
             
             
## 06 Nov 2020

* *1 hour* 
  *  Had a meeting with supervisor and showed the major progress I had made since last time
  *  Talked about normalising the data values using the distance between the eyes
  *  Showed the current stage of my literature review 
           
## 11 Nov 2020

* *0.5 hour* 
  *  Had a meeting with supervisor and talked about direction I should take analysis in
  *  Decided to get results to discuss for next week
* *7.5 hour* 
  *  Set up functions to error results as a percentage 
  *  Created a function to tell me how many cases there are of error about a certain threshold
  *  Recreated RetinaFace dictionary as some of the values were wrong
  *  Created function to generate histograms for each algorthims error distances
  *  Worked on github repo by uploading template files and flling them out with my previous data and artifacts
  *  Created function to generate difference in frequencies of errors aswell as corresponding graphs
  *  Generated which face gave the worst and best result for each algortihm
  *  Collated my results in an excel file 
             
## 18 Nov 2020

* *0.5 hour* 
  *  Had a meeting with supervisor and went over the graphs I had created 
  *  Thought about future direction I could take research in
  *  Discussed breaking up histograms into several smaller histograms to compare the bias instead of comparing the algorithms
* *7.5 hour* 
  *  Fixed IoU code to calculate the percentage of overlap correctly
  *  Broke up histogram by specific feature which allowed for some interesting discoveries
  *  Calculated average error differences for all algorithms in their groups
  *  Created histogram for bounding box overlap of the different algorithms in their groups
             
## 25 Nov 2020

* *0.5 hour* 
  *  Had a meeting with supervisor and went over the new graphics I had broken down, showed him the lack of conclusive evidence
  *  Discussed instead of creating a new dataset to instead resize the current dataset and run the algorithms again to see if thats the reason retinaface's results are skewed
  *  Discussed testing the robustness of my dataset by running the tests over samples of my dataset and find the average difference and using it as a standard deviation metric
* *7.5 hour* 
  *  Created notebook to scale my dataset to 300 width whilst keeping its proportions the same
  *  Reran the different algorithms on my new dataset
  *  Rescaled my ground truth to match the correct scaling of the images
  *  Generated the different figures and graphs and noticed an improvement in my results.
             
         
## 7 Dec 2020

* *6 hour* 
  * Researched into the design of the Viola and Jones algorithm
  * Looked at the idea of feature extraction and how Viola and Jones manages detection without deep learning
  * Completed a paper summary of the Viola and Jones paper to assist me when I complete dissertation
           
## 8 Dec 2020

* *6 hour* 
  * Researched into the design of the MTCNN algorithm
  * Looked into reasons why a deep network approach might be related to its poor performance in minorities
  * Completed a paper summary of the MTCNN paper to assist me when I complete dissertation
                      
## 9 Dec 2020
* *0.5 hour* 
  *  Had a meeting with supervisor and discussed plans for the 2 week period
  *  Discussed completing a report which would display my graphs and a paragraph under each explaining what was being shown so that when I move onto the next stage of experiments I know what I have done previously
   *  Discussed cleaning up code into a single solid notebook which would display all my graphs at ease.
             
* *6 hour* 
  * Researched into the design of the DLIB algorithm
  * Completed a paper summary of the DLIB paper to assist me when I complete dissertation  
           
## 11 Dec 2020

* *7 hour* 
  * Cleaned up my comparison notebook code by creating a new evaluation notebook with a consistent and understandable structure
   * Completed standard deviation metric to compare to average of normal dataset aswell. This let me show how robust my dataset was 
           
## 13 Dec 2020

* *6 hour* 
  * Cleaned up the separate algortihm notebooks 
  * Updated the repository with the new annotation files for the 300 width photos
           
## 14 Dec 2020

* *6 hour* 
  * Created a separate resized annoatations file so I could remove some of the uneccesary complexity from the evaluation file itself
  * Created an excel spreadsheet containing all my figures from my evulation notebook
  * Created a corresponding file with descriptions of what the figures showed
           

