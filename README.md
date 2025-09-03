# APES - Acute Pulmonary Embolism Segmenter

<!-- This is a comment and won't appear in the rendered README -->

<!--  --- -->

## Short Description
Pyhton network for deep learning segmentations of thorax CT for further analysis steps, e.g., thrombus analysis.
The detailed description of the computation can be found n the article “Deep Learning-Based Segmentation of Acute Pulmonary Embolism in Cardiac CT images" by Ehsan Amini, Georg Hille, Janine Hürtgen, Alexey Surov,
Sylvia Saalfeld, 2025. Please also cite [nnUNet](https://github.com/MIC-DKFZ/nnUNet) since our approach is based on it.

## Running
- create an input folder where you put the datasets that should be predicted, datasets must be in *.nii.gz format
- create an output folder 
- use your python environment you like; call the network
```
nnUNetv2_predict -i inputFolder -o outputFolder -d 10 -c 3d_fullres -f 1
```
The prediction will be stored in the output folder.
Here, we use fold 1 which achieved best results. If you are interested in all folds, please write an email.


## How to cite
Please cite the article “Deep Learning-Based Segmentation of Acute Pulmonary Embolism in Cardiac CT images" by Ehsan Amini, Georg Hille, Janine Hürtgen, Alexey Surov,
Sylvia Saalfeld, 2025. You can also copy the bibtex:

```biblatex
@article{2025_Amini_SegmentationAcutePulmonaryEmblolism,
  title={Deep Learning-Based Segmentation of Acute Pulmonary Embolism in Cardiac CT images},
  author={Ehsan Amini and Georg Hille and Janine H{\"u}rtgen and Alexey Surov and Sylvia Saalfeld},
  journal={International journal of computer assisted radiology and surgery},
  volume={},
  number={},
  pages={to appear},
  year={2025},
  publisher={Springer}
}
```

## Contact
Ehsan.Amini@uksh.de
