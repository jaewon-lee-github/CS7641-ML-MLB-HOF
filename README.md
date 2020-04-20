# Introduction: National Baseball Hall of Fame
![Hall of the Fame](https://sportshub.cbsistatic.com/i/r/2019/01/20/830ed0de-e5e0-4b38-a343-bb4faa63fd94/thumbnail/1200x675/bb9df4b2adac35e8544aa4bd900c5a26/baseball-hall-of-fame.jpg)
The MLB hall of fame, which selects the legendary MLB players in baseball history, always draws attraction of MLB fans. Now, we are trying to predict the future hall of famers by using machine learning method which we learned on CS7641 class. On the class, we've learned both unsupervised learning and supervised learning approaches. Our team is graduate student team, so we will apply both approaches to analyze our data.
# Our Approach
## Unsupervised learning : Clustering Algorithm
We apply Kmeans, Hierarchical, DBSCAN, and GMM method to our data. These are common unsupervised clustering algorithm to classify the data points.
## Supervised learning: Deep Neural Network
We apply DNN


## Supervised

# Data Collection & Filtering
We gathered the data from the website of [Baseball Reference](https://www.baseball-reference.com/). This data are containing every players who have played or played on the MLB, so we can reduce the size of data set by filtering who is absolutely not eligible to Hall of Fame. Hall-of-Fame-eligible candidates must meet the following requirements.
<blockquote>
<p> A baseball player must have been active as a player in the Major Leagues at some time <b>during a period beginning fifteen (15) years before and ending five (5) years prior to election.</b></p>
<p> Player must have played in each of <b>ten (10) Major League championship seasons</b>, some part of which must have been within the period described in 3(A).</p>
<p> Player shall have ceased to be an active player in the Major Leagues at least five (5) calendar years preceding the election but may be otherwise connected with baseball.</p>
<p>...</p>
-- <cite>Hall of Fame official Site</cite> [1]
</blockquote>

# Analysis
## Unsupervised
## Supervised : Neural Network

  <img src="Figures/MSE_equation.PNG" alt="hi" class="inline" width="300" />

### Neural Net structure
  <img src="Figures/Nerual_Net_MLB.PNG" alt="hi" class="inline"/>

### All-time data
  <img src="Figures/Confusion_Matrix_Data1.PNG" alt="hi" class="inline"/>
  <img src="Figures/Graph_MSE_Data1.PNG" alt="hi" class="inline"/>  

### 10-year data
  <img src="Figures/Confusion_Matrix_Data2.PNG" alt="hi" class="inline"/>
  <img src="Figures/Graph_MSE_Data2_10years.PNG" alt="hi" class="inline"/>

# Conclusion
We are greate! as you know :)

# References 
[1] https://baseballhall.org/hall-of-famers/rules/bbwaa-rules-for-election
