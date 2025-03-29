# Special_Topics_CSIS-4260-002-Assignment_02

Dependencies to download if applicable:
  pip install selenium pandas webdriver-manager
  !pip install vaderSentiment


---- ANALYSIS ----

Part 1 Benchmarking:

For benchmarking using different libraries for web scrapping, I have used 'BeautifulSoup' and 'Selenium' as my selected libraries. The analysis is done for a website that contains news articles. By ruuning benchmarking for these selected individual web scrapping libraries for a single page in the website(a single page contains 30 articles), BeautifulSoup performs well comparing to Selenium in terms of execution time. The execution time for BeautifulSoup is less than Selenium. Their respective execution time is documented in the notebook itself and results have been saved as CSV files for reference. After carefully selecting BeautifulSoup as the appropriate library to scrape 100 articles, the results along with the total time for the execution is also documented in the notebook and saved as CSV. I have attached the relevant CSV files for reference.

Part 2 Text Analysis:

For text analysis, I used two algorithms:

1. TF-IDF (Term Frequency-Inverse Document Frequency) → Importance Score
 
   Measures the significance of words in the statement.
   Helps compute the importance score based on weighted word frequencies.

2. VADER (Valence Aware Dictionary and sEntiment Reasoner) → Sentiment Analysis

   Determines the direction (Positive/Negative) of the statement.
   Selects the top 2 sentences for the summary based on polarity.
