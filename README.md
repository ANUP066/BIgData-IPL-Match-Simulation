An IPL cricket match simulation done using big data technologies using two approach.

Technologies used-Hadoop,Spark

Approach 1- Is the normal approach going through ball by ball and predicting outcomes.The batsmen and bowler statistics have been taken from the cricinfo website and based on that clusters have been made using k-means clustering technique.Clusters have been used for prediction whenever a new batsmen or bowler not there in the records collected arrives.For more information about this method refer the "2018-BigData-ClassProjects.pdf".

Approach 2-A decision tree approach where a training data set is given to the decision tree model and based on that predictions made.Spark mllib library gives us the required decision tree model.
