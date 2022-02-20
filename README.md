# Moodify 	![alt text]("https://github.com/Atharva-D/Assignment-Submission/blob/main/Moodify_Thumbnail.jpeg")
## Inspiration
Today, we are going towards a world where everyone is striving for achievement, but many people are succumbing to depression as a result of this struggle. Making a few poor decisions occasionally. As a result, **Moodify** was designed to assist people in de-stressing by recommending movies and songs based on their feelings.
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
Being a student we come across various hurdles in life, which at time lead towards demotivation, and we are proud to tell that we shared this application of ours within our college and got very great feedbacks from them. 
## What we learned
We learned about Machine learning in this model, which helped us for detection of face and we also learned how to create a basic web page and how to deploy the backend code on the web with help of flask. 
## What's next for Moodify
Next we are planning to upgrade this model of ours and increase the accuracy of the same. We are even planninf to add a AI based chat bot with whom, one can share his/her problem and depending on the same, the Bot will suggest them out some solutions and also might suggest them the best suited movie in that situation. 
