# US-West-Coast-Habitat-Classification
A guide to developing non-hierarchical habitat classifications using open-source data and software based on the original R Tutorial by Amelia Bridges and updated to include specific code for the United States West Coast.

# **About this Repository **

This series of code was developed by scientists in the University of Plymouth's Deep Sea Conservation Research Unit as part of a pipeline to assist delegates of the 'Habitat Conservation and Marine Spatial Planning' workshop at the Deep Ocean Collective Solution Accelerator Meeting (Scripps Institution of Oceanography, 2-5th October 2023) in developing regional benthic habitat classifications. The pipeline mirrors that used in McQuaid et al. (2023).

This series of code was added onto by the intern working group between the 'Habitat Conservation and Marine Spatial Planning' working group at the Deep Ocean Observing Strategy and the University of California San Diego's Environmental Systems Senior Intern at Scripps Institute of Oceanography. This addition to the code is representative of the United States West Coast using the FISHGLOB_data extent and data as the delimiter. This series of code can be added to or replicated to represent different data sets. 

The repository is designed to be downloaded as a zip folder and for the scripts to be run sequentially (steps 1 to 3) in the same R Studio session. This document is not designed to provide a thorough background in the theory of non-hierarchical habitat classification, nor the variable selection process. For this, we recommend reading Howell (2010) or the abovementioned McQuaid et al. (2023).

To get started, follow these steps (NB: please make sure you have R and R Studio installed):

    1. Click on the green 'Code' button & then the 'Download Zip' (circled in red).

    2. Unzip the folder in the location you want to work - e.g. Desktop/Documents etc.

    3. Open the .html files and familiarize yourself with the process and what the outputs look like.

    4. Double-click on the .Rproj file - this will open R Studio.

    5. In the files panel in R Studio, open the 'Step1_Accessing_the_data' .qmd file*.

    6. Work through the chunks of code in the script until you reach the end.

    7. Without removing anything from your R environment or closing R, open the 'Step2_Clustering_inputs' .qmd file.

    8. Work through the chunks of code in the script until you reach the end.

*The .qmd documents are the scripts used to create the .html files. These allow you to work through the process manually and alter variables/clusters/datasets if you wish.
