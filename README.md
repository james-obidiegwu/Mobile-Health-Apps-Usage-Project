# Mobile-Health-Apps-Usage-Project
1.	To analyse and identify the features and characteristics most valued by App users that influence their rating and choice of app.
2.	Which demographical factors—gender, age, prefecture, region, occupation, marital status, and number of children, OS type, app purpose, user experience—interactive, entertaining, performance, ease of use, navigation, layout, graphics, visual appeal, visual information, quality of information, credibility as well as privacy issues—confidentiality and privacy, ethics, and rating are associated with the use of a particular category of mobile health apps?
3.	Build a model to predict the rating of Apps by users.
4.	Build a model to predict if app users would recommend the app to other patients or stakeholders.
5.	To predict if app users would pay for apps or prefer to use apps that are free.
DISCUSSION/MODEL EVALUATION
We built several classification models, including a logistic regression model, a K-Nearest Neighbor model, a decision tree model, and a Naive Bayes model. We also built tree-based models like Random Forest and Gradient Boost. The models were built using a balanced dataset. According to the model comparisons, the Decision Tree model had the best accuracy, precision, recall, and f1-score for predicting users who would pay for the app. K-Nearest Neighbor had the highest accuracy, precision, recall, and F1-score (75%, 77%, 75%, and 72%, respectively) for the prediction of users recommending apps. Furthermore, for the tree-based models to predict app rating, the Random Forest model had the best performance of 86 % across all metrics (table 8). In conclusion, app ratings, visual appeal, and the quality of the information are the most significant factors that influence app selection.


Chapter 6:  STRENGTH AND LIMITATIONS OF STUDY

The strength in this study includes going beyond the analysis of the usage of different categories of mhealth apps to building a model to predict the app users that would likely recommend and pay for the apps. The study focused on the various categories of mHealth apps rather than one specific type of app.
One of the study's drawbacks is the lack of a follow-up interview to assess any changes in the user experience. These data represent a moment in time, and a long-term study would more accurately reflect changes in user experience. The sample size was quite limited, which is another drawback. 
For generalizability, the study's findings require more validation. Another limitation is that the pilot study only lasted 12 weeks; it is uncertain whether user compliance would have persisted for longer. Also, the small data points influenced the performance of the machine learning algorithms.


Chapter 7:   FUTURE RESEARCH/RECOMMENDATIONS

There were sufficient participants for a preliminary study, but the sample is not representative. Additional study is required, including samples with more participants. Future studies should propose on how to consider the variety in the demographics of mHealth apps users.
Formal qualitative assessments should be taken into consideration, along with usability testing and other app quality ratings.
This paper offers vital recommendations to developers and behavioural scientists interested in developing mobile applications intended to encourage long-term modifications in health-related behaviour. We advise future mHealth apps to consider potential promoters and challenges to participant engagement. We recommend researchers to focus their attention on app design elements that affect the user experience for engagement and sustainability (e.g., ease of use, quality of information, visual appeal). There should be greater consideration given to creating applications with captivating features.
Making relevant, helpful, and easy-to-use apps should be the aim of all developers. The research findings will be helpful for future study on the many strategies and factors to consider in other to improve mHealth app engagement and retention.


Chapter 8:   CONCLUSION

In summary, the major objectives of this project are to discover the elements that affect app choice and to develop a machine learning algorithm to predict app ratings and whether users will recommend and pay for the apps. Additionally, to ascertain the demographic background of the app users; Age, employment, and marital status were found to be general predictors of mobile health apps. Furthermore, different populations choose various mobile health app categories, which indicates that the use of a particular category of mobile health application is connected in various ways with factors like gender, age, marital status, and privacy concerns. Importantly, the research shows that the quality and reliability of the information on the apps, their ease of use, and their visual appeal are the most crucial factors app users consider when choosing an app.
To predict user ratings and ascertain whether users would recommend and pay for the apps, we used machine learning (ML) algorithms. Specifically, we implemented and compared the performance of five linear model classifiers and three tree-based models, then used the best performing classifier, with F1-score of 86%, to predict our models. Then, using feature importance technique, we determined the factors influencing the choice of mHealth apps.

 

 



