# MammoModelCNN

This project was the backbone for my Final Year Project as practical part, coupled with the Dissertation. This project aims to develop CNNs models to predict Breast Tumour and its severity (benign or malignant). Various approaches were made via experiments over the MIAS and the CBIS-DDSM datasets. The first, being a limited in size and with small diversity dataset, was used with data augmentation, to create new samples from the originals. The CBIS-DDSM is a patched version from Leonardo Lai, and it was used because was found to be more practical and feasible compared to the original 163GB size, as it contains cropped images without losing any critical data.
The following tasks are covered in this repository:

MIAS dataset for:
  - Multi-class detection of Normal, Benign and Malignant;
    - CNN trained from scratch and Transfer Learning using VGG16 and ResNet50;
  - Binary classification of Mass benign or malignant;
  - Binary classification of Calcification benign or malignant;
  
CBIS-DDSM dataset for:
  - Multi-class detection of benign or malignant masses and calcificaitons (4 class);
  - Binary classification of mass or calcification abnormality;
  - Transfer learning over both of the previous tasks using VGG16;
 
 
