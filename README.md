# Assignments Week 6
# Introduction
The goal of this assignment is to navigate through the measurement file from an HPLC-MS/MS analysis. This is a follow-up to last week’s assignment, and includes the combination of chromatography, MS1 and MS2 spectra. The aim is to get familiar with the information contained in each of those steps comprising an HPLC-MS/MS experiment. You will use the S-layer glycoprotein (CSG, UniProt ID P25062) as an example, but this approach can be applied to any protein within the proteome.
# Input data
An .mzML file, the standard data format for HPLC-MS/MS runs, has been uploaded to myCourses. In addition, you can download the reference proteome for Haloferax volcanii, the model archaeon that has been analyzed in this HPLC-MS/MS run from UniProt.
# Tasks and output files
1)	Plot the total ion chromatogram (TIC), i.e. the intensity of all ions over time.
2)	Perform an in silico digest of CSG, using trypsin, filter the resulting peptides to get peptides with a length between 5 and 40 amino acids. How many of those peptides can be found (on the MS1 level, assuming charges from 2 to 4) in the HPLC-MS/MS run? For each of those peptides, extract the ion chromatogram. Plot all extracted ion chromatograms in one graph.
3)	Across the elution peak corresponding to the peptide-ion VTAHILSVGR2+, check if you can find an MS2 spectrum that selected the corresponding m/z for fragmentation. Plot that spectrum.
4)	For the MS2 spectrum from 3), check how many fragment ions (b- and y-ions) you can find? Try to plot an annotated spectrum, e.g. using different colors for b-ions, y-ions, and other ions.
5)	Make sure to comment your code, so that others can read and understand it easily. 
6)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
7)	Commit all your input files, scripts, and result files to your GitHub Classroom repository.
# Submission
You must submit the assignment through GitHub Classroom by 8 am Mar 2 to get full credit. 

