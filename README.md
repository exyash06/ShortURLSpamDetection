# Short URL Spam Analysis
Analysis and detection of short url spam on twitter. Achieved an accuracy of 89.23% on 100,000 tweets.

## Steps performed ##
1. Collecting 100,000 tweets containing bit.ly short url using Twitter API.
2. Gathering meta-data about each short url using Bitly API.
3. Storage of all information in MongoDB.
4. Analysis of the information to discover significant patterns.
5. Classification of short urls using [Weka] (http://www.cs.waikato.ac.nz/ml/weka/).
