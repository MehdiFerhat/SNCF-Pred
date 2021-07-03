# SNCF-Pred
Using the self-service datasets available on the SNCF website  we have tried to create as robust a model as possible to explain the explain the reasons for the differences in travel time between several routes.

# Code User Manual
In order to be able to execute the code in an optimal way, it is necessary to have all the files in the same folder (either the main file or the modules). The Mac OS users should be aware that the SNCFToolbox and StatisticalTools modules both call the OS package, and the paths specified in the relevant functions contain double slashes. If there is a problem when exporting, don't hesitate to modify these double slashes (the concerned functions are specified at the end of each module). Finally, it is important to note that these exports will be located in an "Exports" folder that will be created where the files will be located.

# Libraries Used
• Seaborn
• Pandas
• Numpy
• Matplotlib
• SciPy
• Statmodels
