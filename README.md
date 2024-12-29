# AI_Blog
AI Blog tutorial by CodeWithTomi 


Following the backend projects tutorial provided by CodeWithTomi, I am building an app that allows the user to input a youtube video url. The app then gets the youtube title, transcript, and allows OpenAI to generate a blog about the video which is saved to the database and then returned as a response to the user. 

Learning Opportunities:
This app is created using Python and Django. This is my first introduction to both Python and Django since I have been taught in Javascript and React. Python seems to me as a much more intuitive language than Javascript and therefore has been a fun experience to use it and understand it. 

The tutorial began creating a cloudbased database using Qovery. I was not able to get access to that program so I switched over to Railway and created a PostgreSQL database from there. That was a rewarding new experience as for a moment I dabbled with AWS but ultimately decided against it as I need more learning and experience in regards to AWS to use successfully.

This also was my first time implementing an Admin login functiionality.

Another hiccup I encountered was during the use of pytube. Pytube was implemented in the tutorial to extract the audio from the video and turn it into a transcript to feed into OpenAI. I could not use Pytube as the program was going through some known bugs that were impeding users from implementing it. I switched over to yt_dlp which was a bit tricky converting the function in Python. I did end up getting better quality downloading and audio, which was a nice win for me.

