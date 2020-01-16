## student-performance-prediction
### Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.X
### Project Motivation
The objective of the project was to analyze how various factors affect student performances when taking a specific course. Throughout the analysis we tried to answer following questions.
1. How effective are the traditional academic indicators?
2. How does the Socioeconomic factors impact the final grade?
3. Does attendance has any contribution towards the final grade?
4. Which behaviors are vital for a good grade?
In analysing the numberic attributes we used the correlation matrix to identify the type of influence these attributes have. The categorical attributes were analysed by simply averaging final grade grouped by the attributes in interest. 
### File Descriptions
There are couple of Jupyter notebooks available here
1. Data Understanding - contains the data exploration and analysis steps
2. Modelling - contains the modelling steps including data preparation, model training and evaluation
The data set is available in the student-mat.csv file 
### Results
The finding are elaborated in the following [article](https://medium.com/@sanjayaben/can-the-teachers-predict-how-their-students-would-perform-369314f0a457)
Key findings 
1. Continuous/interim assessments seem to standout as strong indicators of the final grade achieved by students.
2. The guardians who are educated has more influence on students while staying with parents seems to help them perform better. Also the urban setup with facilities like home internet also seems to positively impact performance.
3. The absences do not demonstrate a negative correlation towards the final grade as expected. It could be that the secondary school students cope up with absences better compared to primary students.
4. Behavioral attributes are complex to analyze and may need to be looked at in the context of the culture that exists within the sample. i.e. the conclusions may not be true in all cultural contexts.
### Future work
We can alternatively try to use a classification model which would predict if the final grade is going to be "good" or "bad". For this we need to first transform the G3 into a categorical label, which we can then use to train the model.  This would be a better use of the data set in it's current form.
### Licensing, Authors, Acknowledgements
Must give credit to UCI for the data. You can find the Licensing for the data and other descriptive information at the UCI link available [here](https://archive.ics.uci.edu/ml/datasets/Student+Performance). Otherwise, feel free to use the code here as you would like!
