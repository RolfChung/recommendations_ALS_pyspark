# Summmary


<p>
The goal of this project is to develop collaborative filtering models applying the Pyspark implementation of the Alternating Least Squares (ALS) algorithm to the Amazon consumer review data set and the movie ratings data set. The pyspark.mllib.recommendation module offers amazing methods
to give actual recommendations for individual users or products. The methods are the main focus here and the models developed here are not hyper tuned to get better outcomes.
</p>

<p>
Alternating Least Squares (ALS) is an algorithm widely used for collaborative filtering. The aim is to find users with common interests (products, clubs, activities ...). Recommendations are based on the “birds of a feather flock together”-assumption that people who share an opinion on one topic are more likely to share again an opinion on another new independent topic than with a random third person.</p> 

<p>
According to the 
<a href="https://spark.apache.org/docs/latest/mllib-collaborative-filtering.html" target="_blank">documentation</a> the implementation in spark.mllib has the following and other parameters: 
<p>
    
<ul>
<li>numBlocks is the number of blocks used to parallelize computation (set to -1 to auto-configure).</li>
<li>rank is the number of features to use (also referred to as the number of latent factors).</li>
<li>iterations is the number of iterations of ALS to run. ALS typically converges to a reasonable solution in 20 iterations or less.</li>
</ul> 

<p>
In the project are different tasks of data exploration and preparation carried out confirming the commonplace that 80 percent (or so) of all
Data Science is data cleaning. Using the Pyspark implementation 
of Apache Spark it is helpful to remind yourself that the various API's
are addressed with specific types of languages. The SQL-API is using of course SQL and the data frames and RDDs objects are employing different
domain specific languages.
</p> 
