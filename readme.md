# Weekly Project 4
The purpose of this project is to do some experimenting with `numpy`, particularly around *shaping* your date so you can perform the data analysis you need, along with practicing some standard *data aggregation* techniques.

## Get the project
From your terminal / command line, navigate to a directory where you'd like to store your work.  Then, clone the assignment's github repository and `cd` into the directory to begin working.

```
git clone https://github.com/scottfrees/cmps530-wp5.git
cd cmps530-wp5
```

## Getting the data
This project is set up with DVC, so do a `dvc pull` to get the `temperature.csv` file.  This file contains daily temperature readings (max and min) from two weather reporting stations in NJ - Elizabeth NJ (Station USC00282644) and Conoe Brook NJ (Station USC00281335) - from 1893 until the end of April 2020.  We'll be using the data to track some statistics about daily temperatures in NJ over time.  For the purposes of this project, we don't care much about having two temperature samples for a given day - we just want one.  

## Data Analysis
Your data analysis should take place within the *jupyter notebook* provided - `temperature.ipynb`.  You have been given step by step instructions on how to perform the various data reshaping and analysis tasks.  Try to do this exactly as specified in the notebook's markdown cells, but also feel free to expand on the analysis as well.

```
jupyter notebook
```

