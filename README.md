# stat199-FinalProject

Data
How does Donald Trump's sentiment in his tweets vary across his "in-groups" and 
"out-groups?"

The data set was extracted from a website-TrumpTwitterArchive.com. The original 
curator of the data created their own Twitter scraper in order to obtain the 
data. They utilized Python, Selenium (which is a software suite that allows the 
automation of tests utilizing web browsers), and Tweepy (a Python library for 
accessing the Twitter API). 

After adding other variables, the variables in this dataset are as follows:


- source: Original source where tweet was posted 

- text: text of the tweet 

- created_at: Date and time the tweet was posted/created, provides context

- retweet_count: number of retweets 

- favorite_count: number of favorites 

- is_retweeted: whether or not the tweet was originally posted on a different 
account and Trump retweeted 

- id_str: The scrape.py script collects tweet ids. If you know a tweet's ID 
number, you can get all the information available about that tweet using Tweepy 

- obama: 1 or 0 for whether the tweet talks about Barack Obama.

- biden: 1 or 0 for whether the tweet talks about Joe Biden.

- pelosi: 1 or 0 for whether the tweet talks about Nancy Pelosi.

- kamala: 1 or 0 for whether the tweet talks about Kamala Harris.

- hillary: 1 or 0 for whether the tweet talks about Hillary Clinton.

- aoc: 1 or 0 for whether the tweet talks about Alexandria Ocasio-Cortez.

- pence: 1 or 0 for whether the tweet talks about Mike Pence.

- mcconnell: 1 or 0 for whether the tweet talks about Mitch McConnell.

- fauci: 1 or 0 for whether the tweet talks about Dr.  Anthony Fauci.

- amy: 1 or 0 for whether the tweet talks about Amy Coney Barrett.

- nikki: 1 or 0 for whether the tweet talks about Nikki Haley.

- covid: 1 or 0 for whether the tweet talks about COVID-19.

- climateChange: 1 or 0 for whether the tweet talks about climate change.

- abortion: 1 or 0 for whether the tweet talks about abortion.

- blm: 1 or 0 for whether the tweet talks about the Black Lives Matter movement.

- guns: 1 or 0 for whether the tweet talks about guns.

- news: 1 or 0 for whether the tweet talks about news media.

- usa: 1 or 0 for whether the tweet talks about the United States.

- russia: 1 or 0 for whether the tweet talks about Russia.

- immigration: 1 or 0 for whether the tweet talks about immigration.

- person: categorical variable for the name of the person that the tweet is 
about (from among the 11 looked at in this analysis).

- party: political party of the person who is talked about in the tweet 
(either democrat or republican).

- gender: gender of the person who is talked about in the tweet (either male or 
female).

- ave_sentiment: numeric sentiment score of the tweet.

- posNeg: categorical sentiment of the tweet (either positive, neutral or 
negative).

- date: date that the tweet was posted (mm/dd/yy).

- time: time that the tweet was posted (24-hour format).