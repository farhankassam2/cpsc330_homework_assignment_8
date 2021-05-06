# hw8

## Submission Details

### Summary 
This repository contains all the files committed for my final CPSC 330 assignment at UBC. I am not breaching any privacy policies at UBC because this assignment was very open-ended in which all solutions were purely custom developed by my partner, Raghav, and I. It was meant for us to develop a program that can be used and demonstrated in the real-world, to be shared with employers to showcase our expertise in machine learning techniques. 

The main purpose of our analysis was to make price predictions of an Airbnb listing given Airbnb listings in new york, using features of relevance in an Airbnb listing. These features can be either numeric or categorical in nature and can partain to phycial attributes such as the location and type of room of a listing or to characteristics of the posting on the Airbnb web platform such as the words used in the title or minimum number of nights that guests are required to stay to be eligible to book for a stay.

### Codebase & file structure
The main code is located at `hw8.ipynb`. There is also a full-blown explanation of the code in `exercise3_blog_post.ipynb`, explaining in simple English terminology, the purpose of the data collection and analysis, how the data was peprocessed and how hyperparameters were tuned, as well as resulting predictions and accuracy of these predictions based on certain metrics used.

Data was generously obtained from Kaggle and is located [here](./AB_NYC_2019.csv). The dataset can also be viewed directly in [Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data).

Now ofcourse, you could argue that the hyperparameters could be tuned better or there are alternative ways I could have prre-processed the data before passing it into the models however, this is just the solution(s) we came up with given the time constraints of the assignment. We were also asked to use and compare only three models depending on whether we were solving a categorical or regression problem, which is why we limited to using 3 models. Given that the course is complete, I plan to use better hyperparameters and pre-process the data in a better way to obtain more accurate predictions with the test sets in the data. I will use this repository as a way to update this code as I make the aforementioned changes.

### Ethical Considerations

In addition to that, I would also like to state that I have remained very integral and cconsiderate of the distinction between our training and test data, such that test data was never previously viewed, tweaked or used in training the models. There are major ethical considerations in this realm, such that test sets shall only be used for testing the accuracy of models and not actually training the model (commonly referred to as The Golden Rule), which can skew prediction in accuracy in favour of the model. Therefore, I have adhered to these global ethical guidelines, supervised by our TAs and professor, to truly test how well our models perform. 

Please watch this repository for updates in the code and explanation in the near future as I try to make the model more accurate in its predictions.

### The Purpose of these Models

The purpose of our machine learning models are two-fold:
1) To develop data-driven program in which hosts can input certain characteristics of their Airbnb listing, such as the number of days in he year it is available, the roomtype and the neighbourhood, to help them determine the optimal price to set for their listing. To put our model to test, we will use our best performing model to predict the price of this a listing given a pre-determined set of features as input based on the trends analyzed in past data on listing prices.
2) To help existing hosts know which factors of their Airbnb listing is the most or least significant in determining the price of their listing. To see how hosts may use the model to their benefit, we will show which features of an Airbnb listing are important in predicting the target label (i.e. price).

### Type of Problem
Because our target label is continous in nature without a pre-existing set of unique categories, our problem is a regression problem and we are using three linear machine learning models to gain insight on the provided dataset.

### Acknowledgements

Thanks to my partner, Raghav, on working on this, and several other assignments in the course, with me, and being the motivating and inspiring person he is to ignite part of my passion and curiousity in machine learning models, leading up to the completion of CPSC 330.

Please enter details of your submission here, per the [homework submission instructions](https://github.students.cs.ubc.ca/cpsc330-2019w-t2/home/blob/master/docs/homework_instructions.md).

**Basic Details:** <br>
**Student 1:** <br>
Name: Farhan Kassam <br>
**Student 2:** <br>
Name: Raghav Thakur <br><br><br>

[Here's the link to my report](./hw8.ipynb) <br>
[Here's the link to my blog post for exercise 3](./exercise3_blog_post.ipynb)
<br><br>
Extra dependencies used in my report:

Sources:

Additional explanations:

