## Inspiration
My inspiration is my love for data science and participating in different competitions, since the start of this year I have participated in more than 32 competitions and I always try to achieve high ranking in both Kaggle and Driven Data competitions. I am still new to the world of data science as I still remember that I didn't even know the syntax of python 5 months ago. The journey has taken me through all kinds of languages and machine learning techniques and now here I am submitting my first Devpost project. 
## What it does
It a Web app that uses Expert Ai NLP Edge sentimental and Text analysis to display visualization. The interactive app lets you write your own tweet and give you text analysis. I have also used the API feature to train the entire data set and then use the side widget of streamlit to visualize the data.
## How we built it
- I have used y knowledge of Data Visualization and Machine learning to build this web app.
- Streamlit library is used, which is quite simple and fast to display data.
- ExpertAi APi was used, especially Edge NLP was used to get sentiments, keywords, and entity detection.
- The dataset was scraped from Twitter in February 2015 and contributors were first asked to classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service"). More details about the dataset can be found  [Kaggle Crowdflow](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)
- This project was inspired by Coursera's: [Create Interactive Dashboards with Streamlit and Python](https://www.coursera.org/projects/interactive-dashboards-streamlit-python) guided project.

## Challenges we ran into
- The ExpertAi is fast for on-demand solutions but it is quite slow to train a huge dataset. I have to reduce data to minimize the time to get sentiment values. 
- The API cloud has limited points but after contacting the Dev team I came to realize that if I use Edge I can experiment as much I can.
- I have published multiple notebooks on Kaggle experimenting and playing around but it was not easy at the start to understand what the key features are, but soon I got hang of it. 
## Accomplishments that we're proud of
- I have learned to play around with NLP API for the first time, I have used the Hugging face library but never have a chance to get first-hand experiments to implement API into my project.
- This is my first web APP and as I told you earlier, I am new to this world, so every small achievement means a lot to me. 
- Learning to write Markdown to display my work effectively. 
- Participating in Devpost is an Achievement in itself as I can brag about it too. 
## What we learned
- Never think that building app is difficult
- Always ask for help
- Play around with new technology until you decide what you can do with it.
- Streamit is easy but you need to learn the basics.
- using ```.progress_apply() ```
## What's next for Airline Tweets NLP
I will be enhancing my App by adding more NLP features provided by Expert Ai:
- [Relation extraction](https://docs.expert.ai/edgenlapi/latest/guide/relation-extraction/)
- [Deep linguistic analysis](https://docs.expert.ai/edgenlapi/latest/guide/linguistic-analysis/)
- [Document classification](https://docs.expert.ai/edgenlapi/latest/guide/classification/)
- [Information extraction](https://docs.expert.ai/edgenlapi/latest/guide/extraction/)