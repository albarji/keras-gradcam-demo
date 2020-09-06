# Keras Grad-CAM demo

<div align="center">
  <img src="img/timber_wolf.png" height="200">
  <img src="img/platypus.png" height="200">
  <img src="img/westie.png" height="200">
</div>

-----------------

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/albarji/keras-gradcam-demo/master?filepath=keras_gradcam_demo.ipynb)

Notebook demo on how to use Keras to classify images with Xception net, and obtain visual explanations with Grad-CAM. Just use the binder link above to launch it!

Alternatively, if you want to run this demo locally, install a [python Anaconda distribution](https://www.anaconda.com/products/individual) and then create the environment using the provided environment file:

    conda env create -f environment.yml

After this, log into the environment

    conda activate keras-gradcam-demo

and start Jupyter notebook with

    jupyter notebook

Open the notebook named `keras_gradcam_demo` and you are ready to go!
