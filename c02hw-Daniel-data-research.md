#Daniel's dataset research-Abalone data


I have chosen the abalone data to use for my dataset research project. The source of my dataset comes from UC Irvine's Machine Learning Repository [website](http://archive.ics.uci.edu/ml/datasets/Abalone?pagewanted=all).
The dataset and documentation can be found in the following links:
* [Data](http://archive.ics.uci.edu/ml/machine-learning-databases/abalone/abalone.data)
* [Documentation](http://archive.ics.uci.edu/ml/machine-learning-databases/abalone/abalone.names)


##### 1. What are the structure and contents of your dataset? (Number of records, columns, missing values, etc.)

The Abalone data contains various measurements collected on a sample of 4,177 abalone. From the documentation, we see that there are nine variables. The names of the variables along with other relevant information are summarized below:

|Variable name|Data type|Units|Description|
|:------------|:--------|:----|:----------|
|Sex|nominal|n/a|M, F, and I (infant)|
|Length|continuous|mm|Longest shell measurement|
|Diameter|continuous|mm|Widest shell measurement|
|Height|continuous|mm|Thickness with meat in shell|
|Whole weight|continuous|g|Weight of whole abalone|
|Shucked weight|continuous|g|Weight of meat|
|Viscera weight|continuous|g|Weight of gut (after bleeding)|
|Shell weight|continuous|g|Weight of shell after being dried|
|Rings|integer|n/a|Rings + 1.5 gives the age in years|  


##### 2. What is the history of your dataset (How was it created?)

According to the documentation, the database was first created by *the Department of Primary Industry and Fisheries, Tasmania*. In particular, *the Marine Resources Division* of *the Marine Reserach Laboratories - Taroona*. And it was donated to UC Irvine's Machine Learning Repository by Sam Waugh who was associated with *the Department of Computer Science* at *the University of Tasmania* in December 1995.


##### 3. Has your dataset been written about? What have others used it for?

Referring again to the documentation, at least a couple of academic papers have been written using this dataset:
*Sam Waugh (1995) "Extending and benchmarking Cascade-Correlation", PhD thesis, Computer Science Department, University of Tasmania.
*David Clark, Zoltan Schreter, Anthony Adams "A Quantitative Comparison of Dystal and Backpropagation", submitted to the Australian Conference on Neural Networks (ACNN'96).

Furthermore, the dataset has been used by many different individuals and organizations for exploring data science/data analysis concepts. The *Statistical Consulting Group* at the *San Diego State University* has written a [post](http://scg.sdsu.edu/linear-regression-in-r-abalone-dataset/) on performing linear regressions in R using this dataset.


##### 4. How do you acquire and load the dataset into R? (Include code.)


##### 5. What are some simple statistics describing the dataset?


