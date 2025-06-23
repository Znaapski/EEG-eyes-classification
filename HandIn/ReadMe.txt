Readme file for Bioinstrumentation LGBIO2020
EEG Project 
----------------------------------------------------

Marc Phillipe Marburger and Tomás dos Santos Talento 

----------------------------------------------------

Instructions for main_notebook.ipynb 

In this notebook the complete pipeline is found. 

Some parts of the script contain plotting and visualizations that are not included in the report. These are used throughout the implementation to analyse the steps taken. These can be skipped and are marked as so with comments “Skip this” as first line in each code cell. 

The rest of the blocks can be run. 

Start by importing packages. 

Setup a model, by running one of the models in the model section of the notebook and run the train loop. The train loop is just below the model definitions. It works for all the different models. Be aware that, when running one model it will overwrite the model in memory, therefore only one of the models can be evaluated at a time. 

 


 

Instructions for project_mne_visualization.ipynb 

First run the import section. 

Second run the big block that produces power spectral density plots for the raw signals, after bandpass filtering and after notch filtering. This block takes about 40 seconds to run. 

This notebook is used for visualizing the dataset and reviewing the preprocessing steps done. MNE is useful for presenting all the EEG channels in their dedicated 2D backend. It is a simple way to scroll through the time series and see the effects of filtering etc. At the same time, it produces valuable PSD plots using built-in functions.  