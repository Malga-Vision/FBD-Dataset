# FBD-dataset

The Facade Building Defects (FBD) dataset consists of images of building facades collected from three Italian cities: Genova, Napoli, and Benevento. These images were taken at close range using various devices, such as smartphones and cameras, leading to a range of resolutions and quality levels. To ensure uniformity, all images have been resized to 224x224 pixels, the required input size for each model used in the analysis.  

The dataset includes a total of 1591 images, each representing potential building defects identified through a review of relevant literature and labeled by a field expert into four distinct categories: spalling, cracks, stains, and vegetation. 
- `Stains are areas with localized color variations on surfaces, often caused by natural materials or foreign substances.`
- `Cracks appear as linear breaks in solid surfaces, signaling possible structural weaknesses.`
- `Spalling involves the detachment of surface layers, ranging from small cracks to full detachment.`
- `Vegetation includes biological growth, such as herbaceous plants, shrubs, or trees, which can affect both structural integrity and environmental health.`  

This dataset has been used in a study to develop a deep learning pipeline focused on the automatic classification of building facade defects. The pipeline employs an ensemble of deep neural networks to improve classification accuracy and robustness across different defect types.

Table 1 shows the number of images per class in the training and test sets.  
Fig. 1 shows an image per class in the FBD dataset.  
<div align="center">

| Class | Training set | Test set | Total |
| :---         |     :---:      |     :---:      |          ---: |
| Crack   | 232     | 58    | 290    |
| Spalling     | 436       | 109      | 545    |
| Stain     | 422       | 106      | 528    |
| Vegetation     | 182       | 46      | 228    |
| Total     | 1272       | 319      | 1591    |

*Table 1: Number of images per class in the FBD dataset*

</div>

![Figure 1: Caption for the figure](/fbd.png)
*Figure 1: Sample images representing each class in the FBD dataset.*

## Dataset Split

The dataset has been divided into training and validation sets. The `train-test-split.zip` file in this repository contains the following NumPy arrays:

- `training_images.npy`
- `training_labels.npy`
- `validation_images.npy`
- `validation_labels.npy`

### Extraction Instructions

To extract the files correctly, you will need both `train-test-split.zip` and `train-test-split.z01`. Ensure both files are in the same directory before attempting extraction.

### Citing this work

Please cite the following paper when using the FBD dataset:
```
@article{interlando2024ensembles,
  title={Ensembles of deep neural networks for the automatic detection of building facade defects from images},
  author={Interlando, Matteo and Pacifico, Maria Giovanna and Novellino, Antonio and Pastore, Vito Paolo},
  journal={IEEE Access},
  year={2024},
  publisher={IEEE}
}
```
