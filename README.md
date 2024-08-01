# bibazu_cnn_training

This package contains code for training convoluted neural networks to be used in aerodynamic part feeding. They are used for detecting the orientation of parts visually so they can be re-oriented arbitrarily.

## User input and configuration parameters
+ Training and validation datasets
+ Neural Net Architecture
+ Augmentations
+ Training parameters

## Output
+ Trained network for live orientation classification

## Local
use the `bibazu_ml_training.ipynb` notebook

Required Installations for the Local Branch (working combination):
+ Python3 (3.10.12)
+ Matplotlib (3.5.1)
+ Numpy (1.23.5)
+ Tensorflow (2.17)
+ scikit-learn (1.5.1)

## Google Colab
1. open the colab notebook in google colab: http://colab.research.google.com/github/match-Aero/bibazu_cnn_training/blob/main/bibazu_ml_training_colab.ipynb
2. save it locally, to your own github or google drive to save changes
3. add your own training data using direct upload
4. customize dataset path variables "synthetic_ds_path" and "real_ds_path"
5. do training
6. export your trained neural networks
