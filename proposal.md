# Project Proposal

## Research Question
Can passenger class, sex, age, and fare predict whether a Titanic passenger survived?

## Dataset
- **Name:** Titanic - Machine Learning from Disaster
- **Source:** Kaggle (https://www.kaggle.com/c/titanic)
- **Access link used:** https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv
- **Size:** 891 rows, 12 columns (PassengerId, Survived, Pclass, Name, Sex, Age, SibSp,
  Parch, Ticket, Fare, Cabin, Embarked)

## Related Work (Two-Source Scan)

1. **"Predicting Survival on the Titanic" (Kaggle competition writeups/kernels)** —
   Numerous public Kaggle notebooks on this dataset consistently find that sex and
   passenger class are the strongest predictors of survival, reflecting the historical
   "women and children first" evacuation protocol and unequal lifeboat access across
   ticket classes. Most approaches use logistic regression, decision trees, or random
   forests, reaching 75-85% test accuracy.
2. **"Machine Learning on the Titanic Dataset" (general ML tutorials, e.g. towardsdatascience.com
   walkthroughs)** — These typically emphasize the importance of feature engineering
   (extracting titles from names, family size from SibSp/Parch) to boost accuracy beyond
   the basic feature set, and note that Age and Cabin have substantial missing data that
   must be handled carefully.

## Planned Approach
This project uses a simpler feature set (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked)
with a logistic regression model, focusing on establishing a clear, interpretable baseline
rather than maximizing accuracy through heavy feature engineering.
