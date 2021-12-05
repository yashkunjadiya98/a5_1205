# a5_1205
Data Archive Activity
# Loading necessary libraries
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
These are the libraries using import function.
# Loading the dataset using 'pandas' library
df = pd.read_csv("/Users/yashkunjadiya/Desktop/uni docs/1200/datasets/HousingNew.csv")
here we read and load the data set of housingNEw.csv file from harddrive.
# df.head()
Using head function in python we retrive rows froms the data set
# df.tail()
Using tail function in python we retrive last five rows froms the data set
# df
we used df function called data frame for retrive all data set.
# df.shape
This shape function we used for to get shape of data.
# df.size
By using Size function we can retrive the size of the dataset
# df.info()
The info() functiomn is used to print a concise summary of a dataframe.
# df1 = df.drop('ID', axis=1
Here the the drop() function we used to drop ID lebel from row & coloum.
# df1.describe()
Using drscribe() function we can get key insight from the dataset
# df1.describe().T
This function we used for transpose the dataset.
