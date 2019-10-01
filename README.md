Name:	Multiplot

Filename:	Multiplot-Tkinter_FullGUI_Mac-Win.crl.python27_5-8-19.py

Author:	Casey Luskin

Summary:	Multiplot is an open-source, multi-platform, GUI-based Python application that allows visualization, calculation, and analysis of paleomagnetic data produced by the RAPID/CIT, JR6, and 2G magnetometer systems (Luskin et al., 2018). It primarily uses the Python-based Tkinter -GUI environment and Matplotlib plotting functions. 

While there already exist many excellent desktop applications for paleomagnetic data analysis and visualization, such as Paleomag 3.1 (Jones, 2002), PaleoMac (Cogné, 2003), PuffinPlot (Lurcock and Wilson, 2012), MagIC and the PmagPy suite (Tauxe et al., 2016), as well as useful online tools (Koymans et al., 2016; Hatakeyama, 2018), Multiplot offers unique capabilities that complement these other software packages. Multiplot’s main utility lies in its interactive/dynamic 3D display of demagnetization behavior which facilitates data analysis (e.g., component selection during least squares analysis), and its ability to produce customizable diagrams for publications. As a teaching tool, it can illustrate concepts like 3D trajectory of demagnetization steps, principle component analysis, vector component addition, and interpretation of Zijderveld diagrams.

Multiplot’s primary feature displays paleomagnetic demagnetization data in four side-by-side customizable “plots” which allow easy visualization and analysis of sample/site behavior: Zijderveld Plot, 3D Plot, Equal Area Plot, and J/J0 Plot. Each plot offers features not provided by existing paleomagnetic data analysis programs:

Zijderveld Plot: Most paleomagnetic programs generate Zijderveld plots with inclination projected against the E-W, N-S, or hyperbolic axes, which Multiplot also does. But the ideal angle for viewing demagnetization steps may lie between these axes. Multiplot can project inclination data along a vertical plane sitting at any angle specified by the user, including within a plane aligned with the “average declination,” minimizing distortion of data due to “apparent dip.”

3D Plot: A principal novel contribution of Multiplot is its 3D Plot, which displays demagnetization path defined by measurement steps and best-fit lines in 3D space which can be manually and dynamically rotated to view from any angle. When juxtaposed with the Zijderveld diagram, this plot greatly enhances data analysis by fostering easy visual identification of steps within components. 

Equal Area (Stereonet) Plot: In addition to plotting sample demagnetization data, Multiplot can plot selected components (lines or arcs) of samples or sites on an equal area plot, and also calculate, display, and save mean directions (and α95 confidence ellipses) of a selected set of components from a site, or set of sites.

J/J0 Plot: This standard diagram corrects a problem in Paleomag 3.1 that failed to indicate intensity increases, and can display histograms show relative and absolute intensity gain or loss. Curie temperature ranges of common magnetic minerals can also be overlaid.

For each of these plots, data can be displayed from (a) selected steps from a single sample, (b) selected samples at a single step, or (c) multiple selected steps from multiple selected samples. The latter capability (plotting multiple steps from multiple samples on a single plot) can provide an instantaneous sitewide snapshot of sample behavior and mean directions.

Multiplot also includes a paleomagnetic calculator which can determine individual site or grand mean virtual geomagnetic pole (VGP) locations, mean directions, coordinate conversion and rotation, fold tests, and common paleomagnetic statistics (α95, k, and semi-axes of ellipses of confidence).

Intended Scope of use: 	Multiplot was originally written for use in this investigation as a tool for assessing sample behavior during demagnetization, though it soon expanded to other capabilities. Most of the site-specific data analysis and results diagrams in this thesis were created using Multiplot. became used by other colleagues in the Paleomagnetism Lab at the University of Johannesburg (UJ). It is currently in final development and is intended for public release in 2020.

Requirements:	Python 2.7 installed on Windows or Mac with standard built-in Python libraries/modules, plus numpy, matplotlib, and xlrd. 

Input:	Multiplot can plot data from the RAPID Squid format, JR6 Spinner format, or 2G Long Core format. It can also plot .lsq files generated by Paleomag 3.1. The paleomagnetic calculator can also accept input from Excel files, text files, or input directly typed into a text box. 

Output:	Multiplot produces a variety of common paleomagnetic diagrams that can be modified in a variety of ways and saved in different formats (e.g., .png, .jpg, .pdf, .tif). The calculator outputs text of the calculated statistics. 

Number of lines of code:	29,062

Other Credits:	Some segments of filereading code adapted from a script written by Michiel de Kock, and code for math functions related to plotting ellipses of confidence on Equal Area plots borrowed from PmagPy. Support, testing, and feedback was provided by users within the paleomagnetism laboratories at UJ and the University of São Paulo. 

Download and Support:	Multiplot is still in development but a working version can be downloaded from https://github.com/pongola/Multiplot/ or Multiplot.org. For support or assistance, please contact the author Casey Luskin at caseyl@uj.ac.za or casey.luskin@gmail.com.
