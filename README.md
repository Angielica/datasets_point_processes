# datasets_point_processes

### Social media
-	[Stack OverFlow](https://archive.org/details/stackexchange): Stack OverFlow is a question-answering website in which users can be awarded by answering posted questions on the website. Each event is composed of the type of reward and the time at which the reward was awarded.
-	[Retweet](https://drive.google.com/drive/folders/0BwqmV0EcoUc8MVRvUEgtVmRaZ1U?resourcekey=0-86_dKFm2POj0hCqb8FVnpw): Retweet contains sequences of tweets, where each sequence contains an origin tweet and some follow-up tweets. Each tweet has associated the time and the user; users are grouped into categories based on the number of their followers. 
-	[MemeTrack](https://drive.google.com/drive/folders/0BwqmV0EcoUc8M2wzMnJVenRLdzQ?resourcekey=0-WLXES-gCTmeJxzRweNZzcQ): MemeTrack contains mentions of several memes spanning ten months.
-	[LastFM](http://millionsongdataset.com/lastfm/): LastFM is a music recommendation dataset containing sequences of songs that selected users listen to over time. Artists are used as event types. Specifically, the dataset contains roughly 1,000 users with entire listening history of 19, 150, 868 (user, time, artist, song) tuples from 2004 to 2009.
-	Facebook: Facebook contains a list of all the posts on the Wall of New Orleans Facebook users. It was used for a period of 23 weeks from March 15, 2007, to August 22, 2007.

-	[Reddit] (https://www.kaggle.com/datasets/colemaclean/subreddit-interactions): Reddit is a social network website in which the users submit posts to subreddits (sub-forums). Posts from the most active users on the most active subreddits are recorded. Each sequence corresponds to a list of submissions a user makes. Subreddits are used as event types.

-	MOOC: MOOC contains the interaction of students with an online course system. There are 97 unique types of interactions.
    
-	Wikipedia: The dataset contains most edited pages. A sequence corresponds to edits of a Wikipedia page. 

-	[Yelp] (https://www.yelp.com/dataset): Yelp contains data from the review forum and the reviews for the 300 most visited restaurants in Toronto are considered. Each restaurant has a corresponding sequence of reviews over time.

-	[Duolingo](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/N8XJME): Duolingo contains 13 million Duolingo student learning traces. 
-	[Microsoft Academic Search (MAS)](https://www.microsoft.com/en-us/research/project/open-academic-graph/): MAS provides access to publication venues, time, citations, etc.
-	[Wiki-Talk](http://snap.stanford.edu/data/wiki-talk-temporal.html): The Wikipedia dataset is a time network from Wikipedia in which users edit the discussion page for each other. This dataset has been used for 21 weeks from January 1, 2007, to May 28, 2007, including 104,027 temporary edges during this period.
-	[CollegeMsg](http://snap.stanford.edu/data/CollegeMsg.html): The College Massage dataset includes private messages posted on the OSN at the University of California, Irvine. This dataset includes a period of 27 weeks from April 16, 2004, to October 28, 2004, and a total of 59,564 temporary edges. 
-	Digg: Digg is a news aggregator. The dataset contains votes by its users for 3,553 news articles. The timestamp of votes along with the anonymized user-id form the cascade. It has 82,778 nodes (users) and has an average cascade length of 30.0.
-	Weibo: Weibo is a Chinese micro-blogging platform, where the social network consists of follower links, and cascades reflect re-tweeting behavior.
-	Higgs: Higgs is a public dataset built by monitoring the spreading processes on Twitter before, during and after the announcement of the discovery of a new particle with the features of the elusive Higgs boson on 4th July 2012.
-	[Seismic](http://snap.stanford.edu/seismic/): Seismic data is originally gathered by the authors of \cite{paper14}. It contains a set of Twitter information cascades where each cascade is a set of resharing events and each event is a tuple (u,t) with u being the user out-degree and t being the resharing timestamp.
-	Amazon Beauty and Amazon Clothes: Amazon Beauty and Amazon Clothes contain sequence of product reviews.
-	[tianchi-mobile](https://www.kaggle.com/code/suolyer/tianchi-mobile/data): tianchi-mobile collects users’ behavioral data on Alibaba’s M-Commerce platforms. It records users’ actions on items with timestamps, rounded to the nearest hour.
-	ML-1M: ML-1M collects users’ rating scores for movies.
-	Behance: Behance collects likes and image data from the community art website Behance.
-	Amazon Movies: Amazon Movies refers to the reviews of movies. For each item they consider the time of the written review as the time of event in the sequence and the rating (1 to 5) as the corresponding mark.
-	Amazon Toys: Amazon Toys refers to the reviews of toys. For each item they consider the time of the written review as the time of event in the sequence and the rating (1 to 5) as the corresponding mark.

Regarding the dataset Twitter, even if the dataset name is the same in several papers, the characteristic are different. For this reason, we have decided to rename the datasets.
-	Twitter (a): Data gathered from Twitter which comprises profiles of 52 million users, 1.9 billion directed follow links among these users, and 1.7 billion public tweets posted by the collected users.
-	Twitter (b): The dataset contains 569 URLS shared by 5,942 users. The reshare sequence for a URL creates a cascade where the average cascade length is 5.70.
