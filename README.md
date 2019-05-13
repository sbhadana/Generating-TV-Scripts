# Generating TV Scripts

This project was developed as a part of Udacity's Deep Learning Nanodegree. In this project, i have created a Recurrent neural network from scratch using pytorch. The Neural Network I generated a new, "fake" TV script, based on patterns it reconginzes in this training data.


### Prerequisites

* Python 3
* Numpy
* Pandas
* MatPlotLib
* OpenCv
* Pytorch

### Install

1. Download the project materials from our GitHub repository. You can get download the repository with
  ```
  git clone https://github.com/sbhadana/Generating-TV-Scripts.git
  ```
 2. Download anaconda or miniconda based on the instructions in the [Anaconda documentation](https://docs.anaconda.com).

 3. Create a new conda environment:
  ```
  conda create --name RNN python=3
  ```
 4. Enter your new environment:
  * Windows: >>  ```activate RNN ```

 5. Ensure you have numpy, matplotlib, pandas, and jupyter notebook installed by doing the following:
  ```
  conda install numpy matplotlib pandas jupyter notebook
  ```
 6. Run the following to open up the notebook server:
  ```
  jupyter notebook dlnd_tv_script_generation.ipynb
  ```
 7. Execute all the cells in the code.

### Project Contents

 - Get the Data
 - Explore the Data
 - Implement Pre-processing Functions
 	- Lookup Table
 	- Tokenize Punctuation
 - Pre-process all the data and save it
 - Check Access to GPU
 - Input
 	- Batching
 	- Test your dataloader
 	- Sizes
 	- Values
 - Build the Neural Network
 	- Define forward and backpropagation
 - Neural Network Training
 	- Train Loop
 	- Hyperparameters
 	- Train
 - Generate TV Script
 	- Generate text
 	- Generate a new script


## Built With

* Python 3

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* The data comes from Udacity.
