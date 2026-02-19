# Training a Model to Classify the Extreme Durability of Rolled-Formed Aluminum

> Our model is built in Python and uses a stacked ensemble of CatBoost and LightGBM classifiers. Each model is trained in the provided training data, and their outputs are blended to create the final predictions. Our final code is stored in the "FinalCode.ipynb" file.
> 
> While we initially experimented with simpler models such as logistic regression and a KNN-classifier, both approaches underfit our data and resulted in a low test accuracy, motivating us to consider bagging and boosting techniques as an alternatve. After implementing a baseline random forest model in scikit-learn alongside XGBoost, LightGBM, and CatBoost, we found that the CatBoost and LightGBM classifiers achieved the lowest test error rates. This led us to constructing a stacked ensemble of the two to optimize our performance.
<br>



## Group Members (Alphabetical Order)

- **James Clawson** - [@j-clawson](https://github.com/j-clawson)
- **Stanley Hsu** - [@stanleyhsu123](https://github.com/stanleyhsu123)
- **Tabitha Yu** - [@longlegdog](https://github.com/longlegdog)


