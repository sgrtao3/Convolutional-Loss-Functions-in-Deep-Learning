# ACSE9 Final Independent Project
## Convolutional Loss Functions in Deep Learning 


<!-- TABLE OF CONTENTS -->

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#Prerequisites">Prerequisites</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This project presents optimisation strategies on adaptive loss functions with Wiener filters in deep learning.

Features:

* Methods for both 1D and 2D calculation
* Improvements in both accuracy and computation difficulty
* Tests for all the implementations
* Elegant visualization
* Project report with detailed explaination


## Prerequisites

* Python 3.7 or above
* CUDA and Jupyter libraries
* GPU Accelerator

## Usage

There are four notebooks and one report within the repo.

* Notebook 1 (1D_method1.ipynb)

This notebook contains a way of calculating 1D adaptive loss function with Wiener filter without using torch.roll. Note that this notebook is set up to be run on Google Colab with GPU.

* Notebook 2 (1D_method2.ipynb)

This notebook contains another way of claculating 1D adaptive loss function with Wiener filter using torch.roll. Note that this notebook is set up to be run on Google Colab with GPU.

* Notebook 3 (2D.ipynb)

This notebook contains a way of calculating 2D adaptive loss function with Wiener filter. Note that this notebook is set up to be run on Google Colab with GPU.

* Notebook 4 (Test.ipynb)

This notebook provides the tests of adaptive loss functions with Wiener filter for all the methods implemented above. 

* PDF file (FinalReport.pdf)

This report presents details about this project, including introduction, software description, implementation, test, results, discussion and conclusion.


<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

* PyTorch
* Google Colab
