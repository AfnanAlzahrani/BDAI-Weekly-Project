# BDAI-Weekly-Project-Pyspark


<img src="https://drive.google.com/uc?export=view&id=13Mel-yO67So16PUPu3yFasJmweaOjq7P"/>

## :round_pushpin: Table of contents
> * [Data Review](#data-review)
> * [Columns](#columns)
> * [Preprocessing](#preprocessing)
> * [EDA](#eda)
> * [Building a Model ](#building-a-model)
> * [Model Evaluation](#model-evaluation)
> * [Resources](#resources)
> * [Team Memebers](#octocatteam-memebers)

## Data Review
TripAdvisor European restaurants dataset from Kaggle, It consists of  1083397 rows and 42 Columns

### Columns:
> * restaurant_name : name of the restaurant on TripAdvisor 
> * country : country name retrieved from original_location
> * city : city name retrieved from original_location
> * latitude : latitude coordinate
> * longitude : longitude coordinate
> * claimed : restaurant business claimed on TripAdvisor
> * price_level : level of prices in current currency 
> * meals : types of meal
> * cuisines : types of cuisine
> * vegetarian_friendly : is the restaurant vegetarian friendly?
> * vegan_options : does the restaurant offer vegan options?
> * gluten_free : does the restaurant gluten-free options?
> * open_days_per_week : number of open days per week retrieved from original_open_hours
> * open_hours_per_week : original open hours on TripAdvisor
> * working_shifts_per_week : number of working shifts per week retrieved from original_open_hours
> * avg_rating : average restaurant rating
> * total_reviews_count : total reviews count
> * default_language : default language displayed while scraping
> * reviews_count_in_default_language : total reviews count in default language
> * food : food rating
> * service : service rating
> * value : value rating

## Preprocessing
> * Drop unnecessary columns 
> * Handling  missing values
> * Converting the price values '€', '€€-€€€', and '€€€€' into three categories (low, medium, high)
## EDA
<img src="https://drive.google.com/uc?export=view&id=15pjmJ7CgEdmza2wwwukV1P1Pi72c-eEq"/>

<img src="https://drive.google.com/uc?export=view&id=1IW2R1--_yYVGVoWkHfcLkkkgB-6UBcvP"/>

<img src="https://drive.google.com/uc?export=view&id=1QQTA1pji8twzj-LMitY953kj7C5f7quw"/>

<img src="https://drive.google.com/uc?export=view&id=1pngt_BAD0q4eb8Li9G9n_tnip1-qoLok"/>

<img src="https://drive.google.com/uc?export=view&id=1L-xvmNjdEuVm0w_3xuEHFXM-vxShrqrP"/>


## Building a Model 

We used three models: decision tree, random forest and logistic regrassion.
we used the following measures: accuracy, F1 Score, weighted recall and weighted precision.

## Model Evaluation

Based on the measures we observed that all three classifiers had a similar accuracy but the Decision tree is the best model.

## Resources

The data : https://www.kaggle.com/code/stefanoleone992/tripadvisor-european-restaurants-eda/data

## :octocat:	Team Memebers

- [Abdullah Huwaishel](https://github.com/hush966)
- [Afnan Alzahrani](https://github.com/AfnanAlzahrani)
- [Jumana Almussa](https://github.com/jumana0)
- [Mahmuod Alhassan](https://github.com/alhassanm)
- [Amjad Almusallam](https://github.com/ASM650)



# SDA - Machine learning - CodingDojo - pyspark 

