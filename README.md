
# PotterBot
A bot that posts Harry Potter quotes to Twitter. The goal of the bot is to examine the current top trends on Twitter from large cities like New York, Los Angeles, and Philadelphia, and associate the trends with relevant Harry Potter quotes. Quotes are scraped from the GoodReads pages of all seven Harry Potter books using JSoup and regular expressions. They are processed as documents in corpus and compared for similarity to trends using a vector space model and tf-idf values. The best quotes are posted to Twitter using the API of Twitter4j.
## Usage
To run the program, it suffices to execute the PotterBotMain class. To customize what kind of books are used, one could modify the URLs used in the PotterBot class.
## External Libraries
JSoup - https://jsoup.org/
Twitter4j - http://twitter4j.org/en/index.html
## Other Resources
Information retrieval - http://www-nlp.stanford.edu/IR-book/
