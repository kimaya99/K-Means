# K-Means
Database setup:

1.	 By using pgAdmin GUI application, we can interact with PostgreSQL database server via an intuitive user interface.

2.	The default password needs to be provided here, in order to connect to the database.

3.	 Now the table ml is created with the columns id as integer, name as text and score and integer. Thereafter, the datasets are fed in the table.  

Execution:

1.	Ask for the no of clusters required for distinction.

2.	On basis of this number, determine initial cluster means. The first element of the database is taken as the mean of the first cluster. The second element corresponds to second cluster and so on.

3.	Here 79 is the first mean, 62 second and 92 the third mean of the third cluster. Further scores are added in the clusters to which calculated distance is minimum.

4.	A new mean of every cluster is calculated. And all students are again reassigned to the clusters on basis of the distance calculated from the mean of the respective clusters.

5.	This is reiterated until no two scores can be swapped between two clusters.

6.	JFreeChart which is an open source library developed in Java, is used within Java based applications to create the bar chart.
	

