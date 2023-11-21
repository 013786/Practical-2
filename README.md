# Summary of findings:
This practical was a journey, as I expect most of this work will be in real life situations.  My initial review of the data set didn't uncover things like prices entered as 123456789 or
other default/dummy values.  I was working through the lesson and finally identified that and circled back.  Additionally, using the entire data set added significant time to the process.  
I finally decided to select a subset for development to speed iteration.  This also showed itself when I went to upload the project to github and the files size was too large.  I had to 
learn how to compress files on mac OS without including hidden files and then modify the .ipynb to account for the compression.

As I began to look at the problem, I asked what features were related to price.  While that is interesting, I think that a more thoughtful question would be: 'How should I price my
inventory?" or "Which car would bring the highest sales price?"  Similar questions, but the first helps with a car that is presented to you (no control, just figure out a good price) while 
the second is more along the lines of what should a dealer target.

I ended up building a linear regression model to answer the first question and used sequentialfeatureselector to identify the key features for the second question.

Next steps would be to run this concept past a group of dealers and see if this answers the kinds of questions they are asking.  I think this provides useful insight, but direct feedback
from the experts would help.
