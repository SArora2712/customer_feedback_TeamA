📊 ReviewSense
Turning Customer Feedback into Actionable Insights

🚀 ReviewSense is an end-to-end Customer Feedback Analytics System that transforms raw textual reviews into meaningful business intelligence using Natural Language Processing (NLP) and interactive data visualization.

The system processes unstructured customer opinions and converts them into structured insights, sentiment trends, and decision-support dashboards for organizations.

✨ Key Features

✅ Automated text preprocessing pipeline
✅ NLP-based sentiment classification
✅ Keyword frequency intelligence
✅ Interactive business intelligence dashboard
✅ Dynamic filtering & export functionality
✅ Real-world analytics workflow implementation

🏗 System Workflow
Raw Customer Reviews
        ↓
Text Cleaning & Standardization
        ↓
Sentiment Classification
        ↓
Keyword Extraction
        ↓
Interactive BI Dashboard
        ↓
Actionable Business Insights
🔹 Milestone 1 – Data Cleaning & Preprocessing
🎯 Objective

Prepare raw textual feedback for accurate NLP processing.

⚙️ Processing Steps
Removed special characters and punctuation
Converted text to lowercase
Eliminated redundant spaces
Standardized textual formatting
Generated a new processed column → clean_feedback
📥 Input
Raw feedback dataset (CSV)
📤 Output
Milestone1_cleaned_feedback.csv
🛠 Tools Used
Python
pandas
Regular Expressions (re)
🔹 Milestone 2 – Sentiment Analysis
🎯 Objective

Classify customer opinions into sentiment categories.

📊 Sentiment Classes
Positive
Negative
Neutral
⚙️ Implementation
Applied TextBlob polarity scoring
Generated confidence scores
Created sentiment distribution visualization
Produced sentiment bar chart
📥 Input
Milestone1_cleaned_feedback.csv
📤 Outputs
Milestone2_Sentiment_Results_new.csv
sentiment_bar_chart.png
📌 Output Fields
clean_feedback
sentiment
confidence_score
🛠 Tools Used
Python
pandas
TextBlob
matplotlib
🔹 Milestone 3 – Keyword Extraction
🎯 Objective

Identify high-frequency keywords from customer reviews.

⚙️ Processing Steps
Lowercased textual data
Removed non-alphabetic characters
Tokenized words
Computed frequency using Counter
Ranked keywords based on occurrence
📥 Input
Milestone2_Sentiment_Results_new.csv
📤 Output
Milestone3_Keyword_Insights.csv
📌 Output Fields
keyword
frequency
🛠 Tools Used
Python
pandas
collections.Counter
Regular Expressions (re)
🔹 Milestone 4 – Interactive BI Dashboard
🎯 Objective

Visualize analytical insights through an interactive dashboard.

🎛 Dashboard Filters
Sentiment selector
Product filter
Date range selection
📌 KPI Indicators
Total Reviews
% Positive Reviews
% Negative Reviews
% Neutral Reviews
📊 Visualization Components
Sentiment distribution bar chart
Product-wise sentiment summary
Sentiment heatmap
Monthly sentiment trend analysis
Top keyword frequency chart
Word cloud representation
Confidence score histogram
📤 Export Capabilities
Download filtered review dataset
Download keyword insights
📥 Inputs
Milestone2_Sentiment_Results_new.csv
Milestone3_Keyword_Insights.csv
📤 Outputs
Interactive Streamlit Application
ReviewSense_Filtered_Reviews.csv
ReviewSense_Keywords.csv
🛠 Technology Stack
Python
pandas
TextBlob
matplotlib
seaborn
WordCloud
Streamlit
▶️ Installation & Execution
Step 1 — Install Dependencies
pip install pandas textblob matplotlib seaborn wordcloud streamlit
Step 2 — Run Sentiment Analysis
python milestone2.py
Step 3 — Run Keyword Extraction
python milestone3.py
Step 4 — Launch Dashboard
python -m streamlit run milestone4.py
📊 Business Value

ReviewSense helps organizations to:

Monitor customer satisfaction levels
Evaluate product performance
Identify recurring customer issues
Track sentiment trends over time
Enable data-driven strategic decisions
Generate exportable reports for stakeholders
🎓 Learning Outcomes
Practical NLP preprocessing techniques
Sentiment classification using polarity scoring
Keyword intelligence generation
Data visualization best practices
Interactive dashboard development
End-to-end analytics pipeline design
🏁 Project Summary

ReviewSense demonstrates a complete real-world feedback analytics pipeline, transforming raw reviews into:

✔ Sentiment Insights
✔ Keyword Intelligence
✔ Interactive Business Dashboards

This solution is suitable for business intelligence, customer experience analysis, and decision-support systems.

