# Features Explanation Method


This repository embeds a [notebook that presents the Feature Explanation Method (FEM)](https://github.com/labribkb/fem/blob/main/FEM.ipynb).
FEM aims at explaining a classification decision by depicting the important input features.
The presentation is inspiraed by the [Gradcam example of Keras](https://keras.io/examples/vision/grad_cam/)

The method is fast as it relies only on activation values of the last convolution layer, do not rely on backpropagation or dedicated rules, and is class-agnostic.

This work has been published at IPTA 2020:

    Fuad, K. A. A., Martin, P. E., Giot, R., Bourqui, R., Benois-Pineau, J., & Zemmari, A. (2020, November). 
    Features understanding in 3D CNNS for actions recognition in video. 
    In 2020 Tenth International Conference on Image Processing Theory, Tools and Applications (IPTA) (pp. 1-6). IEEE.
