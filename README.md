PROJECT 3: REDDIT POSTS 

Executive Summary:

https://www.reddit.com/ is one of the most popular websites in the world.  

The site is divided into 'sub reddits' that focus on specific subjects of interest.  Users post to the sub-reddits with links, comments or information that would be of interest to the sub-reddit.

The intention of this project is to build a model that has a high accuracy in predicting whether a reddit post title belongs to one of two sub-reddits.  

The two subreddits that were chosen were ‘The_Donald’ and “Showerthoughts’:  

“The_Donald’ is a subreddit for the discussion of all things Donald Trump.  It is generally a pro-Trump community. The introduction that is posted on the sub-reddit wiki states the theme of the sub-reddit is "where we try to outline why one would want to vote for Trump"  

Showerthoughts is a reddit where people post semi-philisophical or rhetorical questions about life or technology or pretty much any subject.  The site intro states: "A subreddit for sharing those miniature epiphanies you have that highlight the oddities within the familiar." Generally it is for entertainment and humor. 


An example of a 'shower thought' is: "When jogging, we put on special clothes so that people don't think we are running to or from something"

The data was downloaded from the pushshift api which has consolidated all reddit posts.  Approximately 10,000 unique posts were downloaded from each group.  Basic cleaning was done such as removing numbers and other characters that are not words.  

A random forrest model, a logistic regression model and a multinomial Naive Bayes classifier were tested on the cleaned, parsed text data. The logistic regression model performed the best with approximately 85% accuracy.  



Notebook index:
=======
* 0_Reddit_project_3_testing.ipynb :  Initial start to project using Reddit API and testing methods of data gathering.
* 1_BC_scraper.ipynb: Brian Collins code to access pushshift api to gather data.
* 2_Project_3_start.ipynb : Beggining data exploration and cleaning of data.
* 3_Project_3_model.ipynb : Modeling process and minor cleaning/adjustment of data.
* 4_Project_3_model-NO_SHOWER.ipynb.ipynb : Modeling process and testing out if removing certain key words affects accuracy.


