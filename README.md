#Customer Feedback Sentiment Analysis and Topic Modeling

##Overview
This Python script is designed to analyze customer feedback data. It performs sentiment analysis using two different methods (TextBlob and VADER) and conducts topic modeling using Latent Dirichlet Allocation (LDA). The code provides insights into sentiment distribution, sentiment variations across sources and locations, and identifies dominant topics within the feedback.

##Prerequisites
Before running the code, ensure you have the following libraries and tools installed:
- pandas
- matplotlib
- seaborn
- textblob
- nltk
- scikit-learn
You can install these libraries using pip:
          pip install pandas matplotlib seaborn textblob nltk scikit-learn
Additionally, you'll need to download NLTK data for stopwords and the VADER lexicon. You can do this by running the following code within your Python environment:
            import nltk
            nltk.download('vader_lexicon')
            nltk.download('stopwords')
            nltk.download('wordnet')
            nltk.download('punkt')

##Data Preparation:
Place your customer feedback data in a CSV file and provide the file path in the code.
Ensure that the CSV file contains a column with the feedback text.

##Run the Script:
Execute the Python script provided.
The script will perform data preprocessing, sentiment analysis, and topic modeling.

##View the Results:
Sentiment analysis results will be displayed using visualizations, including sentiment distribution, sentiment across sources and locations, and sentiment vs. confidence score.
Topic modeling results will show the dominant topics within the feedback data.

##Customization
You can adjust the number of topics for LDA by modifying the num_topics variable in the code.
You can customize the preprocessing steps by modifying the preprocess_text function to suit your specific requirements.

#Author : Manasvi Mishra 
