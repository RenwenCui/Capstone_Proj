# Monocular Depth Estimation
For this project, we want to build a deep neural network to predict the depth map from a single RGB image in an end-to-end way. The input of the network is RGB images, and after applying the network the output of this system is the corresponding estimated depth maps.

## Usage
The code sample written by myself for peer review:
`python train.py`

If you want to run this code, please download  all `.py` files that contain modules the main function `python train.py`  will call.

### Code Structure ###
`python data.py` reads and pre-processes the NYU v2 dataset.
`python loss.py` contains loss functions.
`python model.py` contains an encoder-decoder model for monocular depth estimation.


## Small test dataset
The small test dataset for NYU-Depth-V2 can be downloaded [here](https://drive.google.com/file/d/1HFAsEQCDUx0UC63Yv5uKE2Z5Z9cKDMV0/view?usp=sharing).

