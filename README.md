# Sentiment Analysis Of YouTube Comments
This MATLAB script calls and runs a YouTube comment scrapper from python and then puts said comments through a sentiment analysis model. It
outputs a spreadsheet with a series of scores: the total positive and negative scores and the average negative and postive scores. 

The YouTube comment scrapper is a modified version of https://github.com/egbertbouman/youtube-comment-downloader so that the main function 
takes arguments instead of having to call the module with arguments. 

The sentiment analysis model is a modified version of the demo found here: https://www.mathworks.com/help/textanalytics/ug/train-a-sentiment-classifier.html
