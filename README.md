####  Course Project 1 for Coursera 'exdata-011'  
README.md


Content
----------
This document provides background information and explanation of my course project submission for Exploratory Data Analysis (Coursera 'exdata-011') conducted by Johns Hopkins University.

Topics covered  
----------
- Project overview  
- Outcome summary  
- Submitted files and contents  
- Starting point
- Input package  
- Running the R scripts
- How the input was processed  
- Output files


Project overview
----------
This course project consists of using using R Base Graphics to create replicas of example plots of various subsets of a dataset containing measurements of a household's electric power consumption over time. This is accomplished via use of an R script to input, process and plot the data, and by posting documentation including the output files, R scripts to produce them and other relevant information, for peer review on GitHub.

Full details and assignment instructions are available from the [project GitHub repo.](https://github.com/rdpeng/ExData_Plotting1)


Outcome summary
---------
Required materials have been posted to my [public GitHub repository](https://github.com/rricce01/EDACourseProject1). This repository contains four pairs of files, Each pair consists of a plot output file and the R script which produces that plot. File pairs are named plotx.png and Plotx.R where the x indicates the assignment example plot number (1 to 4). 

Each plot output file submitted matches the correspondingly-numbered example plot given in the assignment. The plot output files were created using the correspondingly-numbered R script. 


Submitted files and contents  
----------
The following files are available on my [public GitHub repository](https://github.com/rricce01/EDACourseProject1)

- plot1.png, plot2.png, plot3.png, plot4.png  
- plot1.R, plot2.R, plot3.R, plot4.R  
- README.md  

"plot1-4.png": four files each containing one replicated plot created to fulfill the project assignment. Each plot is a 480 by 480 pixel graphic, viewable using a graphic viewer or editor supporting the .png format.  

"plot1-4.R": four files that contain the four R scripts that processed the energy consumption data in file "household_power_consumption.txt", and output the replicated plots as files "plot1-4.png" respectively.  

"README.txt": (the file you are reading now) contains explanatory information on the project submittal.


Starting Point
----------
Project input is a set of measurements of an individual household's electric power consumption, collected over a period of four years, plus descriptions of the collection process, formats and interpretation of the measured data elements.

The data package was obtained from the [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu/ml/index.html) by class faculty and posted for download by the class [here](https://github.com/rdpeng/ExData_Plotting1). 


Input Package
----------
The data downloads as "exdata_data_household_power_consumption.zip". The unzipped file, "household_power_consumption.txt" contains the sampled power consumption measurements data. 

This data is used as input by the "Plot1-4.R" scripts. 


Running the R scripts  
----------
For proper execution, the unzipped file "household_power_consumption.txt" must be saved in your system's working directory.

If the script files "Plot1-4.R" are also saved in your system's working directory, they can be run it by substituting the plot example number (1-4) for the "x" in the filename "Plotx.png" and entering the following command at the R console prompt.
>    source("./Plotx.R")

If the "Plot1-4.R" files are saved elsewhere, put the R script's fully-qualified file string into the source() command above, or load the script into RStudio and run it using RStudio functions. 


How the input was processed  
----------  
The following processing was performed by the R scripts on the input dataset:
- The date and time fields in the input data were converted to appropriate formats  
- a subset of data was created containing only observations from Feb 1, 2007 and Feb 2, 2007
- rows (observations) containing a "?" in the plotted measurement fields were removed
- plots of the example measurement data were created with appropriate formatting
- plots were saved as .png files


Output files
----------
The output file for each R script "plot1-4.png" is written to the working directory. They will contain the properly formatted plot of the processed subset of the inputs.
 
Output files can be examined using a graphics viewer or editor that supports.png formatted files.

