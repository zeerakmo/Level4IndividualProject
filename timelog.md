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
           
## 15 Dec 2020

* *6 hour* 
  * Completed the status report first draft
  * Continued work on report file with descriptions
  
## 16 Dec 2020

* *6 hour* 
  * Continued to work on the report file
  * Researched about the datasets each algorithm I am using is trained on 
  
## 15 Jan 2021

* *8 hour* 
  * Altered the images to see if I could get the MTCNN detector to perform better
  * Tested these and compared against the orignal results in the evaluation file

  
## 22 Dec 2020

* *8 hour* 
  * Altered more images and realised that different alterations affect each image differently
  * Updated the evaluation file with more altered images results
  * Had meeting with supervisor and discussed next steps on how to cover all bases of research
  
  
## 29 Dec 2020

* *8 hour* 
  * Realised by changing the brightness of every image was more succesful than adding on contrasting lines and it shows that generally brighter faces perform better
  * Tested this hypothesis on all images with face errors more than 7% for MTCNN
  * Aggregrated results in spreadsheet to compare and contrast with
  
## 15 Jan 2021

* *8 hour* 
  * Had a meeting with supervisor in which we discussed plan for this semester and room for project expansion
  * Showed test results and concluded that more work was required

## 18 Jan 2021

* *4 hour* 
  * Worked on new methods of changing images such that they worked with my research question
  * Changed contrast of entire image instead of just adding lines 
## 22 Jan 2021

* *7 hour* 
  * Had meeting with supervisor and discussed blockers 
  * Showed results of changing contrast of entire image and decided to pursue this experiment

## 29 Jan 2021

* *8 hour* 
  * Had meeting with supervisor and showed updated results, discussed holding off on any extra experiments and instead starting to write dissertation
  * Worked on fixing up graphs and figures for disseration and researched method to write it
  * Cleaned up results of changing contrast into own tables 

## 4 Feb 2021

* *8 hour* 
  * Worked on dissertation main sections of methodology, results and discussion
  * Completed methodolgy section and results
## 11 Feb 2021

* *8 hour* 
  * Started to work on discussion section and got a chunk of the analysis completed although plenty of space for refinement
  * Continued research into the algorithms

## 15 Feb 2021

* *8 hour* 
  * Worked on background section of report and started explaning 4 algorithms
  * Continued work on discussion section

## 19 Feb 2021

* *8 hour* 
  * Had a meeting with supervisor and showed status of report sections
  * Continued to work on background and discussion section aswell as start the introduction section


## 22 Feb 2021

* *4 hour* 
  * Worked on background section and discussion section for algorithms and updated structure of the report


## 26 Feb 2021

* *8 hour* 
  * Had a meeting with supervisor and asked for feedback on structure, realised I should decrease the size of chapters
  * Completed dataset section and started writing the implementation section
  * Whilst writing implementation section, found a small error in code which meant I had to recreate my figures


## 28 Feb 2021

* *8 hour* 
  * Ran through report and updated where the error was present and altered discussion slightly
  * Fixed the implementation section and started conlcusion
 
## 1 Mar 2021

* *8 hour* 
  * Started to work on refining entire report sections and adding more information so I could have a first draft ready by mid march
  * Redid methodology section and cleaned up discussion
  * Redid sections of the report to be in line with the research question


## 3 Mar 2021

* *5 hour* 
  * Added referecnces into the report and figures from other sources
  * Cleaned up background section to relate better to research question


## 5 Mar 2021

* *6 hour* 
  * Redid photos and created new figures for report and sourced everything correctly
  * Changed conclusion section to contain 3 sections which included research question answer

## 10 Mar 2021

* *7 hour* 
  * Refined report sections and uodated dataset bias section to include recent findins from the diversity in faces paper
  * Removed section describing old implementations
  * Updated methedology to describe metrics


## 15 Mar 2021

* *8 hour* 
  * Had meeting with supervisor and showed report, got positive feedback on structure
  * Started to clean up references properly and relate them to content
  * Cleaned up english errors in report to make it read better
  * Added in sections describing each chapter


## 28 Mar 2021

* *7 hour* 
  * Worked on referencing
  * Fixed background section and implementation section to relate better and be more coherent


## 29 Mar 2021

* *8 hour* 
  * Added in more analysis into discussion section of the report so that it was easier to read
  * Updated the background section with emphasis on helping reader understand structure of algorithms
  * Altered tables in report to be actual latex tables instead of images and cleaned formatting of figures

## 30 Mar 2021

* *8 hour* 
  * Refactored entire report
  * Moved the dataset bias into the discussion section
  * Moved algorithms to background section
  * Changed methedology to evalutation because the paper made more sense
  * Had meeting with supervisor and discussed changed and submitted a real 1st draft that would actually get proper written feedback
  * Worked on changing background section first paragraph to help describe facial detection easier
  * Changed discussion section content to flow better aswell as relate to the research question better
  
## 31 Mar 2021

* *8 hour* 
  * Started at the introduction and backgrond and started to add in more information for feature based methods and image based methods
  * Altered disucssion to do with dataset bias
  * Changed introduction to explain the face detection better
  * Changed headings to make more sense and separated image sizes to look neater


## 1 Mar 2021

* *8 hour* 
  * Altered background section on image based methods
  * Altered discussion for HOG, MTCNN and RetinaFace to better relate to results and be honest
  * Wrote discussion to do with research question
  * Changed algorithms section to explain the Viola-Jones algorithm correctly
  * Changed algorhtims section to flow more coherent
 

## 2 Mar 2021

* *8 hour* 
  * Fixed evaluation section and background section with more detail
  * Added in information about each metric coherently
  * Added new section into discussion to talk about dataset bias and introduce it better
  * Changed conclusion and research question answer to fit with the updated discussion
  * Combined sections in discussion to talk about sampling bias and benchmark bias separately

## 3 Mar 2021

* *8 hour* 
  * Added limitations section
  * Resized graphs and changed their locations
  * Cleaned up the results section to read better
  * Updated background with more information for feature based algorithms
  * Added in all extra content required
  * Added in uncertainty values to tables

## 4 Mar 2021

* *8 hour* 
  * Created presentation for project
  * Recorded presentation
