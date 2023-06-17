# Personality-Prediction-of-Instagram-Users-Using-Machine-Learning
Using the extracted real-time data from Instagram user accounts, predict the personalities of social media users by using their Instagram captions and categorizing their personalities based on the MBTI test through the application of machine learning algorithm, logistic regression.
## Overview
The main aim is to develop a machine learning  that fetches data from a set of Instagram accounts and predicts the personality using captions. Captions are the explanation about an Instagram picture that users post to provide more context including some emoji, hashtags, and tags.

## Motivation
Social media utilization has been increasing rapidly. Usage of social media sites, such as Instagram, Twitter, and Facebook, for social interaction has also become a popular trend. Personality prediction model predicts the personality of the users using real-time data from social media accounts. 


## Project Structure

![Workflow](https://imgtr.ee/images/2023/06/17/YpLo4.png)

## Myers Briggs Type Indicator (MBTI)

![Workflow](https://imgtr.ee/images/2023/06/17/Ypx4X.jpg)

## Data Collection (Test data)
Initially, a web scraping tool known as Phantom buster is used. This scraping tool comes with different customized operations to scrape data from the internet. With the help of this tool, a huge number of data can be extracted in less time, and it is more efficient. The extracted data can be stored in the form of CSV or JSON file. To determine personality, the data containing captions under each Instagram post was collected. For each Instagram account, minimum of 3 posts from the particular user is considered. The URLs of these posts are taken in an Excel document. Finally, after launching the saved file the data scraped is available in the form of CSV and is ready to download. 

## Data (Training set)
For the training dataset, a publically accessible standard dataset was acquired from Kaggle. The dataset was then lemmatized, stopwords were removed, and vectorization was performed. In our study, we used a supervised model called Logistic Regression. After that, we used the training dataset to train the model


## Notebooks
- `PRES_PRED.ipynb`: The dataset is pre-processed, and machine learning algorithms such as logistic regression is primarily used to categorize people based on the Myers-Briggs Type Indicator Test (MBTI). 


## Algorithm Used
- Logistic Regression

## Performance Metrics Used
- Confusion Matrix
- Accuracy
- Percision
- Recall
- F1-score
- Macro and Weighted Average
- Make scorer

## Packages Used
- Pandas 
- Numpy
- Matplotlib 
- Seaborn
- Sklearn 
- Plotly 
- nltk
- Ipython

## Results
Before fitting the classifiers to the MBTI training dataset, it was preprocessed in three steps. The datasets are imported using the pandas module from csv format. Text processing necessitates preprocessing because it converts input into a standard format before converting it into features. It's the equivalent of converting human-readable text to machine-readable text.
To fit the model, the training dataset is used. The model is given the second batch of data to generate values and compares them to the predicted values. A test dataset is used to evaluate the fit machine learning model. The purpose is to estimate the performance of the machine learning model on new data.

## Conclusion
Most of the people prefer to show their positive side in social media platforms. They post happy pictures and write motivational and positive captions. Since people’s life are judged based on their projection in social media, everyone portrays themselves as cheerful and happy even though they are going through bad situations in life. Results show that introverts mostly prefer social media for communication. They are more comfortable using social media for interaction than having direct contact with people. Social media help introverts to share their thoughts and feelings by limiting their interaction. Many Instagram users are intuitive as they have futuristic thinking and creativity, so they find possibility in every opportunity. In the 150 profiles we collected from Instagram, out of the 16 categories of MBTI traits most people fall under these four categories - INFJ, INFP, INTJ, and INTP. 
This study provides a fairly precise assessment of a person's personality traits at the moment, and it may be applied to a wide range of scenarios like assistive technology, recommender systems, and adapted environments etc. Knowing the user's personality might help to determine things like his probable interests or needs in various situations. The data collected for prediction is not grouped based on gender, age, country or of any kind. For the future development of this experiment, we can rely on collecting more data, thereby considering more attributes for accurate results.


## Documentation

[Documentation](https://drive.google.com/file/d/1cZ8r2xeWFTvQUXkYOJaWXoSSHDulmr3s/view?usp=sharing)


