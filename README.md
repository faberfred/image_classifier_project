[//]: # (Image References)

# Image Classifier Project

### Introduction & goal of the project

The objective of this project is to *implement* and *train* an image classifier to recognize different species of flowers. 

We'll be using [this dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) of 102 flower categories, you can see a few examples below.

<img src="./assets/Flowers.png" width="400" alt="Flowers"/>

The project is broken down into multiple steps:

* Load and preprocess the image dataset
* Train the image classifier on the dataset
* Use the trained classifier to predict image content
  

### Setup
The setup description applies to *Linux Ubuntu 18.04 / 20.04* with pre-installed *Anaconda* and a *CUDA* enabled graphics card.

Create and activate a new conda environment named *ai* with *Python 3.6*:
```python
conda create --name ai python=3.6
conda activate ai
```
Now install the latest [*PyTorch*](https://pytorch.org/) version together with the *CudaToolkit 10.1*:
```python
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
```

To use *Jupyter Notebook* run the following code:
```python
conda install ipykernel jupyter
jupyter notebook
```

### System Settings

- Python version: *3.6*
- PyTorch: *1.4.0 and 1.5.0*
- Cuda: *CUDAToolkit 10.1*
- Operating system: *Ubuntu 18.04 and 20.04*
