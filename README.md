# CS3: Case Study Reproduction

## Welcome!

Welcome to the Movie Poster Person Detection case study repository.  In this repo, you will find the necesssary items and steps to reproduce the results necessary for this case study.

<img width="474" height="262" alt="Screenshot 2026-05-04 at 8 26 24 PM" src="https://github.com/user-attachments/assets/18070996-9a33-4f4e-b2c7-536816a5c42b" />


## Instructions for Reproduction 
To reproduce our results, first run the file titled ‘data_collection.ipynb’.  This will produce a metadata .csv file and a folders of images for the 10,000 movie poster images.  Ensure all necessary packages are downloaded for this first step.  Given the streaming of the data, the preprocess cleaning will also be completed by this script.  These folders are also available for download titled ‘filtered_poster10k’, and ‘movies_10y_metadata10k.csv. Download ‘ProjectPosters.yolov8’ directory.  Run the ‘yolo_modeling_labeled.ipnyb’ script to train the model on the custom class. Next, generate results .csv and append to metadata.csv.  This data can also instead be downloaded in the file titled ‘movies_10y_metadata_with_counts_both.csv’. 

To begin modeling, download and run the ‘gradient_boosting_and_plots.ipnyb’ file. Ensure all packages are installed for this step. For the regression modeling, download and run the 'linear_regression.ipynb' file Ensure all of its packages are installed as well. 

## Software & Platform
For data downloading and preprocessing, we used Jupyter Notebook with python. The following packages will need to be installed for downloading and preprocessing: “load_dataset”, “datetime”, “pandas”, and “os”.  

For modeling, analysis, and evaluation with the Yolov8s model, we used python in a Jupyter Notebook.  The packages used in these steps were “ultralytics”, “pandas”, “os”, “matplotlib”, “numpy”, and “sklearn”.  The packages not previously used, “ultralytics” and “sklearn”, need to be installed for modeling, analysis, and evaluation.

For creating the Gradient Boosting model as well as the partial dependence plot, we again used Jupyter Notebook with python. The following packages were used: "pandas", "numpy", "scikit-learn" (specifically train_test_split, GradientBoostingRegressor, mean_squared_error, and PartialDependenceDisplay), and "matplotlib".

For the regression modeling, "pandas", "numpy", "matplotlib", and "sklearn" were used in a python notebook file.  These packages have been installed in pervious steps.

All work was completed on Mac OS.
