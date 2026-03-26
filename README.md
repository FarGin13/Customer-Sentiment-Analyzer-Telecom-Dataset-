<h1>Customer Sentiment Analyser (Telecom Dataset)</h1>

<h2>Overview</h2>
<p>
This project analyzes telecom customer feedback using Natural Language Processing (NLP)
to classify sentiment as <b>Positive</b>, <b>Negative</b>, or <b>Neutral</b>.
</p>

<h2>Project Objective</h2>
<p>
The goal of this project is to understand customer opinion from telecom feedback data
and generate useful business insights related to customer experience, satisfaction, and churn.
</p>

<h2>Features</h2>
<ul>
  <li>Text cleaning and preprocessing</li>
  <li>Sentiment analysis using TextBlob</li>
  <li>Classification into Positive, Negative, and Neutral sentiment</li>
  <li>Visualization of sentiment distribution</li>
  <li>Analysis by churn status, service type, gender, and tenure group</li>
</ul>

<h2>Dataset</h2>
<p>
This project uses a telecom customer churn dataset that includes structured customer data
along with customer feedback text.
</p>

<p>
<b>Dataset Source:</b><br>
<a href="https://www.kaggle.com/datasets/beatafaron/telco-customer-churn-realistic-customer-feedback" target="_blank">
Telco Customer Churn - Realistic Customer Feedback (Kaggle)
Used the main dataset -"telco_churn_with_all_feedback"
</a>
</p>

<ul>
  <li><b>customerID</b> - unique customer identifier</li>
  <li><b>gender</b> - customer gender</li>
  <li><b>InternetService</b> - type of internet service</li>
  <li><b>Contract</b> - contract type</li>
  <li><b>tenure</b> - number of months as a customer</li>
  <li><b>MonthlyCharges</b> - monthly bill amount</li>
  <li><b>Churn</b> - whether the customer left or stayed</li>
  <li><b>CustomerFeedback</b> - written customer review</li>
</ul>

<h2>Tools and Technologies</h2>
<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>TextBlob</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Google Colab</li>
</ul>

<h2>Workflow</h2>
<ol>
  <li>Load the raw telecom dataset</li>
  <li>Clean and preprocess customer feedback text</li>
  <li>Apply sentiment analysis using TextBlob</li>
  <li>Generate polarity, subjectivity, and sentiment labels</li>
  <li>Analyze sentiment trends across customer groups</li>
  <li>Visualize results using charts</li>
  <li>Export final results to CSV</li>
</ol>

<h2>Sentiment Metrics</h2>
<p>
<b>Polarity</b> measures how positive or negative a text is, ranging from
-1 (very negative) to +1 (very positive).
</p>

<p>
<b>Subjectivity</b> measures how opinion-based a text is, ranging from
0 (objective/factual) to 1 (highly subjective/opinion-based).
</p>

<h2>Key Insights</h2>
<ul>
  <li>Most customer feedback shows positive sentiment</li>
  <li>Negative sentiment is more common among churned customers</li>
  <li>Customer satisfaction differs across service types</li>
  <li>Customer tenure can influence sentiment trends</li>
</ul>

<h2>How to Run</h2>
<ol>
  <li>Open the notebook in Google Colab</li>
  <li>Upload the telecom dataset file</li>
  <li>Run all cells step by step</li>
  <li>View charts and analysis results</li>
  <li>Download the generated <code>sentiment_results.csv</code> file</li>
</ol>

<h2>Output</h2>
<ul>
  <li>Sentiment classification results</li>
  <li>Summary statistics</li>
  <li>Visual charts</li>
  <li>Saved CSV output file</li>
</ul>

<h2>Future Improvements</h2>
<ul>
  <li>Compare sentiment results with preprocessed datasets</li>
  <li>Add machine learning models for sentiment classification</li>
  <li>Build a churn prediction model using sentiment as a feature</li>
  <li>Create an interactive dashboard</li>
  <li>Improve text preprocessing for more accurate sentiment analysis</li>
</ul>

<h2>Author</h2>
<p>Fargin Binta Anowar</p>
