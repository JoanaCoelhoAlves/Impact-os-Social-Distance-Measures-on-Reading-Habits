This repository contains 3 main folders: 
- code
- data 
- docs

The folder code contains 3 documents: scrapper, processing and DEA, R models.
"scrapper" contains the Python code developed to webscrape Goodreads.com relevant information for this analysis. The output is the dataset "goodreads_data", which is the input data for the second document "processing and EDA".

NOTE: because I webscrapped a large amount of profiles the goodreads_data is a very heavy file that GITHUB does not support, in case you are interested to run the code on your own or if you feel the dataset is relevant for your research pelase email joana.pires.coelho1@gmail.com so that i can send you the dataset.


"processing and EDA" as the names indicates is used to pre-process data, create necessary variables for the research, as well as my own developed algorithm to retrieve country location from the "detail" section of a public user goodreads.com profile. The code also contain plots (correlatio heatmaps, boxplots to eye-look outliers), descriptive statistics (...). The output is the dataset "dataset_part1", which is the final database used to conduct the first part of the analysis. 

The first part of the analysis corresponds to use equation 1,2 and 3 from the paper "Frontiers virus shook the streaming star estimating the COVID-19 impact on music consumption". Such paper is on the folder "docs" from the present repository. 

After, apply "dataset_part1" in the models created in the third "code" folder: "R models".

NOTE: in order to perform the all process, it is requeired to have R-Studio as Anaconda Propmt (or equivalent). In case the user only want to see the statistical inferences please only open the "R models" folder and use as input "dataset_part1"
