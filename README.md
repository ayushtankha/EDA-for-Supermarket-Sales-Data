# EDA-for-Supermarket-Sales-Data
<b>Project Structure</b>


Task 1: Initial Data Exploration
In this task,I import essential libraries such as NumPy, Pandas, Seaborn, Matplotlib and so on. I use Pandas to read in the data, get a brief glimpse of the first few rows, and calculate some quick summary statistics of the numeric columns.

Task 2: Univariate Analysis
In this task, I conduct univariate analysis on both continuous and categorical variables.
I first plot the distribution of customer ratings with seaborn and also overlay the mean, 25th and 75th percentile quantiles calculated using Numpy.Then I use Pandas' .hist() method to plot the distribution for all numeric variables. Using Seaborn's .countplot() method, we see the frequency distribution of 'Branch' and 'Payment' which are categorical variables.

Task 3: Bivariate Analysis
In this task, I conduct bivariate analysis on both continuous and categorical variables. I use Seaborn to plot scatterplots and regression plots to identify the relationship between customer rating and gross income. Additionally, I use Seaborn to plot a boxplot to check the difference in aggregate sales figures between the three branches of supermarkets, and to compare sales patterns between men and women. I plot a time series graph to check for trends in gross income over a period of three months.

Task 4: Dealing With Duplicate Rows and Missing Values
In this task, I identify and deal with duplicate rows and missing values in our dataset. I calculate the number of duplicate rows and delete them using Pandas. I then do the same with missing values, but instead of deleting those rows, we replace missing values by the means of their respective columns.

Task 5: Correlation Analysis
In this task, I conduct correlation analysis on the numeric variables in our dataset. I use Numpy to calculate the correlation between two numeric variables. I then use pandas to calculate a correlation matrix to show all pairwise correlations of numeric variables. Finally, I use seaborn to plot the calculated correlation matrix as a heatmap that is easily interpretable.
