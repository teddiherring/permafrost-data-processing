**[contents](#Contents) | [setup](#Setup) | [running the notebooks](#running-the-notebooks) | [issues](#issues)**

# permafrost-data-processing
A place for the International Permafrost Association action group “towards an international database of geoelectrical surveys on permafrost (IDGSP)” to share data and processing algorithms.

## Contents

This respository has a few things in it so far:

1. [notebook for data processing](./data_filtering.ipynb): In this notebook, you can load, filter, and invert ERT datasets.
2. [data files](./data_unified): This folder contains various ERT datasets that you can load into the data processing notebook. The datasets are all in the [BERT unified data format](http://resistivity.net/bert/data_format.html).
 
## Setup

Here are step-by-step instructions for running these notebooks locally on your machine:

Install Python. You can use [anaconda](https://www.anaconda.com/download/) for this.

Clone this repository by running the following in your command line:

```
git clone https://github.com/teddiherring/permafrost-data-processing
```

Next, `cd` into the directory you just created:

```
cd permafrost-data-processing
```

You can use the provided conda environment to set up the necessary software packages:

```
conda env create -f environment.yml
conda activate idgsp
```

Next, running the following command

```
jupyter notebook
```

will open a Juputer notebook in your web browser. You now open the data_filtering notebook and start running the code!

## Running the notebooks

You can run each cell in the notebook individually by pressing  `shift + enter`, or you can run the entire notebook by selecting `Cell`, `Run All` in the toolbar.

## Issues

Please [make an issue](https://github.com/teddiherring/permafrost-data-processing/issues) if you encounter any problems while trying to run the notebooks.
