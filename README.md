# Task-3-Classification
# Preprocessing 
#### Remove unnecessary columns liks('Unnamed: 0',"id",'date','author')
#### Remove Punctuation
#### Remove Punctuation
#### Remove stopwords
#### Remove numbers
#### Apply Stemmer
#### Apply TfidfVectorizer to get features
#### Apply the LabelEncoder on the "topic" column with 11 categories

# Models
#### Split data into 80% train and 20% test
## Random Forest Classfier
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/c27a193a-5fef-44f8-b198-9243cb02aca2)
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/162815e3-ab3f-4edc-b425-5f253f9360e0)
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/db4eb830-55a4-45a1-8601-de8928490353)

#### Model is not good because it makes the data overfit.

## Naive_Bayes
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/e4cfe68b-15bb-4823-85c1-360bdee1d76b)
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/59d301c6-df72-40dc-82ad-d6ff1a79d2a8)
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/93e8b49e-ded4-41b5-a71b-ccb8e0245a07)
#### Model is good.

## LinearSVC
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/f9388746-1873-49dd-b867-1111a1701670)
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/be3abbae-ac8b-4b23-8a53-0fd55335b0a0)
![image](https://github.com/mohamedali-sc/Task-3-Classification/assets/96593530/15dc6e66-fd16-445d-94bf-590c57672227)
## Model is not good because it makes the data overfit.


# Enhancements
##### We can use cross-validation to avoid overfitting
##### We can use grid search to choose the best hyperparameters.
