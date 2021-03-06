# Deep Depth Densification Network for Depth Prediction using RGB Image/ Semantic segmentation and sparse LIDAR Data
This network is developed to combine RGB image and and sparse LIDAR data to produce a depth map of a scene.

# Reference
Paper: https://arxiv.org/pdf/1804.02771v2.pdf

# Development so-far
- The network was created and trained on the google colab platform.
- Created an algorithm to perform input parameterization based on the paper.
- Created a the deep depth densification network mentioned in the paper and trained on the NYUv2 labelled dataset. (RGB Image + Sparse LIDAR data)
- Trained the same network with semantic segmentedimage and sparse lidar data.

# Setup
The Notebook folder contains the notebook file for training and testing the network.
NOTE: The project is still on working phase, the code was developed on jupyter notebook, hence few extra lines for the adapting to the platform.

# Network Structure and Results from paper and Results obtained
- The network used is a deep depth neural network with residual connections
<img src="https://github.com/SUDHARSANM29/deep_depth_densification_network_for_depth_prediction/blob/master/Images/network_structure.JPG" width="450" height="280">
- The input paameterization of lidar data. The datais further horizontal flipped to increase the data points.
<img src="https://github.com/SUDHARSANM29/deep_depth_densification_network_for_depth_prediction/blob/master/Images/input_parameterization.JPG" width="450" height="280">
- The following image shows the result obtained in the paper which used extensive data for training.
<img src="https://github.com/SUDHARSANM29/deep_depth_densification_network_for_depth_prediction/blob/master/Images/paper_results.JPG" width="300" height="280">
- The below diagram and table shows the output obtained using the network created in this project and trained using labelled NYUv2 dataset comprising of 1449 images.
<img src="https://github.com/SUDHARSANM29/deep_depth_densification_network_for_depth_prediction/blob/master/Images/test_prediction_nn.JPG" width="450" height="280">
<img src="https://github.com/SUDHARSANM29/deep_depth_densification_network_for_depth_prediction/blob/master/Images/network_results.JPG" width="450" height="150">
