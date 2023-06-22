# Comment2Likes: Estimating Video Likes using Comment Data

## Project Description
Comment2Likes is a data science project aimed at developing a predictive model to estimate the number of likes a video will receive based on the information extracted from its comments. By leveraging valuable insights from user comments, this project aims to provide content creators, marketers, and platform administrators with a tool to gauge the potential popularity of their videos and optimize their content strategies accordingly.

## Dataset
The dataset consists of two files:
- `videos-stats.csv`: Contains basic information about each video, such as title, likes, views, keyword, and comment count.
- `comments.csv`: Contains the top ten most relevant comments for each video, along with the comment text, likes, and sentiment.

Dataset Link: [Data_Link](https://example.com/dataset)

## Project Workflow
1. Data Cleaning: Remove duplicates and handle missing values in the dataset.
2. Exploratory Data Analysis (EDA): Visualize video likes distribution, analyze the relationship between comments and likes/views, identify common keywords, and explore comment sentiments.
3. Natural Language Processing (NLP): Perform tokenization, remove stopwords, and analyze comment sentiment using NLP techniques.
4. Feature Engineering: Extract meaningful features from comments for predictive modeling.
5. Predictive Modeling: Build a machine learning model using processed comment data to predict video likes.
6. Model Evaluation: Evaluate the performance of the predictive model using appropriate evaluation metrics.
7. Presentation: Create a PowerPoint presentation summarizing the problem statement, tools used, approaches, and EDA insights.

## Tools and Technologies
- Data Cleansing: Python, Pandas library.
- Exploratory Data Analysis (EDA): Python, Matplotlib, Seaborn libraries.
- Natural Language Processing (NLP): Python, NLTK, Scikit-learn libraries.
- Machine Learning: Python, Scikit-learn, XGBoost, TensorFlow, or PyTorch libraries.
- Version Control and Code Repository: GitHub.
- Presentation: PowerPoint.

## Project Structure
The project repository contains the following files and directories:
- `videos-stats.csv`: Dataset file containing video statistics.
- `comments.csv`: Dataset file containing comment data.
- `notebook.ipynb`: Jupyter Notebook file containing the code for data cleaning, EDA, NLP, and predictive modeling.
- `presentation.pptx`: PowerPoint presentation summarizing the project.
- `README.md`: Documentation file providing an overview of the project.

