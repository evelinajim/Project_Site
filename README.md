# Project_Site
What we hope to create on one portion of our proposal is an online tool using Microsoft Flow and Python. The packages I will use for building this api is tweepy. Tweepy is described as an easy-to-use python library for accessing twitter api (https://www.tweepy.org/ ). This tool will pull 100 tweets from a twitter user, place it in a csv file, and then filter and score the tweets from threatening, mild, and violent hate. After doing so, using a sentiment analysis tool, the tool will detect what score the tweet would receive in the case of the criteria made by Eve. After scoring the user, it will then do the same for their followers (limited to the first 10 so that the system does not crash). The tool will then pop up with a name of all the files that scored higher risk and place the information in a csv file.    In order to create my scoring method, I will create three text files. These files will be separated by subject: non-threatening, negative, and violent text words. The csv tweet files will then be read in and filtered through these categories. They will be placed in separate arrays and then be written to a new file with only the names of the twitter user. I will be placing the text files in my github for public use and may develop a stronger tool in place of this method such as a deep learning tool so that the words may continue to become up-to-date and not rely on a static file. I will then finish with two files that have the user information placed and their score. I will work on adding context/geographical component to my sentiment analysis in order to make the data more reliable and further the study of speech detection research.  
