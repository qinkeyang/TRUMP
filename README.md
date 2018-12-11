# TRUMP
scrapy for trump twitter
first scrap trump tweeter in 2017 and 2018, and clean the text. But in this model, I cannot remove the hashtags without lose information.
second get the approval_rate data
then i convert the approval_rate data by setup threshold which decide whether the data change should be marked as increase or decrease.
after this doing wordembedding from glove and set up a series of nerual network to find the relationship for trump tweet and the change of approval rate
However, my teacher told me from the output, there is little learned by the neural network, I have to consider maybe what said my trump has little influence on the approval rate, but what the response from people is more important. 
So I have to consider the number of retweet and likes in the tweeter
Also the commend(which is a huge dataset and not allowed for me to analyze in computer)
or I could set a social graph which include some celebrities and found the people response from their retweet of Trump tweeter.
