# TAR-UC-E-Data-Hackathon-2020
## Team C11 - Team FALCON
We are students of Tunku Abdul Rahman University College (TARUC), one of the Premier Digital Technology Instituions (PDTIs) in Malaysia. We are currently pursuing second year in Bachelor of Computer Science (Honours) in Data Science.

We are very delighted to participate this E-Data Hackathon Competition 2020 which was held from 23 to 25 October 2020. According to the organiser, 36 teams of students that have been shortlisted. All teams have been divided into 3 parallel sessions and teams in different session have been assigned to a topic. The topic that our team have been assigned to is sentiment analysis/Natural Language Processing on digital marketing. After much discussion, we have decided to work on the analysis of the comments by the female customers on  Women Clothing E-Commerce and classify them into positive or negative comments. The dataset is taken from the Kaggle Website

We have applied all the necessary data science skills that we have learnt in the subjects BACS3013 Data Science and BACS3074 Artificial Intelligence in the University College  to make this project a success.

There are 6 sections in total:

Business Understanding
Data Understanding
Data Pre-processing
Data Modelling
Data Evaluation
References

# Business Understanding
In this section, we have described the backgound of the E-Commerce together with same examples.

# Data Understanding
In this section, we have described the number of rows and columns in the identified dataset. Besides, we have also identified the 2 main variables/features that would be used for sentiment analysis.

# Data-processing
In this section, we have performed some data pre-processing job before performing data modelling. Our main focus is on the review text/comments and hence we have removed all other unwanted columns/features. Firstly, we check for missing values, in which the column is left blank. All we did is to remove the entire row that has the missing values. Then, we remove the puncutaion in each sentence, and turn all the characters into lower-case characters. Next, tokenisation process is conducted to split the sentence into a few words. After that, we remove stopwords such as "a," "and," "but," "how," "or," and "what", perform lemmetisation and remove non-English words.

# Sentiment Analysis
In this section, we can visualise the postive and negative words using the word cloud. After that, we perform feature generation using bag od words. Lastly, we split the dataset into the training and testing data as well as handling the imbalance data.

# Data Modelling
In this section, we have performed the data modelling by usigng four different algorothms such as  Random Forest (RT), Decision Tree (DT), Support Vector Machine (SVM), and Naive Bayes (NB). The accuracy, precision, recall, and Area Under Curve (AUC) are also computed.

# Data Evaluation
In this section, we have described the accuracy, precision, recall, and AUC for each of the algorithms used in data modelling.

# References
1. Kaggle - https://www.kaggle.com/
2. CRISP-DM - https://www.sv-europe.com/crisp-dm-methodology/
