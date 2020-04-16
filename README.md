# ICP_Topo_Diff_Matlab
Matlab code and earthquake topography datasets to experiment with ICP 3D differencing

Contents: 
Matlab code that performs windowed ICP and plots the results. There are several Matlab files listed in the included Matlab script that must be downloaded from MathWorks. 


To perform the ICP Differencing: 

1. Download the Matlab script differencing_matlab.m and open in Matlab. 

2. Download these functions from Mathworks:

Matlab ICP File Exchange (Jacob Wilm): 
%https://www.mathworks.com/matlabcentral/fileexchange/27804-iterative-closest-point

Lasdata File Exchange (Teemu Kumpumäki):
%https://www.mathworks.com/matlabcentral/fileexchange/48073-lasdata

3. Place the downloaded files in the same directory as differencing_matlab.m. 

4. Download already processed datasets for the Kumamoto earthquake here: https://cloud.sdsc.edu/v1/AUTH_opentopography/www/shortcourses%2FA2HRT_RCN%2FKumamoto_Lidar.zip
or process your own lidar data given the links below. 

5. Put the downloaded lidar datasets in the same directory as the Matlab scripts. The Matlab ICP differencing script (differencing_matlab.m) assumes that the pre-earthquake file is called 'pre.las' and the post-earthquake file is called 'post.las'. 

6. Run differencing_matlab.m on Matlab. It will probably take 10-30 minutes depending your computer's processing speeds. When it completes, Matlab will display a vector field map indicating the 3D displacements for the 2016 M7 Kumamoto, Japan. 

7. To experiment further with ICP, change the sz parameter (Line 40). This is the window size/ resolution used in the ICP calculation. Also change the grd parameter (Line 41). This is spacing between the individual ICP measurements. 


The full Kumamoto datasets are available from OpenTopography here: 

Pre-earthquake: https://portal.opentopography.org/lidarDataset?opentopoID=OTLAS.052018.2444.2

Post-earthquake: https://portal.opentopography.org/lidarDataset?opentopoID=OTLAS.052018.2444.1


Several references for ICP differencing: 

Presentation slides: https://cloud.sdsc.edu/v1/AUTH_opentopography/www/shortcourses%2FA2HRT_RCN%2FICP_differncing_DEMO.pdf

Scott et al: (2018): https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2018JB015581

Nissen et al: (2014): http://www.sciencedirect.com/science/article/pii/S0012821X14005378

Nissen et al: (2012): http://onlinelibrary.wiley.com/doi/10.1029/2012GL052460/full


Funding Acknowledgment: OpenTopography is supported by the National Science Foundation under Award Numbers 1833703, 1833643 & 1833632
