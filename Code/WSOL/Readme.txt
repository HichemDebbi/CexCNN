Requirements: Tensorflow and keras

The following notebooks are needed to generate the experimentswith respect to CexCNN as well as CAM:
1. LambdaFinalLastLayer_All_HM/LambdaFinalLastLayer_All_HM_CAM, which  are used for generating heatmaps.
2. VOC_BBOX_Imgnet_Final/VOC_BBOX_Imgnet_Final_CAM, which are used to compute IoU, generate BBox, and compute the final GT-known accuracy.

PS: 
- The final evaluation results are let on the notebook to be consulted.
- The empty folders are required to receive the results of each notebook. It is prefered to run each method CexCNN/CAM seperately.
- The ILSVRC2012 validation dataset is required to reproduce the results. The images must be in the ImagentDataset folder, and the bbox
data in ILSVRC2012_bbox_val_v3/ILSVRC2012_bbox_val_v3_ALL

- Final WSOL accuracy results reported in the paper are found at the end of final output cels of the notebooks:
VOC_BBOX_Imgnet_Final/VOC_BBOX_Imgnet_Final_CAM

- Gimagnet is the file containing the causal information learned of filters with respect to each category.