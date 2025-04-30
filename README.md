# StarWarsLDA
hank you for joining me today! The purpose of this tutorial is to conduct webscraping of Star Wars movie scripts and then use a Natural Language Processing (NLP) method called Latent Dirichlet Allocation, often abbreviated as LDA, to do "Topic Modeling". A lot of vocab, I know! Topic modeling is when we discover underlying themes, or "topics" within textual data, and LDA is the algorithm we use to accomplish that. Basically, we do not have to manually look thousands of words to do that ourselves! The web scraping will be done with a package in Python called "Beautiful Soup", which simply extracts specific text from the websites that we call, rather than having to go to each URL and copy paste it ourselves.

The algorithm will not tell us the meaning of each topic. Rather, we as experts in Star Wars will look at the groupings, which are based on appearing in similar contexts, and decide what to call that topic.

This process is useful because if you have a lot of text data, whether movie scripts or something more business oriented such as customer reviews, it can help summarize key themes without us having to read each line.

Here is a brief overview of all that we will do in this tutorial:

1.) Web scrape movie scripts from all Star Wars Movies (Episodes I - IX, Rogue One, and Solo, for a total of 11 scripts)

2.) Clean and preprocess the text data (this just means making it look nice so that the LDA algorithm can best analyze it, we can't be giving it dirty/uncleaned data!)

3.) Apply LDA to get the word groupings or "topics"

4.) Look at the topics, and with our Star Wars expertise, label each topic.

4.5) If the topics look a little bit wonky, we can modify our model parameters and re-run them.

5.) Interpret and visualize our results!
