# Moodify
## Inspiration
Today, we are going towards a world where everyone is striving for achievement, but many people are succumbing to depression as a result of this struggle. Making a few poor decisions occasionally. As a result, **Moodify** was designed to assist people in de-stressing by recommending movies and songs based on their feelings.
## What it does
**Moodify** is a facial expression recognition-based movie and music suggestion website that cheer up users and saves time while searching for a movie or song that matches their mood.
1. It recognizes facial expression based on the 7 categories i.e., angry, sad, fear, happy, disgust, surprise and neutral.
2. Based on the emotion it gives user two choices  either suggesting movies or songs.
3. If user wishes to watch movies/songs then a list of movies/songs matching their mood are suggested with movie/songs poster.
4. When user clicks on movie which he wishes to watch, they will be redirected to IMDB website and for songs it redirects them to Spotify website.
## How we built it
Python is the primary programming language, and many of its libraries are utilised, including CV2, Keras, numpy, pandas, and others. The model uses a deep learning algorithm to recognise the user's facial expressions; the model is first trained and evaluated on a dataset of over 34,000 photos. The model first detects the user's expression and then suggests movies and music to cheer them up. Flask, HTML, and CSS are used to deploy the project to the web. With a user-friendly layout, our Web page strives to provide the user with a positive atmosphere.
## Challenges we ran into
The major challenge we faced were lack of dataset available across the web, which indeed affected the accuracy of the model, to overcome that we ourselves clicked few pics and added the same to the dataset. 
## Accomplishments that we're proud of
Being a student we come across various hurdles in life, which at time lead towards demotivation, and we are proud to tell that we shared this application of ours within our college and got very great feedbacks from them. 
## What we learned
We learned about Machine learning in this model, which helped us for detection of face and we also learned how to create a basic web page and how to deploy the backend code on the web with help of flask. 
## What's next for Moodify
Next we are planning to upgrade this model of ours and increase the accuracy of the same. We are even planninf to add a AI based chat bot with whom, one can share his/her problem and depending on the same, the Bot will suggest them out some solutions and also might suggest them the best suited movie in that situation. 
