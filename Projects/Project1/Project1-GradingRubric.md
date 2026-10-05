# Project 1: Present a Data Visualization

## Grading Rubric

### The Draft Version

The __draft version__ will simply need to have something for each section below. A *completely missing section* will be scored as zero points. Each section will be worth 5 points. Your project will not need to pass the reproducibility test, although it is highly recommended. 

The instructor will provide feedback on each section that needs improvement. 

### The Final Version

The __final version__ of Project 1 will be scored on the presence and completeness of each of the project items outlined below, as well as meaningful improvement of the visualizations in response to class feedback. 

#### Reproducibility Test

Successful replication of the Project by the instructor. The replication process is as follows: 
    1. The zip file is downloaded and uncompressed. 
    2. The RStudio project is opened using the RProj file. 
    3. The RMD is opened and ``Knit" button is pressed.

If the RMD fails to knit, or if there are errors produced in the code, the project will receive no more than 50% of the available points.

#### Rproj File (10 points)

This file sets up the RStudio environment for the project and should be included. 

Rubric:

 - Full points: The RProj file is present and is able to successfully open an Rproj. 
 - No points: The Rproj file is absent or unable to open the project successfully.

#### Data Set (20 points)

The data set a separate file as a CSV or other text file of appropriate extension. Do not include XLSX or other file types of spreadsheet or database files. Data set files should be simple tables that can be directly connected back to the source listed as a reference for the data.

Rubric:

  - Full points: presence of data set as a CSV or other text file. 
  - -10 points: file is present but not in an appropriate form OR data cannot be connected back to the original source.
  - No points: absence of data set, in an inappropriate form, AND not connected back to the referenced site.

#### RMD File (20 points)

The RMD file containing the code for loading and cleaning the data set, creating the visualization, and any documentation. Code and regular text should be separated out into text areas and code chunks. RMDs should knit into either an HTML or DOC file successfully to get full credit for the project. 

Rubric:

  - Full points: The RMD file is present and knits into either an HTML or DOC file successfully. 
  - No points: The RMD file is absent or does not successfully knit into an HTML or DOC file. 


#### File header (10 points)

The file header should include a title describing the project based on the data set (do NOT put just ``Project 1'', describe the project!), your name, your course section (either 01 or 02), and the submission date. Note that this header needs to be formatted correctly, or the RMD will not knit!

Rubric: 

 - Full points: contains all elements (descriptive title, name, course section, submission date)
 - -2 points: each missing element. 
 - No points: header is missing or misses all elements. 


#### Setup chunk (10 points)

The setup chunk contain library calls for any required packages to run the code. It has the specific name "setup" and is the first code chunk of the document. 

Rubric: 

  - Full points: appropriate setup chunk exists. 
  - -3 points: for each missing (name of chunk, first chunk, library calls).
  - No points: no setup chunk. 

#### Loading and Cleaning Data (30 points)

This section should have a code chunk that loads the data set from the project and text descriptions of data cleaning steps taken. If no data cleaning is necessary, the statement "No additional data cleaning steps were necessary," should appear in this section.

Rubric: 

  - Full points: section exists and contains all elements that load the data successfully and cleans data before plotting. 
  - 20 points maximum: data set loads successfully but is not cleaned, the statement is absent. 
  - 10 points maximum: the data set is loaded and cleaning steps are present, but those steps are not effective. The data set is loaded and cleaning steps take place outside of this section. 
  - No points: data set is loaded and cleaned outside of this section, the section is absent. 

#### Visualizations (25 points each)

This section should contain both code that produces the data visualizations you have created and text description of what the visualizations tell you about the data. There should be __two visualizations__, each is worth 25 points. 

Rubric: 

  - Full points: Visualizations work well, make sense, and well labeled (axes, any aesthetic groups). Descriptions are appropriate. 
  - 20 points maximum: visualization work well, but elements are unlabeled. All other aspects are appropriate.
  - 15 points maximum: visualizations work well and all elements are labeled. No or grossly inadequate text description. 
  - 10 points maximum: visualization is present but lacks label(s) and no or grossly inadequate text description. 
  - No points: missing visualization. 

#### References (10 points) 

This section will list all external resources used to produce your project other than GenAI, including articles, Stack Overflow posts, books, etc. It will also link back to the original data source used for the project. 

Rubric: 

  - Full points: All references are listed with sufficient details to find the source. This includes an active hyperlink to each source that was accessed online. 
  - 5 points maximum: lists external resources with sufficient details but does not reference original data set and/or does not contain a hyperlink to the original source page.
  - No points: section is missing. 

#### Response to Feedback (20 points)

This section outlines in text what were the major feedback received from the instructor and peers and how you changed the project to address the feedback. There needs to be evidence that __at least two items__ of feedback from the instructor and __three items of feedback__ from peers were incorporated into the project. Please spell this out, the instructor can't keep track of everyone's changes!

Rubric: 

  - Full points: the necessary changes are implemented and well described. 
  - -4 points: for each item missing or inadequate. 
  - No points: no change are described, section is absent. 

#### Generative AI Reflection (Optional)

If you have used GenAI in creating your project, you must include a reflection (text only) which covers the following: which GenAI resource was used (Chat GPT, CoPilot, etc), how the resource was used to produce the code and how that code was integrated into your project, and any complications you experienced using the resource. 

