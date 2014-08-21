StegExose: Corpus overview
=========================

StegExpose.zip
---------------
A zip file containing the Java source code of the StegExpose project as well as a runnable jar file named 'StegExpose.jar', a README file describing the programs usage and a directory named 'testFolder' containing 3 stego images and 13 clean images originating from the original test pool used for this project.

sample steganalytic report.csv
----------------------
A Comma Separated Value file generated by StegExose indicating whether it expects a file to have hidden data and if so, how much of it (quantitative steganalysis).


StegExpose analysis.ods
----------------------
Open Office spread sheet that contains the following information on all images in the test pool (15,200 images).
	*	Output of detectors
	*	Combination of detectors (fusion techniques)
	*	ROC (receiver operating characteristic) values
	*	Size of the actual and estimated embedded information
Additional sheets include a graph of the ROC curve and a table containing speed results of individual detectors as well as speed test on the default and fast mode of StegExpose.

Steganography tools.zip
-----------------------
Zip file containing binaries for the four different steganography tools used to create the stego files in the projects test pool.

Detectors.zip
--------------
A collection of the four steganalytic techniques used in this project.
