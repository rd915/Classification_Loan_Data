# Classification_Loan_Data

This project is broken up into two notebooks.  

Part 1 utilizes a logistic regression to return a balanced accuracy score, a confusion matrix, and a classification report using resampling.  It utilizes four different methods to sample the data before running a logistic regression on loan data to deteremine if the models adequately predicts whether a borrower is high or low risk. The model relies on the sample data, oversampled data, undersampled data, and a combination of over/under sampled data.

Part 2 returns the same three statistics from part 1 but utilizes two different ensemble methods using scaled data.  These two models are the Balanced Random Forest Classifier and the Easy Ensemble Classifier. 

## Technologies
This use project uses Python 3.8 and iPython in Jupyter Lab.  Windows 10 is the operating system.

## Libraries Uses
    Pandas - used to create dataframes and manipulate data in dataframes
    Numpy - used to perform calculations on data
    Pathlib - path library used to set filepath
    collections - uses Counter to count data
    sklearn - used for logistic regression, scaling, training models, and 
    imblearn - used for imblanced classification report and esemble learning modules

## Installation Guide
This requires the latest version of Anaconda, sklearn, and imblearn. 

## Examples
![](./Images/resampling_code.JPG)
![](./Images/class_report.jpg) 

## Usage

This needs to be used with datasets are that setup for classification.  Import a dataset that you want to use that has binary results as a y-value.  Run both the notebooks for the models' results. 

## Contributors
Ryan Dibeler

ryandibeler@gmail.com

## License
MIT License

Copyright (c) [2021] [Ryan Dibeler]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.




