# Recipe-site-traffic
Data analysis and modelling on a fictional data set about a company that creates recipes and meal plans.

Data set available on kaggle: https://www.kaggle.com/datasets/nourelimane/recipe-site-traffic-2212/data

Analysis performed using Jupyter Notebook (Python) with description and full report contained in the notebook.

# Summary

Tasty Bytes was founded in 2020 in the midst of the Covid Pandemic. The world wanted inspiration so we decided to provide it. We started life as a search engine for recipes, helping people to find ways to use up the limited supplies they had at home. Now, over two years on, we are a fully fledged business. For a monthly subscription we will put together a full meal plan to ensure you and your family are getting a healthy, balanced diet whatever your budget. Subscribe to our premium plan and we will also deliver the ingredients to your door.

The team have noticed that if they display a popular recipe on the homepage, the traffic of the website goes up by up to 40% which leads to more subscriptions. Therefore the company would like a data scientist to:

- Predict which recipes will lead to high traffic.
- Correctly predict high traffic recipes 80% of the time.
- Make recommendations for next steps.

The dataset contains recipe id, calories, carbohydrates, sugar, protein, category, servings and if the recipe generated high traffic when posted on the homepage.

# Conclusion

To have the highest chance of predicting which recipe will lead to high traffic, I recommend deploying the random forest classifier model into production. By implementing this model, we will correctly predict which recipe will lead to high traffic 77% of the time, with most of the failed predictions being high traffic recipes classified as low traffic.
