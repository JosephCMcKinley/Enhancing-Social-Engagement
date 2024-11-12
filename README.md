# Enhancing-Social-Engagement

This repository is a comprehensive record of the experimental research and data analysis conducted during my Physics PhD at FAU as a Graduate Research Assistant from 2021 to 2024.  

This research was conducted as part of an NIH/NIA-funded project investigating the preservation and loss of social engagement in groups of older adults 
with Alzheimer's disease and related dementias (ADRD) interacting younger unimpaired adult facilitator and control subjects.


The analyses conducted by my research team include: 

(i) exploratory analyses observing patterns in data features such as the length of time spoken by participants and 
distributions in the social engagement scores for different hosts, which make use of data visualization schemes such as color-coded "Turn-at-Talk Graphs" and histograms, as well as 

(ii) multivariate linear regression analyses comparing various types of features as predictive variables of the level of social engagement for each event, 
including the Host ID, the number of people speaking in a given event, the presence or absence of various types of behaviors such as humor or affirmation, 
the amount and percentage of time spoken by the various speaker groups.  

These analyses allowed our team to identify strategies that group facilitators can use to maximize social engagement in groups of older adults with ADRD.


The following files are stored in this repository:

A. Microsoft Excel files consisting of social engagement event data as rated by two professional raters.  This data consists of 1839 social engagement events with
   Likert scale ratings of the degree of engagement, the number of people engaged during each event, and indicator variables for various types of behavior and
   the host ID for each event.
   
B. Praat files, including Pitch and Intensity Tiers extracted from video audio files, and diarization logs created using Praat's annotation features.
   These files are stored in compressed zip folders.
   
C. MATLAB files, including graphs and programs that read in the data and conduct the analyses.

D. Tables and Figures displaying relevant data produced by the analyses.


All data that is made publicly available here has been deidentified in accordance with standard research ethics regarding human subjects.


To independently reproduce the analyses yourself, do the following:

1. Download the MATLAB programs.
2. Download the Praat data zip files and extract them.  Set the MATLAB path to include the Praat data files.
3. Download the Excel data.  Set the MATLAB path to include the Excel data files.
4. To run the analyses on all videos, run the MATLAB file "finalMainRun".  To run the analyses on a single video, run the MATLAB file "finalQuickRun", in lines 4, 5, and 6 enter the video date.
5. After running the analyses for either a single video or all videos, the program will outpout the Tables and Figures presented on here and in the corresponding manuscript.

ACKNOWLEDGEMENTS: We gratefully acknowledge Charles Cooper for helping to write many of the MATLAB programs stored here, which are essential for the analyses.  We also acknowledge FAU's Louis and Ann Greene Memory and Wellness Center and the study participants for providing us with the data for analysis.
