# Recommendation System
![Cream and Yellow Illustrated Scooter Sale Twitter Post](https://github.com/quant-dot-ai/scooter-recommendation-system/assets/146693417/d42abe45-fd1b-4eee-a69d-ccf53cac55a2)

### Introduction
Electric scooters are a great way to get around. They are prevent you from being late to class, save the environment and quite fun. But one quick search online will flood you with options. This makes it  really difficult to choose the right one for your specific needs. Battery capacity, motor rpm and weight listed on shopping websites do not mean a lot to the average consumer (unless you are an electric scooter aficionado). We aim to simplify this choice by going through many (and I mean MANY) user and critic reviews, figure out the common features and the sentiment around scooters to recommend the perfect one for you!

### Data Used
Our custom built [Feature dataset](https://github.com/quant-dot-ai/scooter-recommendation-system/blob/main/Electric_Scooter_Features.csv) and [Reviews Dataset](https://github.com/quant-dot-ai/scooter-recommendation-system/blob/main/Electric_Scooter_Reviews.csv)  were created by scraping thousands of reviews from Amazon and youtube video comments.

### Tools and Tech
We used python, more specifically we used selenium for scraping, nltk, pandas, numpy and sklearn packages for processing. Google's and openAI's APIs for connecting to services like Youtube and ChatGPT. 

### Analysis
A detailed presentation with our motivation, methodology and findings can be found [here](https://github.com/quant-dot-ai/scooter-recommendation-system/blob/main/Electric%20Scooter%20Recommender%20System.pptx). (It lacks the charisma of our presenters but has most of the information)

### Insights and Recommendations
| Brand      | Model | Pros                        | Cons                              | Recommendation                 |
|------------|-------|-----------------------------|-----------------------------------|--------------------------------|
| Wheelspeed | Primer| User-friendly               | Weak brakes                       | Great if there have been many  |
|            |       | Reliable speed              | Password needed                   | complaints about missing bikes |
|            |       | Cruise control              |                                   | in your neighbourhood          |
|------------|-------|-----------------------------|-----------------------------------|--------------------------------|
| Gotrax     | GXL V2| Lightweight                 | Battery Issues                    | Good if have to carry it long  |
|            |       | Efficient brakes            | Maintenance                       | distances (from car to class)  |
|            |       | Great speed                 | Headlight                         |                                |
|------------|-------|-----------------------------|-----------------------------------|--------------------------------|
| VOLPAM     | SPT7  | Dual shocks                 | Height adjustment &               | Great for speed, choose this   |
|            |       | Simple assembly             | Adjustment screw required         | if you are frequently late for |
|            |       | Stable                      |                                   | class                          |
|------------|-------|-----------------------------|-----------------------------------|--------------------------------|


### Business Usecase and further development
This model can easily be extended to other types of recommendation systems that would benefit from sentiment analysis. Examples include but are not limited to:

1. **Educational Content and Online Courses:** Sentiment analysis can be utilized by online learning platforms to recommend courses and educational content that have received positive feedback from learners with similar backgrounds or interests.

2. **Healthcare and Wellness Apps:** These apps can use sentiment analysis to recommend health and wellness products, exercises, or routines that have positively impacted users with similar health profiles or goals.

3. **E-commerce and Retail:** In online shopping platforms, sentiment analysis can be used to parse customer reviews and ratings. This information can help in recommending products that have received positive feedback, thus improving customer satisfaction and potentially increasing sales.

4. **Movie and Music Streaming Services:** Services like Netflix or Spotify can use sentiment analysis to understand user reviews and social media comments about movies, TV shows, or songs. This can help in recommending content that is not only popular but also positively received by audiences with similar tastes.

5. **Restaurants and Food Delivery Services:** Platforms like Yelp or Uber Eats can implement sentiment analysis to analyze customer reviews about restaurants or specific dishes. This can aid in recommending eateries or meals that have garnered positive sentiments from customers with similar preferences.
