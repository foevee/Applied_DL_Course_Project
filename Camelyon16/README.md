## Cancer Detection using Transfer Learning (Camelyon16 Challenge)

This is the project trying to re-implement the ideas in the paper "Detecting Cancer Metastases on
Gigapixel Pathology Images" [here](https://arxiv.org/abs/1703.02442). 

The images data are from Camelyon16 Chanllenge using Neural Networks to detect the cancer cells from the tissues. 
This project followed the same idea to utilize transfer learning on pre-trained VGG16 model for image classification. 
It divides into 3 parts:
   1. Data Preprocessing: generate sample patches from Whole Slide Images (WSI), do upsampling and data augmentation for imbalanced data.
   2. Model Training: use pretrained model on VGG1 to train the classification model and fine-tune the parameters.
   3. Model Evaluation: use metrics like accuracy, AUROC and also visualize using heatmap.
    
