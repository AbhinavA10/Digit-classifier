# Digit-Classifier

Classifying MNIST digits using Keras and CNNs

[Kaggle Competition](https://www.kaggle.com/c/digit-recognizer/overview)

Skeleton is based on [this article](https://keras.io/examples/vision/mnist_convnet/)

Here is a cool [dataset explorer, for MNIST](https://knowyourdata-tfds.withgoogle.com/#dataset=mnist&tab=STATS&group_by=__none__&select=kyd%2Fmnist%2Flabel&draw=kyd/mnist/label,,&item=test%5B0%25%3A2%25%5D_142)

## Steps to setup environment:
- `conda env create --file environment_digits.yml`
- `conda activate digits`
- `jupyter labextension install @jupyter-widgets/jupyterlab-manager` [Source 1](https://stackoverflow.com/questions/49542417/how-to-get-ipywidgets-working-in-jupyter-lab), [Source 2](https://ipywidgets.readthedocs.io/en/latest/user_install.html#installing-the-jupyterlab-extension)
- `jupyter-lab`

## To update conda env from `.yml` file:

```
conda activate digits
conda env update --file environment_digits.yml
```

## Next Steps:
- cleanup code
- train on Kaggle
- view graphs in Tensorboard
- use model on our own custom image
- Keras has a reshape layer 
    - https://keras.io/api/layers/preprocessing_layers/core_preprocessing_layers/normalization/  (preprocessing image)
    - https://keras.io/api/layers/preprocessing_layers/image_preprocessing/ (preprocessing image)
- Plot output of Conv2D, and kernels (after training) for interest
    - https://towardsdatascience.com/visualizing-intermediate-activations-of-a-cnn-trained-on-the-mnist-dataset-2c34426416c8 
    - https://machinelearningmastery.com/how-to-visualize-filters-and-feature-maps-in-convolutional-neural-networks/ 

## TODO after testing model
- add Data Augmentation if needed
    - e.g. shifting and scaling so image does not have to be centered?