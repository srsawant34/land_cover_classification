# Land Cover Classification System
Land Cover Classification
-------------------------

Following are the directions and requirements to run the each experiment. For each experiment a jupyter notebook is provided.

Kaggle Notebook: Experiments that require Kaggle resource to execute are mentioned below. GPU hardware used is GPU100.
    
    1. DeepLabV3:
       File: DeepLabV3.ipynb
       Libraries: torch, pandas, matplotlib, numpy, PIL, OpenCV, pytorch lightning, pytorch's segmentation module.
       Directions: On kaggle add dataset, and follow and run the each cell sequentially to run the experiment. Before implementation of the model make sure to install library mentioned in fist cell and import all necessary libraries (present in next cells) 
    2. U-net: 
       File: Unet.ipynb
       Libraries: torch, pandas, matplotlib, numpy, PIL, OpenCV, pytorch lightning, pytorch's segmentation module.
       Directions: On kaggle add dataset, and follow and run the each cell sequentially to run the experiment. Before implementation of the model make sure to install library mentioned in fist cell and import all necessary libraries (present in next cells) 
    3. SegNet:
       File: SegNet.ipynb
       Libraries: torch, pandas, matplotlib, numpy, PIL, OpenCV, pytorch lightning, pytorch's segmentation module.
       Directions: On kaggle add dataset, and follow and run the each cell sequentially to run the experiment. Before implementation of the model make sure to install library mentioned in fist cell and import all necessary libraries (present in next cells). In this notebook there two different implementation of Segnet, one in which Segnet fails and generate a random color mask. And the other implementation is provided below this failed attempt. 
    4. MaskRCNN:
     Note: Google Colab: MaskRCNN model have various dependies issues with multiple packages. This requires installation of some libraries with specific versions like numpy. This is not possible in Kaggle notebook which doesn't let us install and load the required version since it comes with preloaded versions of the libraries. Before running enable GPU hardware and upload the dataset (can be downloaded from dataset link: https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset) and provide the correct path of the dataset directory.
     File: Mask_RCNN.ipynb
     Libraries: torch, pandas, numpy, OpenCV, PIL, pycocotools, matplotlib
     Directions: Run the first cell to install required version of numpy and restart the runtime. The don't run this cell again and continue to run the remaining cells sequentially. This order is crutial some packages must be installed in particular order. If these steps are followed then notebook should run seamlessly. 


I have also included the colab notebook file where some of the additional visualization code is written. File is DataVis_land_classification.ipynb. 
