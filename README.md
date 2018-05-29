## austin-animal-center-classifier
This repository contains different models, that were used to predict outcome animal type for AAC shelter 

Used dataset: https://www.kaggle.com/aaronschlegel/austin-animal-center-shelter-outcomes-and/data

### Short description of the dataset:

| Feature name         |  Feature description                                  |  Type   |
|----------------------|-------------------------------------------------------|---------|
| age_upon_outcome     | Age of the animal at the time at which it left the shelter. | String |
| animal_id            | Id of an animal | String |
| animal_type          | Cat in our case. | String |
| breed                | Animal breed. Many animals are generic mixed-breeds, e.g. "Long-haired mix". | String |
| color                | Color of the animal's fur, if it has fur. | String |
| date_of_birth        | date of animal's birth  | DateTime |
| datetime             | Timestamp of outcome | DateTime |
| monthyear            | Accurate time of birth | DateTime |
| name                 | name of an animal | String |
| outcome_subtype      | sub-operation, that will be process with an animal | String |
| outcome_type         | Ultimate outcome for this animal. Possible entries: transferred, euthanized, adopted. | String |
| sex_upon_outcome     | sex and spayed/intact charasteristic of an animal | String |
| count                | number of animals | Numeric |
| sex                  | sex (Male/Female) | String |
| Spay/Neuter          | Boolean charasteristic of Spay/Neuter | String |
| Periods              | number of animal's periods | Numeric |
| Period Range         | Number of days in an animal's period | Numeric |
| outcome_age_(days)   | outcome age, converted in days | Numeric |
| outcome_age_(years)  | outcome age, converted in years | Numeric |
| Cat/Kitten (outcome) | is outcome animal a kitten or a cat | String |
| sex_age_outcome      | grouped sex, age and outcome | String |
| age_group            | age and a group of animal | String |
| dob_year             | year of dob | Numeric |
| dob_month            | month of dob | Numeric |
| dob_monthyear        | year and a month of dob | DateTime |
| outcome_month        | month of outcome | Numeric |
| outcome_year         | year of outcome | Numeric |
| outcome_weekday      | weekday of outcome | String |
| outcome_hour         | hour of outcome  | Numeric |
| breed1               | breed of first outcome (like russian blue) | String |
| breed2               | breed of a second outcome | String |
| cfa_breed            | is CFA | Boolean |
| domestic_breed       | is domestic | Boolean |
| coat_pattern         | pattern of an animal's color | String |
| color1               | first color of an animal | String |
| color2               | second color of an animal | String |
| coat                 | coat of an animal | String |



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
