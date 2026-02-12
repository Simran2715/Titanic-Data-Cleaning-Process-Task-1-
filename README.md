# Titanic-Data-Cleaning-Process-Task-1

->I have used pandas to clean the titanic dataset properly.
-> In this I have firstly identifyied the columns data types and there i have observed that Age and Fare column were in float values. So, I converted them into integer values. But as there were some null values present in the Age column I used Int64 to convert into int column.
After that i have identified that the Age , Cabin and Embarked columns. I filled null values for Age feature with median and as Cabing column was categorical, I filled null values with mode. And as for Emabrked column i removed completely
-> Afterwards I have encoded all the categorical features into numerical
-> At last i checked outliers with the help of boxplot and removed with the use of IQR method

