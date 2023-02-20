# Viral-Tweets-Prediction
EDA for Viral Tweets, analyzing data sets to summarize their main characteristics


Problem Description:

In today's world virality is a very important tool,
A post, a video, a picture and more... can be viral.
We will focus on this project mainly on finding a solution in the field
The posts on social networks because this is the most talked about problem

Will a post go viral?

Method Chosen:

I started by researching the, in order to find the features that characterize a post in the best way.
The selected features are: number of tags, amount of likes on the last post, amount of shares on the last post, length of the post.
In order to represent the data we used a scale (normalization of the data is important because I use KNN) according to the selected features.
And to build the prediction model we used KNN whose number of neighbors is chosen by a loop which each time increases K by 1 until we reach N.

SCORING:

Since a viral post is usually characterized by external factors, i.e. other users, I came to the conclusion that I will have to classify virality according to a formula that tested the post viral is indeed.
Viral = 0.3333 * likes + shares

Results:

In conclusion, I reached an accuracy result of over 95 percent, this was possible thanks to the survey method and the experiments on the number of K. In addition, we reached an unequivocal conclusion that our data will not take into account such and such words (sometimes virality is unethical). Instead I did a detailed EDA and gave tips to the post writer for recommended words.
