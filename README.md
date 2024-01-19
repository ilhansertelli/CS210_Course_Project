# CS210_Course_Project

In this project, I aimed to analyze my personal health activity data by using various tools in Python.
Firstly, I extracted the data from Apple Health application and I parsed the XML file by using BeautifulSoup.
After creating the dataframe, I divided the main dataframe into sub dataframes in order to examine the different
features such as step count, distance walked, basal energy burnt and so on in order to facilitate the analysing
process.

I utilised the charts and graphs provided by seaborn and matplotlib libraries in Python in order to visualise
and present my data. By checking the charts that are made, I looked for patterns in order to find out whether 
I can verify my hypothesis or not.

I used the t-test in order to check the correctness of my hypothesis and by the statistical tests, I tried to
find a p-value less than 0.05. After finding a p-value less than 0.05, I decided to apply a simple machine
learning model on my project

Firstly, I started the simple machine learning process by using applying linear regression on my distance walked
data in 2022. After implementing linear regression, I used mean squared error in order to determine the quantity of
total error in the prediction.

Lastly, I divided my 
