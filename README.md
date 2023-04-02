# Online-Retail-Customer-Segmentation

We have done this project through team coordination, our team contains four members i.e Umesh pardeshi, Suvarna gadakh, Sakshi suthar, and Priyanka Kumari. the data set given by a company that sells unique gift items online. The data set given in the excel format contains a total of 541909 rows and 8 columns. 8 columns include data as follows.

InvoiceNo contains unique bill number given data in the form of object data type
StockCode contains a unique stock/gift code given data in the form of object data type
Description contains a brief description of gift items given data in the form of object data type
Quantity contains the total number of gift items quantity given data in the form of int data type
InvoiceDate contains the date of purchase given data in the form of datetime data type
UnitPrice contains gift price per item given data in the form of float data type
CustomerID contains customer id given data in the form of float data type
Country contains the respective country name belonging to the customer
firstly we loaded the given data set in the colab environment bus using the pandas read function. then we have to check the data first look using the head function. after overviewing the data set, we have done exploratory data analysis. we extracted some useful data insight by comparing variables using the arithmetic operator. after that, we plotted graphs using plotting, seaborn, and plots to visualize all insight found in exploratory data analysis. then we have done hypothesize testing on resultant variables, Hypothesis Testing is a type of statistical analysis in which you put your assumptions about a population parameter to the test. It is used to estimate the relationship between 2 statistical variables. to perform a hypothesis test we used the z test, When the variances are known and the sample size is high, a z-test is a statistical test to assess if two population means are different. A hypothesis test known as a z-test is one in which the z-statistic has a normal distribution. A z-statistic, also known as a z-score, is a numerical representation of the outcome of a z-test. then we did Feature Engineering & Data Pre-processing, in this part we handles missing values, prepare data for modeling, and handled outliers and data scaling. the final part is data modeling here we have formed clusters using Kmeans cluster and silhouette analysis and finally, we have visualized all clusters using dendrograms. in this way, we have done an Online Retail Customer Segmentation unsupervised capstone project. here are insights we get,

White Hanging heat T-Light holder is the most demanding gift of all.

Lunch bag black skull is the least demanding gift of all.

The UK has placed maximum orders for unique gift items.

After the UK, Germany placed maximum orders for unique gift items.

The UK has to purchase a total of $4.2 million in gift items.

The Netherlands has purchased a total of $200 k gift items.

Online retail gift shop generates $ 8 + million in revenue from the UK only.

WORLD WAR 2 GLIDERS is the most bought item ever with 53847 quantity.

DOT stock code gift generated a total of $ 2,06,245 in revenue.
