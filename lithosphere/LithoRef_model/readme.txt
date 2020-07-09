================================================================================================================
                                   README file for global model LithoRef18
                                            Version 1.0 (01/2019)
 
Reference: 
Afonso, J.C., Salajegheh, F., Szwillus, W., Ebbing, J., Gaina, C. (2019), A global reference model of the 
lithosphere and upper mantle from joint inversion and analysis of multiple data sets. GJI volxxx, doi:xxxxxxxxx
================================================================================================================

The actual model is distributed as a text file called LithoRef18.xyz. This README file explains the main 
parameters listed in that file. 


- Moho_r, LAB_r, Crust_den_r, LM_den_r and Asth_den_r are the moho depth, LAB depth, average crustal density, 
average lithospheric mantle density and average sublithospheric mantle density, respectively, which define 
a spherically-symmetric reference (or background) model used during the calculation of gravity anomalies, geoid 
anomalies, and gravity gradients. Therefore, as standard in potential field modelling, the predictions from 
the reference model are subrtracted from those given by the actual density model to obtain the respective 
anomalies. This reference model is simply the global horizontal average of the actual model at each iteration. 
The reported values in file LithoRef18.xyz are those obtained in the last iteration.  

- MOR Elevation (m), L0, Weighted average of the mantle density at MOR (kgm-3), MOR crustal density (kgm-3), 
MOR crustal thickness (m) and Lithospheric Mantle thickness (m) are parameters used in the calculation of 
isostatic elevation (Eqs. 16-18). See Section 3.2 for details on the rationale and selection of a reference 
MOR column.  

- ALFA and BETA are the thermal expansion and compressibility coefficients used in the density calculation of the 
lithospheric mantle (See section 4, Eq. 19).  

- LONG (Column 1) and LAT (Column 2) are Longitude and Latitud. The observed data are reported in:
 
 Column 3: Elevation (m)
 Column 10: Geoid (m)
 Column 11: Free Air (mGal)
 Column 12: Gzz (Eotvos)
 Column 13: Gxx (Eotvos)
 Column 14: Gyy (Eotvos)
  
The main model parameters are reported in:

 Column 4: Moho Depth (negative below sea level)
 Column 5: LAB Depth  (negative below sea level)
 Column 6: Average crustal density (kg m-3) 
 Column 7: Average lithospheric mantle density (kg m-3)
 Column 8: Sublithospheric mantle density (kg m-3)


- Questions about this model can be sent to: juan.afonso@mq.edu.au and/or farshad.salajegheh@mq.edu.au