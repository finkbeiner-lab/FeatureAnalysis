# FeatureAnalysis
Feature extraction, being one of the most curial machine learning and computer vision tasks, is effective in capturing valuable and informative details surrounding the cells. This Feature Analysis focus on individual cell image that were cropped into 300x300 pixel for single cell analysis. Cell crops were preprocessed to remove any crop with edge artifacts, dead cells, clumps, out-of-focus, images with bad intensity signal, or non-centered cells. Morphological properties such as cell area, cell texture, complexity and intensity are extracted using a combination of image processing operators. These features can provide important information about cells that helps identify subtle differences between cell lines that may not be apparent through other features.

# Getting Started 

The project can be either cloned or downloaded to your device. The code is implemented in Python 3.6.13 with Jupyter Notebook, and with the requirements of the open-source libraries in the **requirement.txt** file.

## Installation
You can find the [Jupyter Notebook installation](https://jupyter.readthedocs.io/en/latest/install.html) documentation on ReadTheDocs. For a local installation, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    $ pip install notebook

You may install dependencies using:

    $ pip install -r requirements.txt

Or install each depenency with the command:

    $ pip install 'dependency'
    
## Usage - Running the notebook

Launch with:

    $ jupyter notebook

- **Feature Analysis.ipynb** - Main Notebook to run for obtaining feature CSV
- **TestingImages** - Folder contains example input images 
- **FeatureOutputs** -- Folder contains example output images and output feature CSV
- **Feature Analysis Modeling** - Folder contains R Markdown script for single or multiple timepoint statistical analysis

## Modify User Input accordingly:
<img width="969" alt="image" src="https://github.com/finkbeiner-lab/FeatureAnalysis/assets/88739975/88d2047e-3893-4951-82c3-2acdc8bf8697">

- For each feature, option to set plot_graph = TRUE to view and save images into output folder. Set as False otherwise.


