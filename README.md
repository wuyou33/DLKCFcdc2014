DLKCFcdc2014
============

DLKCFcdc2014
-General usage notes:
 -
 -1. This release of software is intended to complement a paper submission to the 53rd Annual Conference on Decision and Control (CDC)
 -2. This software is intended to be run on Eclipse. It was developed using Eclipse 4.3.0, and the development environment is Java SE Development Kit 7u25.
 -
 -How to use the software:
 -
 -1. Download the $\mathbf{DLKCF\_Observable}$ and $\mathbf{DLKCF\_Consensus}$, and import the two projects into Eclipse.
 -2. To generate Fig. 1b in the paper, run Test.java in DLKCF\_Observable and plot the generated trueState.csv using Main.m in the folder "MatlabPlot". (Note that trueState.csv should be put in the folder "Result\_Plot", same for the rest of the plots generated using Main.m.)
 -3. To generate Fig. 2a in the paper, run Test.java in DLKCF\_Observable and plot the generated writerAvr.csv using Main.m in the folder "MatlabPlot". 
 -4. To generate Fig. 2b in the paper, run Test.java in DLKCF\_Observable and generate the solid line by the data in the first column of  Lyapfun.csv. For the dashed line, set the variance of model error on the boundary cells from 0.0009 to 0.09 (line 174, 180, 184, 185 in RoadModel.java), and plot the first column of the generated Lyapfun.csv.
 -5. To generate Fig. 3a in the paper, run Test.java in DLKCF\_Consensus and plot the generated trueState.csv using Main.m in the folder "MatlabPlot". 
 -6. To generate Fig. 3b in the paper, run Test.java in DLKCF\_Consensus and plot the generated writerAvr.csv using Main.m in the folder "MatlabPlot". 
 -7. To generate Fig. 3c in the paper, run Test.java in DLKCF\_Consensus and plot the first columns of Disagreement.csv and Disagreement1.csv, to generate the solid and dash dot line, respectively.
 -8. The csv files in the foldes "results" are generated by the supplementary code, which can be considered the same as the figures in the paper subject to some random Gaussian noise from the initial guess noise and the sensor noise.
