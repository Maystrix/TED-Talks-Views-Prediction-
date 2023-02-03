# TED-Talks-Views-Prediction-
Supervised Learning -Regression

![image](https://user-images.githubusercontent.com/102039796/216668604-7e499001-7f76-48ae-ad62-c5b62d175085.png)

## Summary ![rainbow](https://user-images.githubusercontent.com/102039796/216668803-7f6a97f1-9dff-419e-83e9-c4569092862c.png)

The dataset contains over 4000 TED Events and the main objective was to build a model for views generated for these events. The dataset was feature-rich but was heavily influenced by outliers , which were handled using Interquartile Range (IQR) method. Many important insights were received from the features extracted from the dataset using Feature-Engineering. One-Hot Encoding was performed for binary conversion of object type data-types. Regression Models implemented for analysis were Linear Regression along with regularizations Lasso, Ridge & Elastic-Net followed by Decision Trees and its ensembles techniques. Models were evaluated on their MAE, R2 score which concluded with Random-Forest being the best of all the models with a train-score of 98% and test-score of 80% and least MAE .Feature importance were calculated using SHAPLEY method and it was found that features generated using feature engineering were the most important and impacted the model prediction the most. It was concluded that TED events can be focused more on the theme of Self-Improvement , Education, Personality development within the time-limit of 16 min with 4-7 topics for each event and make the event available in as many languages as possible .These factors were associated with wide-spread reach of TED events and its popularity .Also , if the events are published at the start of the Year , close to March month , max views were generated.It was concluded that on an avg the views generated for any new TED events following the above features and factors could fetch an average views of 2.17 million.

## Conclusion ![rainbow](https://user-images.githubusercontent.com/102039796/216669238-a29ca918-71c7-4aeb-ad62-542479d052e2.png)

* Focus should be given on specific topics, number of topics and available languages count.
* Overall theme of majority of the events focus on Education & Self-development
* Events should be made available in as many languages as possible
* Those speakers should be selected, who have made a significant contribution in their respective field and possess significant knowledge
* Events should be published online mostly on Friday and in the month of March
* Avg views prediction for new TED event wrt given dataset will be around 2.17 million
