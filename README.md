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
 
 
Dataset availability:
- MIAS: https://www.kaggle.com/datasets/kmader/mias-mammography
- CBIS-DDSM: https://www.kaggle.com/datasets/gabrielecotigliani/cbis-ddsmpatched/settings


The best way to import and run the repository, is either by downloading the files and load them on Kaggle, which is the environment used for this project, as it was found to be quick for data access and manipulation, where is possible to load any dataset into the environment and process it once, to have it on the go, as a variable. Kaggle also offers a variety of GPUs and TPUs for free (30h/p.week) to speed up trainng processes, also offering Persistance over output variables and files. Quite handy when weights and graphs needs to be retrieved from a training if things go wrong. 
Colab can be used instead of Kaggle, but this was discarded for the project, as it's more tedious to perform data manipulation, and it was found to be way slower.

Alteratevely, this can be treated as a normal repository for Python, it can cloned and the libraries can be installed using the requirements.txt file with:
- pip install -r requirements.txt

This was created only for those who wish to use it on a local environment rather then web based ML platforms. The libraries should be all compatible, as this project was built keeping in my compatibility and simplicity.
