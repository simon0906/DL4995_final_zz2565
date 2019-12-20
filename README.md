# DL4995_final_zz2565
# Author: Zhenyu Zhang, Uni: zz2565

code/: contains all the codes of this project. <br />
    project_extract_patches.ipynb: extract 299x299 patches with stride 128,128 from 21 images: 14 training, 6 validation, 1 test <br />
    project_InceptionV3_model_training.ipynb: training, validation plus test using InceptionV3 as pretrained model <br />
    project_VGG16_model_training.ipynb: training, validation plus test using VGG16 as pretrained model <br />
<br />
best_f1_score_model.h5: model saved with best_f1_score on tumor patch recognition <br />
<br />
Project raw data and extracted patches link: https://drive.google.com/drive/folders/12GCBFCcZAcu3MzbM2iZQtYYMPWyst_dl?usp=sharing <br />
    all_patches/: contains all extracted patches for training, validation and test with their activations. <br />
    slides were distributed into three folders: <br />
        original_slides/: slide image for training and validation <br />
        masking_slides/: mask slide image for training and validation <br />
        testing_slides/: slide and mask slide image for testing <br />

Viedo link:
