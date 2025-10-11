# MSSEG MS Lesions Results
This repository contains supplementary results for the MSc dissertation titled
"Repeatability by Radiologist When Segmenting the Brain."

This project aims to investigate how the repeatability in ground truth used to segment a brain volume from medical images affects the subsequent training for automation which can be performed using neural networks. The U-Net neural network will be trained for brain volume and lesion volumes in patients with multiple sclerosis. The MICCAI dataset will be used for this study, with image segmentation performed by 7 different radiologists. This project will involve medical images, Python coding, and mathematical analysis of subsequent data. 

Contents:
-3D Slicer results.zip
 -Contains the segementation files, results table for each metrics, and images for each patient.
  
-2D U Net results(100 epochs).zip
 -Contains the results tables which includes the Hausdoff Distance and Dice Coefficient values.
 -Each images includes FLAIR, Ground Truth Mask, and Predicted Mask.
 
-2D U Net graphs and results tables.zip
 -Contains training loss curves, Dice score histograms, Hausdoff Distance histograms and the results tables which includes the Hausdoff Distance and Dice Coefficient values.
 
-3D U Net results(100 epochs).zip
 -Contains the results tables which includes the Hausdoff Distance and Dice Coefficient values.
 -Each images includes FLAIR, Ground Truth Mask, and Predicted Mask.
 
-3D U Net graphs and results tables.zip
 -Contains training loss curves, Dice score histograms, Hausdoff Distance histograms and the results tables which includes the Hausdoff Distance and Dice Coefficient values.
