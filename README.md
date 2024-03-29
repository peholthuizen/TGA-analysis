# TGA-analysis

As PhD-students from Materials and Environment group at Civil Engineering. Therefore, we do a lot of research in phase analysis of cementitious materials by characterization and quantification. One of the most common techniques for us is a Thermogravimetric analysis (TGA). By burning your sample until high temperatures, the material decomposes and loses weight at specific temperatures, which can be quantified and will correspond to a specific chemical component.  
For this reason we developed the notebook TGA_Analysis.ipynb that will read the produced csv file from the TGA analysis, automatically identify different phases in your analysed material by using inflection point in the mass Loss curve by using the first and second derivative and ask you for your phase of interest, which will be plotted. 
Additionally we use a lot more material characterization tools, which all come down to peak finding, which is comparable to the first derivative of the TGA Mass loss. Therefore, one can imagine that this notebook can be rewritten for different csv-files and used to find the peak position.

This respository contains the aforementioned notebook. Additionally, the respository contains the datafiles (.csv files) used for testing the notebook, which can be found in the folder Data.
