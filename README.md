# 🔋 NetClean - Complex Networks Data-Cleanser


Cleanse and organize the output files from [this repository](https://github.com/bt3gl/NetAna-Complex-Network-Analysis).

To be used [in this repository](https://github.com///MLNet-Classifying-Complex-Networks).


1. Cleansing:
------------

Here we get all the outputs from MNet Network Analysis and we put together into vector files, separated by sampling groups  (for further sampling analysis) and network type. It contains header. Missing values are completed with '-'.

2. Separating:
--------------

Here we get all the outputs from MNet Network Analysis and we put together into vector files for each network (all sampling results all together. We also add an additional column for the class. It does not contain the above header. Missing values are completed with '0'.

3. Generating Final File:
-----------------------------

Here we read the vectors files from previous step and create a unique file for all the data.

The file for the entire nets is here. The file "label.data" explain each column.


