## austin-animal-center-classifier
This repository contains different models, that were used to predict outcome animal type for AAC shelter 

Used dataset: https://www.kaggle.com/aaronschlegel/austin-animal-center-shelter-outcomes-and/data

### Short description of the dataset:

| Feature name         |  Feature description                                  |  Type   |
|----------------------|-------------------------------------------------------|---------|
| age_upon_outcome     | Age of the animal at the time at which it left the shelter. | String |
| animal_id            | - | String |
| animal_type          | Cat in our case. | String |
| breed                | Animal breed. Many animals are generic mixed-breeds, e.g. "Long-haired mix". | String |
| color                | Color of the animal's fur, if it has fur. | String |
| date_of_birth        | - | DateTime |
| datetime             | Timestamp of outcome | DateTime |
| monthyear            | - | DateTime |
| name                 | - | String |
| outcome_subtype      | - | String |
| outcome_type         | Ultimate outcome for this animal. Possible entries: transferred, euthanized, adopted. | String |
| sex_upon_outcome     | - | String |
| count                | - | Numeric |
| sex                  | - | String |
| Spay/Neuter          | - | String |
| Periods              | - | Numeric |
| Period Range         | - | Numeric |
| outcome_age_(days)   | - | Numeric |
| outcome_age_(years)  | - | Boolean |
| Cat/Kitten (outcome) | - | String |
| sex_age_outcome      | - | String |
| age_group            | - | String |
| dob_year             | - | Numeric |
| dob_month            | - | Numeric |
| dob_monthyear        | - | DateTime |
| outcome_month        | - | Numeric |
| outcome_year         | - | Numeric |
| outcome_weekday      | - | String |
| outcome_hour         | - | Numeric |
| breed1               | - | String |
| breed2               | - | String |
| cfa_breed            | - | Boolean |
| domestic_breed       | - | Boolean |
| coat_pattern         | - | String |
| color1               | - | String |
| color2               | - | String |
| coat                 | - | String |



### Outcome binary metrics:

| Model name                  | Accuracy real | AUC-ROC real | Average |
|-----------------------------|---------------|--------------|---------|
| Logistic regression         |        |       |  |
| Random forest with 80 trees |        |       |  |
| Bootstrapped decision tree  |        |       |  |
| Bagging cllassifier         |        |       |  |
| KNN classifier with 98 NN   |        |       |  |
| Decision tree               |        |       |  |
| Linear regression           |        |       |  |
