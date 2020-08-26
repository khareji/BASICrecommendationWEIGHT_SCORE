# recommendation
Basic recommendation syste, based on weight score(content based)
Recommendation based on weighted_average
Recommendation based on scaled weighted average and popularity score(Priority-50% for both)
https://medium.com/@developeraritro/building-a-recommendation-system-using-weighted-hybrid-technique-75598b6be8ed https://codeburst.io/explanation-of-recommender-systems-in-information-retrieval-13077e1d916c
# information
whenever we use netflix, youtube, flipkart for our need, there we see recommendation for different different things like recommendation for movie , videos , or a porduct etc .
all these things which appears as recommendation is created by system by seeing the user bheaviour or creating a score board of different features . by which we get new-new recommnedation.
basically there are 2 ypes of recommendation system Collaborative and content based filtering , in collaborative filtering method that are based solely on the past interactions recorded between users and items in order to produce new recommendations. These interactions are stored in the so-called “user-item interactions matrix” ,The class of collaborative filtering algorithms is divided into two sub-categories that are generally called memory based and model based approaches.
content based filtering method  that only rely on the user-item interactions, content based approaches use additional information about users and/or items. If we consider the example of a movies recommender system, this additional information can be, for example, the age, the sex, the job or any other personal information for users as well as the category, the main actors, the duration or other characteristics for the movies (items).

# procedure of our model
here i have created a calloboartive filter based recommendation system on movie data which is downloaded from 
kaggle , which have different diffrenet features so i have created a , weight socre column by using the rating , vote count, popularity 
# formula 
formula for weight =((r*v)+(meanofr*qunatilev))/(v+qunatilev)
further using the 50% popularity and 50% weight score , which will determine the next recommendation porduct to the user
# conclusion
detailed conclusion has been provided in the BASICrecommendationWEIGHT_SCORE.pynb
