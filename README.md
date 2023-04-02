## Inspiration 🚀
* Identify common language patterns to distinguish between fake and real news articles. 🤔
* Examine the sources cited in articles to differentiate between fake and real news. 🕵️
* Compare the headline to the body content to identify sensationalist headlines. ⚖️
* Analyze social media engagement to gain insight into the audience and potential impact. ⛓️
* Use machine learning algorithms to automate the process of identifying fake news in the future. 🧑‍💻

## What we did 💻
The data analysis of fake and real news involves the use of various methods and techniques to examine and compare large datasets of news articles to identify patterns and characteristics that distinguish between them.
* Our project involves analyzing a dataset of fake and real news articles.
* We have used the following components:

    * Data Collection from Kaggle 🗑️
    * Data Cleaning & Processing using following Parameters 🧹

        * Duplicate & NaN Removal
        * Stopword Removal
        * Special Character Removal
        * Regex-based Cleaning
    * Feature Extraction using the following Parameters 📝

        * Sentiment Analysis using Vadir Score
        * Topic Modelling using Latent Dirichlet allocation
        * Sentence length & Text Complexity (Simple Measure of Gobbledygook Readability Level (SMOG) Score & Flesch-Kincaid (FK) Grade Level) using Textstat
        * Clustering using K-Means Model 
        * Text Vectorization using LSTM & TfIdf Vectorization
        * Dependency parsing using spacy En_cor_web_sm Model
        * Parts of Speech using NLTK
        * Named Entity Recognition using spacy En_cor_web_sm Model
    * Data Visualization & Exploratory Data Analysis using tools and libraries like 📊

        * Matplotplib
        * PyLDAvis
        * Seaborn
        * Plotly
        * d3.js
        * Tableau
        * Commonly used graphs were 

           * Bar Graph
           * Stacked Bar Graph
           * Network Co-occurrence Graph
           * Pie-Chart
           * Histogram
           * Bigram Graph
           * Violin Chart
           * Chord Chart
           * TreeMap
           * HeatChart
           * Box-and-Whisker Plot
           * Wordcloud
           * Line Chart
           * Bubble Plot
   * Machine Learning Model to detect Fake news based on extracted features 🔍
   
        * Long Short Term Memory Model (LSTM) using Pytorch
        * Bidirectional Encoder Representations Model (BERT) using Pytorch
        * Support Vector Machines (SVM) 
        * Naive Bayes ALgorithm

## How we built it 🛠️
We utilized the following Tools in building the project
   * VSCode, Google Colab & Jyupter Notebook to Run Code 
   * Python 3 as preferred Language of choice 🐍🥇
   * Tableau & Microsoft Excel for Data Exploration 📈

## Challenges we ran into 🧗‍♂️
Following were the main challenges we ran into:
   * GPU & RAM requirement, due to which we had to shift to Google Colab to run sessions
   * Limited Data features, due to which we had to invest time in data exploration and feature extraction

## Accomplishments that we're proud of 
We are proud of the following accomplishments:
   * Extracting insights & Developing a highly accurate machine learning model: We are proud to have developed a machine learning model that can accurately classify news articles as either real or fake, with a high degree of precision and recall.

   * Contributing to the fight against misinformation: By identifying fake news articles and helping to prevent their spread, we are proud to have made a valuable contribution to the ongoing effort to combat the spread of misinformation and its potentially harmful effects.

   * Advancing the field of natural language processing: Through our work on this project, we have contributed to the advancement of the field of natural language processing by exploring and developing innovative techniques for analyzing language patterns and identifying patterns that distinguish between real and fake news.

## What we learned 📚
We learned the following during this Hackathon 
   * Importance of data preprocessing: We learned that data preprocessing is a crucial step in any data analysis project. It is important to clean and transform the data before analyzing it to ensure the accuracy and reliability of the results.

   * Importance of feature engineering: We also learned the importance of feature engineering in building machine learning models. Creating relevant features from the raw data can greatly improve the accuracy of the models.

   * NLP techniques: We gained a deeper understanding of natural language processing techniques and how they can be applied to analyze text data. This included techniques such as text cleaning, tokenization, part-of-speech tagging, and dependency parsing.

   * Machine learning algorithms: We learned about various machine learning algorithms such as logistic regression, random forests, and support vector machines, and how they can be used to classify text data.

   * Collaborative working: We learned the importance of collaboration and communication in a team project. Working together allowed us to combine our skills and knowledge to produce better results than we would have achieved individually.



## What's next for True Hypothesis 🔮
There are several potential areas for future work in the data analysis of fake and real news:
   * Expanding the dataset: While there are currently large datasets available for training machine learning algorithms to identify fake and real news, these datasets may not be representative of all types of news articles. Future work could involve expanding the dataset to include articles from a wider range of sources, topics, and regions.
   * Developing new techniques: While current techniques for analyzing fake and real news are effective, there may be new techniques that could be developed to improve accuracy and efficiency. For example, researchers could explore the use of natural languages processing techniques, such as topic modelling or entity recognition, to identify patterns in news articles.
   * Combining multiple techniques: Rather than relying on a single technique for analyzing fake and real news, future work could involve combining multiple techniques to improve accuracy and reliability. For example, machine learning algorithms could be combined with manual content analysis to improve classification accuracy.
   * Assessing impact: While data analysis of fake and real news can provide insights into the prevalence and characteristics of fake news, future work could explore the impact of fake news on individuals and society as a whole. This could involve studying the effects of exposure to fake news on attitudes, beliefs, and behaviours.
   * Developing countermeasures: Finally, future work could focus on developing effective strategies and countermeasures for combating the spread of fake news. This could involve developing educational programs to help individuals identify fake news, or developing algorithms and tools to automatically detect and flag fake news articles.

