# Self Project EXP Stock Status Repository
Creator: Xinghe ☆☆☆

Project Description: Mid-Long Term Investment Strategy based on EXP Stock Status Recognition System
* Data Collection
    * [Crunchbase](https://www.crunchbase.com/)
        * API for balk data -- waiting for the price quote
        * Scrape with pro acccount (5000 limits/month) -- strong defense of bot detection from [PermeterX](https://www.perimeterx.com/resources/case-studies/crunchbase/)); developing working-around methods
        * Manual pull (5000 limits/month) -- current data origin
    * [US Patent office](https://www.uspto.gov)
        * searching for patents of companies of interest using API
        * NLP for understanding the patents
    * News websites about the biomedical, food, and health
        * scraping news data
        * Analyze the sentiment about the news
        * calculate the sentiment score
    * python: selenium, beautifulsoup
* **Explotary Data Analysis**
    * Build python classes to facilite the EDA pipelines
    * numerical, categorical, text data processing pipelines
    * feature engineering using dummpy variables, onehot encoding, natural language processing
    * combine all data for ML
    * python: pandas, numpy, sklearn, NLTK, SpaCy
