# Social-Media-Analysis-Samsung-Galaxy-S8-iPhone-X
[Sentiment Analysis] Analyzed pre and post release text data consisting of consumer posts, comments, and reviews of two different phone models to derive key attributes by using embeddings to find words related to quality, price, and value. Based on these attributes, inferred the sentiment before and after launch of both products using NLP, TF/IDF and LDA.

Overview

This dataset is natural language text data of consumer posts, comments and reviews on Samsung Galaxy S8 and iPhone 8 and X models. The timeline of these posts precede the release of each of the phones by about a month and then continue on for a few months after the announcement.

Background:
Samsung Galaxy S8 was released March 29, 2017 iPhone 8 and iPhone X were released Sep 22, 2017
The data files consist of two sets of files. One for all sources other than Twitter. The other set of files is Twitter only.
Non-Twitter Data: 10 files named Streams (1).xlsx through Streams(10).xlsx. Each Excel file has a chunk of data for a few weeks at a time starting from 3/14 through 6/6 and from 9/13 through 10/31.
1. 3/14 to 3/31: Stream (2).xlsx
2. 4/1 to 4/19: Stream (3).xlsx
3. 9/13 to 9/19: Stream (4).xlsx
4. 9/20 to 9/27: Stream (5).xlsx
5. 9/28 to 10/9: Stream (6).xlsx
6. 10/10 to 10/24: Stream (7).xlsx 7. 10/25 to 10/31: Stream (8).xlsx 8. 4/20 to 5/3: Stream (9).xlsx
9. 5/4 to 5/25: Stream (10).xlsx 10. 5/26 to 6/6: Stream (11).xlsx
Twitter Data:
Data between 3/1/17 thru 6/30/17: T Only 3_1_2017 thru 6_30_2017 Random Stream (1).xlsx
Data between 9/1/17 thru 10/31/17: T Only 9_1_2017 thru 10_31_2017 Random Stream (1).xlsx



NOTES:
1. There could be some duplicate posts in the last two Twitter data exports due to the nature of how the Twitter data has to be captured and exported. You should eliminate them before processing.
2. The details, Sources on the dates etc. are at the bottom of each Excel file. Remove them before ingesting them into your programs.

The natural language data to be processed and analyzed is under Column “Sound Bite”. In addition, you are free to use other structured data elements for a more advanced analysis (e.g. time, type of Source, gender etc.)

The goal of the dataset is to focus on data from regular consumers, NOT from news sources and professional experts. Filters have been applied to discard some of the non-relevant data (e.g. discard news sources and professional reviewers). Further, the underlying tool used to capture the data has to make inferences on how to exactly match before capturing or discarding data, the relevance to the topic varies and will sometimes pull in non-relevant data. In addition, many will also talk about other models/products from the companies (e.g. Galaxy Note, ipads etc.).
Due to the nature of how consumers talk and communicate, the language is not precise.


Tasks

Your task is to process and analyze the natural language data under “Sound Bite”. In particular, here are some comparisons and questions that you could tackle:
- Extract information for the following products: Galaxy S8, iPhone X, iPhone 8.
- What were the most important attributes for each product?
- What attributes were liked the most and what attributes weren’t?
- In particular, how did consumers feel about the Quality, Price and “Value” for each product?
- What was the sentiment for these products? Did the sentiment change BEFORE and AFTER the launch of the products? How?
- Extra Credit: Can you predict the uptake or adoption of the product by looking solely
at the pre-release data? Can you “validate” that by looking at the post-release data? 
- Extra Credit: Process the Twitter and non-Twitter datasets separately for some of the tasks. Can you draw any conclusions on the ease or accuracy of processing and analysis for these two sets? Was one set of sources easier, more accurate than the other?


Some notes on pre-processing data before analysis:
1. You can eliminate more of the non-relevant data by eliminating posts from authors
that have a large number of followers (Column: No. of Followers/Daily Unique
Visitors): they will likely be professionals or celebrities.
2. You may want to process just the Original Posts rather than Original as well as
Replies and Comments (Column: Post Type). Retaining context is tricky when
looking at Replies and Comments.
3. The details, Sources on the dates etc. are at the bottom of each Excel 


