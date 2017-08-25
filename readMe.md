## How To Run:
1. Clone and cd into repo
2. Make sure you have the needed csv file
3. pip install virtualenv
4. virtualenv env
5. source env/bin/activate
6. pip install jupyter scipy numpy pandas sklearn ipython implicit statsmodel
7. ipython notebook

## Files:
1. Test.ipynb : tried to get the implicit collab filtering package to work... my initial idea was to use the results of 
collaberative filtering as a key feature in predicting the watch % of a clip for a user... after several hours of trying to get
the recommend function to work, I gave up on it. I was constantly getting IndexErrors when using the recommend function.
Inspiration for this code comes from:
https://medium.com/towards-data-science/recommending-github-repositories-with-google-bigquery-and-the-implicit-library-e6cce666c77

2. challenge.ipynb : another rough ipython notebook that allowed me to get my ideas down and try out various combinations of
features (something that I could have been more systematic about... though when I tried being slightly systematic about it
the R^2 dropped quite a bit). I was also able to try out different models briefly, but those didn't seem to give me much
better results. I learned some really interesting things about the data through this process though, for example mean and median
are really bad features and a straight liner model greatly overfits and has little predictive power.

3. final.ipynb : FINAL SUBMISSION... cleaned up code, and ran the process of calculating performance 10 times to ensure the
result was not dependent on the split of the data, but was representative of the preformance of the model. Most chunks of code
have some sort of comment as to what I am doing there.

4. thoughts : answers to the questions in the prompt

5. country_codes_to_continent : list of the following format country_codes, continent_code


