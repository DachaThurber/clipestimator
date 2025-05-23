# clipestimator

## src/
### pixel_pose_estim.ipynb
A pipeline for estimating and evaluating the position of a clip based on pixel alignment with a segmented image.

### synth_data_generator.ipynb
A pipeline for generating synthetic data based on backgrounds, foreign objects, and the clip mesh.

### syth_data_pipeline.ipynb
A pipeline for generating a synthetic dataset and training a ResNet18-based position estimator based on the synthetic data.

## data/
### mesh/
A folder for the clip mesh

### backgrounds/
A folder for background images to be used in the creation of synthetic data.

### objects/
A folder for the object segments to be used in the creation of synthetic data.

### synthetic_data
A folder for the storage of completed, labeled, synthetic data to be used in training by synth_data_pipeline.ipynb.

### baseline/segment
A folder for real segmented clip images for testing purposes.


## To run
Python 3.9.19
Pytorch 2.3.1
Pytorch3D 0.7.7
CUDA 11.8
PyVista 0.44.1
