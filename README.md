# Assignments Week 6
# Introduction
This assignment is a continuation of last week, aiming to gain further familiarity with the basics of mass spectrometric data analysis. Rather than looking at a single spectrum, you will now look at a whole LC-MS run, combining information from the chromatography, MS1 spectra, and MS2 spectra. In the end, you might identify your favorite protein in some of the spectra.
# Input data	
The same .idx.gz file with mass spectrometric raw data (from dataset PXD006121) as last week can be used. In addition, you will need the reference proteome for Neisseria meningitidis, which you have used in the previous weeks as well.
# Tasks and output files
1)	Choose your favorite protein from N. meningitidis. Perform an in silico tryptic digest for that protein, and calculate the m/z for all resulting peptides with a peptide length of 5 – 40. Assume that peptide ions can have charges ranging from 2 - 4.
2)	Extract the ion chromatogram for each of the peptide ions calculated in 1), and plot them (ideally in one graph, but separate graphs are fine as well, especially if the max. intensities are very different).
3)	For all peptides that have a distinct elution peak in the extracted ion chromatogram, check if you can find an MS2 spectrum corresponding to that peptide ion within the elution window.
4)	For at least one MS2 spectrum for each peptide in 3), calculate the fragment ions (b- and y-ions) and match them against the measured ions in the MS2 spectrum. Plot the annotated spectrum that highlights (and ideally labels) all matching peaks.
5)	Make sure to comment your code, so that others can read and understand it easily. 
6)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
7)	Commit all your scripts and result files to your GitHub Classroom repository.
# Submission
You must submit the assignment through GitHub Classroom (or MyCourses) by 8 am February 29 to get full credit. 

