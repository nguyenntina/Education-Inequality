# DATA3320 - Project 2: Education Inequality in the U.S.

## Description:

This project addresses educational inequality in U.S. high schools by focusing on students' performance on college entrance exams like the ACT and SAT. We will be using data science methodology and creating plots to answer this question.

## Requirements:

Software and packages that will be used include:

1. Python
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit Learn
6. Colab

## Data:

The primary data set is from EdGap and the secondary data set is from the National Center for Education Statistics.

The EdGap data source can be found at: https://www.edgap.org/#5/37.718/-95.998

The NCES data source can be found at: https://nces.ed.gov/ccd/pubschuniv.asp

Since the NCES data is too large for Github, it can be accessed from the drive link: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view?usp=sharing 

## Data Preparation:

Steps took to prepare the data include:

1. Inspect data set
2. Convert data types where necessary
3. Dropped unnecessary columns
4. Join the EdGap and NCES sets
5. Check for negative quantitative values
6. Perform a train - test split
7. Normalize data
8. Impute missing values

The file "education_inequality_data_preparation.ipynb" performs the data preparation. The file "test_dataset.csv" is the cleaned test data set and "training_dataset.csv" is the cleaned training data set.

## Data Analysis:

Steps took to analyze the data include:

1. Propose an additional step
2. Create plots to answer proposal
3. Use linear regression to see if socioeconomic impact act scores
4. Interpret plots

The file "education_analysis.ipynb" performs the data analysis and the file "education_analysis_slides.pdf" is the analysis slide deck.

## Author:
The author of this repository is Tina Nguyen.

## License:
This project is licensed under the terms of the MIT license.

