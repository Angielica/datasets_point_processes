# datasets_point_processes

### Social media
-	[Stack OverFlow](https://archive.org/details/stackexchange): Stack OverFlow is a question-answering website in which users can be awarded by answering posted questions on the website. Each event is composed of the type of reward and the time at which the reward was awarded.
-	[Retweet](https://drive.google.com/drive/folders/0BwqmV0EcoUc8MVRvUEgtVmRaZ1U?resourcekey=0-86_dKFm2POj0hCqb8FVnpw): Retweet contains sequences of tweets, where each sequence contains an origin tweet and some follow-up tweets. Each tweet has associated the time and the user; users are grouped into categories based on the number of their followers. 
-	[MemeTrack](https://drive.google.com/drive/folders/0BwqmV0EcoUc8M2wzMnJVenRLdzQ?resourcekey=0-WLXES-gCTmeJxzRweNZzcQ): MemeTrack contains mentions of several memes spanning ten months.
-	[LastFM](http://millionsongdataset.com/lastfm/): LastFM is a music recommendation dataset containing sequences of songs that selected users listen to over time. Artists are used as event types. Specifically, the dataset contains roughly 1,000 users with entire listening history of 19, 150, 868 (user, time, artist, song) tuples from 2004 to 2009.
-	Facebook: Facebook contains a list of all the posts on the Wall of New Orleans Facebook users. It was used for a period of 23 weeks from March 15, 2007, to August 22, 2007.

-	[Reddit](https://www.kaggle.com/datasets/colemaclean/subreddit-interactions): Reddit is a social network website in which the users submit posts to subreddits (sub-forums). Posts from the most active users on the most active subreddits are recorded. Each sequence corresponds to a list of submissions a user makes. Subreddits are used as event types.

-	MOOC: MOOC contains the interaction of students with an online course system. There are 97 unique types of interactions.
    
-	Wikipedia: The dataset contains most edited pages. A sequence corresponds to edits of a Wikipedia page. 

-	[Yelp](https://www.yelp.com/dataset): Yelp contains data from the review forum and the reviews for the 300 most visited restaurants in Toronto are considered. Each restaurant has a corresponding sequence of reviews over time.

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

###Healthcare
-	[Electrical Medical Records (MIMIC II)]( https://drive.google.com/drive/folders/1DJZjYv1eWcmK55xmRk4jVRSB1Alx3vY4): MIMIC II is a collection of de-identified clinical visit records of ICU patients for seven years. Each event records the time when a patient had a visit to the hospital and the disease. The dataset contains 650 sequences, each of which corresponds to a patient’s clinical visits in a seven-year period. Each clinical event records the diagnosis result and the timestamp of that visit.
-	[Medical Information Mart for Intensive Care III (MIMIC-III)]( https://physionet.org/content/mimiciii/1.4/): MIMIC-III contains de-identiﬁed clinical visit records from 2001 to 2012 for more than 40,000 patients.
-	[CLINIC]( https://pubmed.ncbi.nlm.nih.gov/7810938/): CLINIC is a dataset for tracking patient clinical status; it consists of baseline physiologic variables along with the time of death (in case).
-	Health: Health contains ECG records for patients suffering from heart-related problems.
-	FLCHAIN: FLCHAIN is a public dataset introduced in a study to determine whether non-clonal serum immunoglobin free light chains are predictive of survival time.
-	SUPPORT: SUPPORT is a public dataset introduced in a survival time study of seriously-ill hospitalized adults.
-	SEER: SEER is a public dataset provided by the Surveillance, Epidemiology, and End Results Program.
-	EHR: EHR is a large study from Duke University Health System centered around inpatient visits due to comorbidities in patients with Type-2 diabetes.
-	COVID-19 CASES: COVID-19 CASES contains daily COVID-19 cases in New Jersey state. 
-	BOLD5000: BOLD5000 consists of fMRI scans as participants are given visual stimuli

###Finance
-	[Financial Transaction]( https://github.com/dunan/NeuralPointProcess/tree/master/data/real/book_order): Financial Transaction contains transaction records for a stock in one day. Each record stores the time information (in millisecond) and the possible action, i.e., buy or sell. 
-	[BPI Challenge 2012]( https://data.4tu.nl/articles/dataset/BPI_Challenge_2012/12689204) and [2017]( https://data.4tu.nl/articles/dataset/BPI_Challenge_2017/12696884): BPI Challenge contains traces of a loan application process at a Dutch financial institute.
-	BPI Challenge 2013: BPI Challenge 2013 contains traces of event data of an incident and problem management system by Volvo Belgium.
-	[NYSE]( http://www.andresmh.com/nyctaxitrips/): NYSE contains 0.7 million high-frequency trading records from NYSE for a given stock within one day.
-	FICO-UCSD: A credit card dataset from the “UCSD-FICO Data Mining Contest" (FICO-UCSD., 2009) to detect fraud transactions. The dataset is labeled, anonymous and imbalanced.
-	QuantHouse: The financial data has been provided by QuantHouse EUROPE/ASIA, and consists of DAX future contracts between 01/01/2014 and 03/01/2014.

###Daily Life
-	New York City Taxi: New York City Taxi is about the trip records of individual taxis for 12 months in 2013. It contains the temporal information of pick-up (drop-off) passengers associated with every trip as well as the location information.
-	[Breakfast](https://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/): Breakfast dataset is composed of 1712 videos containing 52 subjects performing breakfast preparation activities. The videos are recorded in 18 different kitchens and are composed of 48 fine-grained actions.
-	[50Salads](https://cvip.computing.dundee.ac.uk/datasets/foodpreparation/50salads/): It contains 50 RGB video and 3-axis accelerometer data belonging to salad preparation activities performed by 25 actors where each actor prepares two salads. There is an annotation file in which the activity is annotated with two levels of granularity (i.e., high and low). Specifically, the dataset is composed of 17 fine-grained action classes. 
-	[MultiTHUMOS](https://ai.stanford.edu/~syyeung/everymoment.html): MultiTHUMOS is a sports activity dataset that is designed for action recognition in videos. The authors derive the CTAS using 400 videos of individuals involved in different sports such as discus throw, baseball, etc. The actions and goals can be classified into 65 and 9 classes respectively and on average, there are 10.5 action class labels per video.
-	[Helpdesk](https://data.mendeley.com/datasets/39bp3vv62t/1): Helpdesk contains traces from a ticketing management of the help desk of an Italian software company.
-	[LinkedIn](https://github.com/HongtengXu/Hawkes-Process-Toolkit/blob/master/Data/LinkedinData.mat}): LinkedIn contains the job hopping records of several LinkedIn users in several Information Technologies companies, research institutes and universities.
-	[IPTV](https://github.com/HongtengXu/Hawkes-Process-Toolkit/blob/master/Data/IPTVData.mat): IPTV contains log-data records TV watching user behaviors.
-	Smart Home: Smart Home contain a sequence from a smart house with 14 classes and over 1000 events. Events correspond to the usage of different appliances. The next event will depend on the time of the day, history of usage and other appliances.
-	[Stock](https://www.kaggle.com/datasets/szrlee/stock-time-series-20050101-to-20171231): Stock contains daily stock prices of 31 companies. We extract three types of event: ‘up’, ‘down’, ’unchanged’ from each stock. We further partition sequences by every season and obtain 1,488 sequences with average length of 49.
-	[eCommerce](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop):  eCommerce contains users’ behavior in a cosmetics online store. Each user’s behaviors are categorized into four types: ‘view’, ‘cart’, ‘remove-from-cart’, and ‘purchase’. This dataset contains 6,200 sequences with an average length of 64.
-	Citi Bike: Citi Bike shares bikes at stations across New York and New Jersey. The activities for a certain bike form a sequence of events. The training set and test set contain the records of the bikes in Jersey City from January to August 2017 and that of September 2017, respectively.
    
###Disaster Management

-	Earthquake: Earthquake contains the time and location of earthquakes in China.
-	Northern California seismic data: The Northern California Earthquake Data Center (NCEDC) provides public time series data that comes from broadband, short period, strong motion seismic sensors, and GPS, and other geophysical sensors.
-	EARTHQUAKES: EARTHQUAKES contains location and time of all earthquakes in Japan from 1990 to 2020 with magnitude of at least 2.5 from the U.S. Geological Survey. Number of events per sequences ranges between 18 to 543.
    
###Public Security
-	[911-Calls](https://www.kaggle.com/datasets/mchirico/montcoalert): 911-Calls contains emergency phone call records. The dataset has information about calling time, location of the caller and nature of the emergency.
-	Chicago Crime Data: Chicago crime data set is a collection of reported incidents of crime that occurred in Chicago; it contains $\sim$ 13 thousand records, each of which shows time, and latitude and longitude of where the crime happened
-	Atlanta 911 calls-for-services data: The 911 calls-for-service data in Atlanta from the end of 2015 to 2017 is provided by the Atlanta Police Department.

###Others

-	NYC Collision Data: New York City vehicle collision (NYC Collision) data set contains $\sim$ 32 thousand motor vehicle collisions. Every collision is recorded in the form of time and location (latitude and longitude coordinates)
-	Global Database of Events, Language, and Tone (GDELT): GDELT is collected from April 1, 2015 to Mar 31 2016 (temporal granularity of 15 mins). It contains records of events that include two actors, action type and timestamp of event.
-	Integrated Crisis Early Warning System (ICEWS:  ICEWS is collected from Jan 1, 2014 to Dec 31, 2014 (temporal granularity of 24 hrs). It contains records of events that include two actors, action type and timestamp of event.
-	[VLEP](https://github.com/jayleicn/VideoLanguageFuturePred/tree/main/data): VLEP contains 28,726 examples from 10,234 short video clips. 
-	[Neuron]( https://kordinglab.com/spykes/index.html): Neuron contains spike record of 219 M1 neurons. Every time a neuron spikes is recorded as an event, these events form a uni-dimensional event sequence. This dataset contains 3,718 sequences with average length of 265.
-	Activity-Net: Activity-Net comprises of activity categories collected from 591 YouTube videos with a total of 49 action labels and 14 goals.
-	ETH:  ETH contains two scenes each with 750 different pedestrians and is split into two sets (ETH and Hotel). 
-	UCY:  UCY contains two scenes with 786 people. This dataset has 3-components: ZARA-01, ZARA- 02 and UCY
-	Foursquare: An evaluation dataset from Foursquare, a location search and discovery app). Each user has a sequence with the mark corresponding to the type of the check-in location (e.g. "Jazz Club") and the time as the timestamp of the check-in.
-	Celebrity: In Celebrity, the authors consider the series of frames extracted from youtube videos of multiple celebrities as event sequences where event-time denotes the video-time and the type is decided upon the coordinates of the frame where the celebrity is located. 
-	SMRT: SMRT is a set of ATS log data collected from the SMRT corporation, which operates several Mass Rapid Transit systems in Singapore
-	BDD100k: BDD100k is a video sequences, accompanied by basic sensory data such as GPS, velocity, or acceleration.
-	NCAA basketball: NCAA basketball contains 296 basketball game recordings, each typically 1.5 hours long.
-	GigaWord: GigaWord corpus archive of newswire text data in English that has been acquired over several years by the Linguistic Data Consortium

