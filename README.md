# Criminal-Sentiment-Detection
The aim of the project is to predict early signs of criminal sentiments through social media text mining.

Social media sentiment analysis is the process of interpreting and determining whether the social media collected text data is positive, negative, or neutral. It goes beyond just collecting and counting the number of mentions, comments, or hashtags.
Analyzing sentiment gives you deeper insight into the attitudes, opinions, and emotions behind the text. 
Social media data also have curse of dimension problem i.e. high dimension nature of data that required specific pre-processing and feature extraction, which leads to improve classification accuracy.

ALGORITHMS USED:
1) Random Forest
2) KNN
3) SVM
4) Naive Bayes
5) Decision Tree

DEMO:

![image](https://user-images.githubusercontent.com/53509075/168728932-a0dc4bcf-517b-449a-8956-71038c416863.png)
Negative denotes that it is the highest level where criminal sentiments and anxiety symptoms are being detected through the user’s tweets. The more negative words the user uses mean the more negative emotion the tweet has.

![image](https://user-images.githubusercontent.com/53509075/168728971-8b2fdc1e-ea49-4741-948f-1963092b2024.png)
Positive, this mean that person is unlikely to have criminal sentiments or anxiety.

![image](https://user-images.githubusercontent.com/53509075/168729044-00236b96-284e-4675-b24c-3bca0844c639.png)
Neutral, This is the middle level wherein the user may or may not have criminal sentiments but may also be more prone to being affected by it.

RESULTS:

![image](https://user-images.githubusercontent.com/53509075/168728526-90987b70-9745-4d05-b79a-76370dce4f3f.png)

It can be observed that the training performance of Naïve Bayes, Support vector machine, K-Nearest Neighbor, Random Forest were appreciable, but these models did not perform well for testing sets. It can be observed that Decision Tree produced better performances for training, validation, and testing sets.


