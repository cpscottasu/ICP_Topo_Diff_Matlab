# ICP_Topo_Diff_Matlab
Matlab code and earthquake topography datasets to experiment with ICP 3D differencing

Contents: 
Matlab code that performs windowed ICP and plots the results. There are several Matlab files listed in the included Matlab script that must be downloaded from MathWorks. 


To perform the ICP Differencing: 
1. Download the Matlab scripts and download the list functions from Mathworks
2. Download already processed datasets for the Kumamoto earthquake here: https://cloud.sdsc.edu/v1/AUTH_opentopography/www/shortcourses%2FA2HRT_RCN%2FKumamoto_Lidar.zip
or process your own lidar data given the links below. 
3. Put the downloaded las lidar datasets in the same directory has the Matlab scripts. 
4. Run ICP on Matlab. It will probably take 10-30 minutes depending your computer's processing speeds. 


The full Kumamoto datasets are available from OpenTopography here: 

Pre-earthquake: https://portal.opentopography.org/lidarDataset?opentopoID=OTLAS.052018.2444.2

Post-earthquake: https://portal.opentopography.org/lidarDataset?opentopoID=OTLAS.052018.2444.1


Several references for ICP differencing: 

Presentation slides: https://cloud.sdsc.edu/v1/AUTH_opentopography/www/shortcourses%2FA2HRT_RCN%2FICP_differncing_DEMO.pdf

Scott et al: (2018): https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2018JB015581

Nissen et al: (2014): http://www.sciencedirect.com/science/article/pii/S0012821X14005378

Nissen et al: (2012): http://onlinelibrary.wiley.com/doi/10.1029/2012GL052460/full


Funding Acknowledgment: OpenTopography is supported by the National Science Foundation under Award Numbers 1833703, 1833643 & 1833632
