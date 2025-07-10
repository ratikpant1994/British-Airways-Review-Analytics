# British-Airways-Review-Analytics
**Overview**
A comprehensive data science pipeline was built to analyze British Airways customer reviews and uncover the main drivers of customer satisfaction and dissatisfaction. The project combined structured ratings, unstructured review text, and advanced machine learning to deliver actionable business insights.

**Applied Methods**
**Web Scraping**: Automated extraction of 3,949 reviews, ratings, and metadata from SKYTRAX.com.

**Data Cleaning**: Imputation of missing values, type conversion, and outlier handling for robust analysis.

**Text Processing**: Regex cleaning, tokenization, stopword removal, lemmatization (NLTK).

**TF-IDF Vectorization**: Extraction of top 100 keywords, enabling targeted keyword-based analysis.

**Sentiment Analysis**: VADER sentiment scoring to classify review tone and link sentiment to recommendation outcomes.

**Feature Engineering**: One-hot encoding for categorical variables; integration of TF-IDF features.

**Statistical Testing**: Chi-square tests to assess association between keyword mentions and recommendation rates.

**Predictive Modeling**: Random Forest Classifier to identify key drivers of recommendation, with feature importance analysis.

**Visualization**: Bar plots, histograms, and feature importance charts for clear communication of findings.
