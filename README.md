# Metabolic Syndrome

Luz Dobbins

This information will help in recognizing preconditions that can help some one with a boardline results, thus starting a change in his or her way of life before they need medical emergencies. I have had a stroke(minor), heart attack(minor) and have a family history of Diabetes.

## Metabolic Syndrome

1. Source of data

The data.world site from the preapproved list. https://data.world/informatics-edu/metabolic-syndrome-prediction

2. Brief description of data

This dataset will help me access the proprability that someone will get Metabolic Syndrome. Which could lead to other health conditions.

3. What is the target?

The target is Metabolic Syndrome

4. What does one row represent? (A person?  A business?  An event? A product?)

Each row represents a person who does or does not have the syndrome.

5. Is this a classification or regression problem?

This is a classifier because it's a yes or no question.

6. How many features does the data have?

The data has 13 features. I am not counting the seqn column it is not needed for the prediction.

7. How many rows are in the dataset?

There are 2401 rows.

8. What, if any, challenges do you foresee in cleaning, exploring, or modeling this dataset?

I see that ther is missingt data. I also need to encode the variables and scale the data. I plan on using classifier modeling , tuning of metric models(accuracy or recall) and GridSearch.

I have missing data to fix and will be imputing objects and scaling the numerical data. I plan on using classifier modeling , tuning of metric models(accuracy or recall) and GridSearch.

##Visualization

![image](https://user-images.githubusercontent.com/123646377/230627462-3d703e31-9702-44e9-af9b-96627a33154e.png)

This graft shows the difference3 between men and women and how women carry more fat and some have even higher outliers. We know wemon carry more fat to help in the hormone balance and reporoduction.

![image](https://user-images.githubusercontent.com/123646377/230627686-c2b4bedd-8ad4-43b8-be02-65e2918698e6.png)

![image](https://user-images.githubusercontent.com/123646377/230627902-7dfa3636-8cd5-43dd-b904-3211c3273d3f.png)


This graft show the Blood Glucose levels per age of the patients in this dataset. I also added the normal, pre-diabetic and Diabetic ranges. which is what Blook Glucose detects.
Informational chart sourced from diabeticmealsplans.com (https://diabetesmealplans.com/5080/diabetes-blood-sugar-levels-chart-printable/)

##Metrics
I used the KNeighbors matrics with PCA to get the best score of 82% accuracy on the test data. When I only used the KNeighbors it was stuck at a 81% accuracy

Training accuracy: 0.8827777777777778 

Testing accuracy: 0.826955074875208

### I belive that with more data we can look at future recommendations to patients health just from a blood work. 
-I would like to recommend to have a Medical doctor look at these finding and work with us in narrowing down what the best test and resources would be to improve thes finding. I would love to sit with a doctor to ecplain these test better and maybe recommend diffirent items to predict on a model.
-I recommend a larger patient dataset will help these finding, also for now Diabetes has been well studied and recommendations are being made to patients about their predesposition so we can drop that from this dataset.
