# Capstone 5 - Prediciton of Stock Movement Based on Earnings Call Analysis

# Jacob Kovach
# Confidential and Proprietary

Summary:

In this project I aim to create a predictive model of the movement of stock prices based on the company's earnings call. Primary data was obtained using the "Capstone 5 - Call Transcript Scraper" module to scrape ~13500 individual earnings call transcripts from The Motley Fool (www.fool.com). Transcripts were saved locally and recalled in "Capstone 5 - Data Creation and Cleaning" to create a dataframe file of 500 transcripts and list of common words between 3 classes of stock movement: 

  -Significant Increase: Stock closing price delta resulted in an increase of more than 4% between closing price day-of-call minus 1 and closing price day-of-call plus 7. Class 2
  
  -No Movement: Stock closing price delta resulted in movement between 4% and -4% between closing price day-of-call minus 1 and closing price day-of-call plus 7. Class 1
  
  -Significant Decrease: Stock closing price delta resulted in a decrease of more than -4% between closing price day-of-call minus 1 and closing price day-of-call plus 7. Class 0
  
Analysis and modeling of data was conducted using tfidf vectorization and several classifiers in "Capstone 5 - Data Analysis" module. Call files are available available upon request but too numerous to hold in this repo. "call_df_500" file was likewise to large to upload, but available upon request.
