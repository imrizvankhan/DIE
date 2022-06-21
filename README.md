#Lackluster to Glister: Adaptive Image Enhancement in Erratic Visual Conditions,
# DIE-Net

Requirements
Python 
Tensorflow >= 1.15.0
numpy, PIL

Descriptions: This project is the implementation of Lackluster to Glister: Adaptive Image Enhancement in Erratic Visual Conditions, (DIE-Net).  We target the image enhancement in robust degraded visual conditions.  A deep image enhanement networl termed as DIE-Net is proposed for the enhancement, and a weight effecient upgradation and refinement mechanism is proposed to upgrade the low light images for pleasing visual quality. The model implemented in this regard comprises a simple and lightweight image DIE-Net, which split image into eflection and illumination. Our method is capable of working hybridly for the enhancement in degraded visual conditions. 

Dataset:

In this work several datasets are used for the experiments and results are shown interm of subjective and objective metrics. A LOL lowlight dataset, A under-exposed to well exposed dataset (UXOV) and a degraded condition dataset DILCOD and a new test dataset with GT images is used to evaluate the performance. 
# Proposed Dataset
 Considering the requirement we proposed a new 1000 images dataset with groud-truth imageswe captured with the variational exposures and lighting conditions.
It consists of multiple ill-illumination conditions, arranged as under-exposes to well exposed. Test and GT images are captured for the performance evaluation exept these 1000 images. 

We have presented the separate files for test images, results, ground truth and comparison for several methods, where images in seperate folders are shown with results of our method and other state of the arts on multiple datasets.

Dataset-Link for existing dagtasets are given below. 
1- The whole  training dataset of UXOV along with test images, is available at the following google drives link: https://drive.google.com/drive/u/1/folders/1uj8MGHWtRMbeuh8VZemmIv-wqUqVNdo6

2- Lol dataset is publicly available
3- New-DIE dataset test + GT are in the folder above with results and comparison methods, where the dataset link for training DIE-data images will be available at google-drive link.



<image src= "FinalDatasetsample.png" width= 800>
 
  <image src= "onlymodellow.png" width= 800>
  
   
  <image src= "DepthofresidueMap.png" width= 500>
