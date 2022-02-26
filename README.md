# Moodify 	
![image](https://github.com/Atharva-D/Assignment-Submission/blob/main/Moodify_Thumbnail.jpeg)
## Inspiration
In today's world where everyone is striving for achievement, but many people are succumbing to depression as a result of this struggle. Making a few poor decisions occasionally. As a result, **Moodify** was designed to assist people in de-stressing by recommending movies and songs based on their feelings.
## What it does
**Moodify** is a facial expression recognition-based movie and music suggestion website that cheer up users and saves time while searching for a movie or song that matches their mood.
1. It recognizes facial expression based on the 7 categories i.e., angry, sad, fear, happy, disgust, surprise and neutral.
2. Based on the emotion it gives user two choices  either suggesting movies or songs.
3. If user wishes to watch movies/songs then a list of movies/songs matching their mood are suggested with movie/songs poster.
4. When user clicks on movie which he wishes to watch, they will be redirected to IMDB website and for songs it redirects them to Spotify website.
## How we built it
Python is the programming language used to create the emotion recognition model and deploy it on the web application using flask. CV2, TensorFlow, NumPy, matplotlib, and other libraries are also utilized. The model is build using the transfer learning approach for which MobileNet model is used. The FER-2013 dataset, which comprises around 35000 photos, was utilized for model training and validation. This model is deployed on a website created with HTML and CSS using the flask framework. Based on the seven emotions, a new dataset of movies and music was constructed. The data from movies and songs was utilized to create the various templates that correlate to various emotions. 
## Challenges we ran into
It was hard to find Movies and Songs datasets that reflected different emotions on the web. Finding templates of emotion-based movies and songs proved to be a major challenge. It was a challenging task to get the website to access 7 movie templates from the movies button and 7 song templates from the songs button based on the emotion recognized. Dynamic links were used as a means to access the templates for movies/songs corresponding to the output of the model.
## Accomplishments that we're proud of
Creating a project that is effective for the modern generation. Working in unison despite being far away from each other. Creating this awesome project in such a small span of time! Learnt a great deal about Python and different frameworks such as flask and its integration, many new libraries in Python. We thought and build the entire solution in such a small amount of time, overcame all the challenges and find a hack to each problem.
## What we learned
We learnt about the transfer learning approach for the model, which assisted us in face identification, as well as how to develop basic web pages using HTML, CSS and how to deploy the model on the web using flask.
## What's next for **Moodify**
The next step is to improve the model's accuracy. We are also going to introduce an AI-based chat bot with which users may express their problems and, based on the same, the Bot will recommend some remedies as well as the most suitable movie or song in that case.
