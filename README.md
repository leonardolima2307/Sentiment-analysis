# Sentiment-analysis

Sentiment Analysis
The sentiment property returns a namedtuple of the form Sentiment(polarity, subjectivity). The polarity score is a float within the range [-1.0, 1.0]. The subjectivity is a float within the range [0.0, 1.0] where 0.0 is very objective and 1.0 is very subjective.

>>> testimonial = TextBlob("Textblob is amazingly simple to use. What great fun!")
>>> testimonial.sentiment
Sentiment(polarity=0.39166666666666666, subjectivity=0.4357142857142857)
>>> testimonial.sentiment.polarity
0.39166666666666666

source http://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis

Thanks to https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A
