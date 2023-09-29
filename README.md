<h1>Customer Feedback Sentiment Analysis and Topic Modeling</h1>

<h2>Overview</h2>
This Python script is designed to analyze customer feedback data. It performs sentiment analysis using two different methods (TextBlob and VADER) and conducts topic modeling using Latent Dirichlet Allocation (LDA). The code provides insights into sentiment distribution, sentiment variations across sources and locations, and identifies dominant topics within the feedback.

<h3>Prerequisites</h3>
Before running the code, ensure you have the following libraries and tools installed:
<li>pandas</li>
<li>matplotlib</li>
<li>seaborn</li>
<li>textblob</li>
<li>nltk</li>
<li>scikit-learn</li>


<p> You can install these libraries using pip:   
                
    pip install pandas matplotlib seaborn textblob nltk scikit-learn
         
Additionally, you'll need to download NLTK data for stopwords and the VADER lexicon. You can do this by running the following code within your Python environment: 

         
                import nltk
                nltk.download('vader_lexicon')
                nltk.download('stopwords')
                nltk.download('wordnet')
                nltk.download('punkt') 
            


<h3>Usage</h3>
<h4>1. Data Preparation:</h4>
Place your customer feedback data in a CSV file and provide the file path in the code.
Ensure that the CSV file contains a column with the feedback text.

<h4>2. Run the Script: </h4>
Execute the Python script provided.
The script will perform data preprocessing, sentiment analysis, and topic modeling.

<h4>3. View the Results:</h4>
Sentiment analysis results will be displayed using visualizations, including sentiment distribution, sentiment across sources and locations, and sentiment vs. confidence score.
Topic modeling results will show the dominant topics within the feedback data.

<h4>4. Customization:</h4>
You can adjust the number of topics for LDA by modifying the num_topics variable in the code.
You can customize the preprocessing steps by modifying the preprocess_text function to suit your specific requirements.

<h3>Author</h3> Manasvi Mishra 
