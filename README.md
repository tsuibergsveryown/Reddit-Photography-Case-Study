## Executive Summary

### Objective:
By using machines learning models (specifically Natural Language Processing), I’d like to separate the differences between Fashion & Wedding photography in order to continue to grow my Instagram, website, and youtube channel exposure despite the new algorithm change.

### Problem Statement:
As I am getting into both the wedding and fashion photography industry, I need to learn
more about both industries. I need to know what photographers and clients' questions are, what are the most common & relevant issues people have experienced in shooting fashion shoots and wedding shoots, what are the price range and etc... Hence, in this project, I seek to identify the posts between wedding photography & fashion photography on 2 separate reddit forums to learn more about this in depth. I also added a third forum - cinemotagraphy - because a big portion of the money in both of the fashion & wedding industry requires cinematic videography as well.

### Requirements:
- python 3.6.4
- conda 4.4.10
- jupyter 1.0.0
- matplotlib 2.1.2
- numpy 1.14.0
- pandas 0.22.0
- requests 2.18.4
- scikit-learn 0.19.1
- seaborn 0.8.1

### Contents of this README
- Executive Summary
- Objective
- Problem Statement
- Requirements
- The Opener
- The Need
- The Solution
- The Evidence
- The Call-to-Action

In addition, as Instagram announced last week that "we are no longer a photo sharing app." It makes Reddit that much of a great online platform to learn more about both of the photography industry.


### | The Opener |
It's an interesting landscape that photographers are navigating these days when our works are being consumed across so many different places. Some of you might be well aware that Instagram announced earlier this year that "we are no longer a photo sharing app."

As I am getting more into both the wedding and fashion photography industries, the challenge here is how can I tell and separate the two industries now that hashtags #fashionphotography and #weddingphotography on Instagram isn't working out so well? Are the two industry really THAT different? If so, what are the differences? As a professional photographer myself, the learning never stops.


### | The Need |
So what does that mean to the content creators, specifically to photographers as we head into this new algorithm age? Where are my photographers sharing their work, looking for new friends, and asking photography-related questions? Instagram used to be the greatest place for photographers and alike to share their work, get clients, meet co-workers and everything else in between. We now need an online platform so that photographers such as myself can easily asks questions and shares our work at any time from anywhere and however we want. This is the only way to grow our own freelance business online.


### | The Solution |
Lucky for us, there's still the geeky platform - Reddit. Reddit is an awesome place for any category and industry to ask your questions and look for answers. It is still a place for photographers like myself to use anywhere and at anytime. This project will use machine learning models to focus on maximizing the differences between fashion photography and wedding photography so that I can understand both better and then make my own brand value accordingly and appropriately.

With this solution, I aim to grow my instagram, website, and youtube channel exposure by 10% monthly at the end of 6 months.


### | The Evidence |
In this project, I used 4 different machine learning models - CountVectorizer, TfidfVectorizer, KNN, and Random Forest - to classified each subreddit category's submissions. After some fine tuning on its hyperparameters, 3 out of 4 models show both training and testing models well around 98%. Hence, our models are very accurate to tell which submission belongs to which category (r/fashionphotography, r/weddingphotography, or r/cinemotagraphy). This evidently shows that the submissions are very different in nature in order to have the models perform this well, regardless of many similar words that are used throughout all categories (such as shared camera names and vocabularies).


### | The Call-To-Action |
Hence, in order for a photographer to brand him/herself well and differenciate between these 2 photography genre, one needs to study each cateogries and know the differences well especially when he/she is posting submissions in the subreddit group.
