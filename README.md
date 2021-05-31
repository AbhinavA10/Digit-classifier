# Digit-Classifier

Classifying MNIST digits using Keras and CNNs

[Kaggle Competition](https://www.kaggle.com/c/digit-recognizer/overview)

Skeleton is based on [this article](https://keras.io/examples/vision/mnist_convnet/)

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