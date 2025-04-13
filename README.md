<h1>Android Google Play Store Data</h1>

**About the Project:**
• We explored Google Play Store data to understand app market trends and user opinions.
• Used data cleaning, basic stats, and simple visuals to see how apps perform and what users think.

**Project Objective:**
• To learn which app categories dominate, how ratings and sizes relate, and what users say in their reviews.

**Dataset Details:**
• File: Android app.zip (contains apps.csv and user_reviews.csv)
• apps.csv columns include:

• App (name)

• Category

• Rating (stars)

• Reviews (count)

• Size (Mork)

• Installs (count)

• Type (Free/Paid)

• Price ($)

…and more
• user_reviews.csv columns include:

• App

• Translated_Review (text)

• Sentiment (Positive/Negative/Neutral)

• Sentiment_Polarity (–1 to +1)

• Sentiment_Subjectivity (0 to 1)


**Steps Followed in the Project:**

1. Data Loading: Read both CSVs into tables.


2. Data Cleaning:

   • Removed duplicates and empty rows.

   • Converted Size, Installs, Price, and Rating into numbers.



3. Category Exploration: Counted apps per category and found the top 10.


4. Metrics Analysis:

   • Plotted rating distribution.

   • Compared app size vs. rating.

   • Checked ratings for Free vs. Paid apps.

   • Looked at price spread for paid apps.



5. Sentiment Analysis:

   • Cleaned review text and dropped blanks.

   • Scored reviews for polarity and subjectivity.



6. Interactive Visualization: Made clear charts:

   • Bar chart for top categories

   • Histograms for ratings and sentiment scores

   • Scatter plots to spot trends (size vs. rating, polarity vs. subjectivity)




**Libraries Used:**
   • Python
   • Pandas
   • Numpy
   • Matplotlib & Seaborn
   • TextBlob (for sentiment)
   • Google Colab / Jupyter Notebook

**How to Run the Project:**

1. Unzip Android app.zip in Colab or Jupyter.


2. Load apps.csv and user_reviews.csv.


3. Run steps in order: cleaning → exploration → metrics → sentiment → visuals.


4. View charts and insights.



**Final Takeaways:**
  • Family, Games, and Tools apps dominate the store
  • Most apps rate between 4.0–4.5 stars
  • Paid apps slightly outperform free ones in ratings
  • Reviews are mostly positive, with varied subjectivity
  • Simple data steps and charts can reveal big market trends
