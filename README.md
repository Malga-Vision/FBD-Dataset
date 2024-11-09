# FBD-dataset

The Facade Building Defects (FBD) dataset comprises images of building facades collected from three distinct Italian locations: Genova, Napoli, and Benevento. The images in the dataset are captured from a close distance using a front-view perspective with various devices, including smartphones and cameras, resulting in variations in resolution and quality.  
To standardize the dataset, images are resized to [224, 224] pixels, corresponding to the input dimension of each considered model. The dataset contains 1591 images representing potential building faults identified and compiled by analyzing relevant literature [26] [27] and thus labeled by an expert in the field into 4 different classes: spalling, cracks, stains, and vegetation.  
Stains are characterized by localized color variations on surfaces, stemming from the presence of natural components or foreign substances.  
Cracks manifest as linear disruptions within compact structures, indicating structural vulnerabilities.  
Spalling refers to the detachment of coating layers, exhibiting forms ranging from diffuse micro-cracking to detachment formation.  
Vegetation denotes the presence of biological organisms, including herbaceous, shrub, or tree species, capable of impacting both infrastructure and environmental health.  
Table 1 shows the number of images per class in the training and test sets. Fig. 1 shows an image per class in the FBD dataset.  
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

