# EmotionEmbedding
Emotion and word analysis

Read in the following dataset:

https://alpha.lyssn.io/emotionwithembeddings.json (note- this is a pandas formatted json)


1.Create a couple of data visualizations showing frequency of the different emotions, and the distributions of confidence by emotion

2.Is there a relationship between certain emotions and the rater’s confidence in those emotions? (i.e. are some emotions inherently less obvious to raters?) Make you case both statistically and with visualizations

3.Build a python (object oriented) class that is designed to tokenize the sentences and keep track of which emotions get associated with each word.

  Should have a method add_one_sentence(sentence, emotion) that breaks the sentence into words (i.e. unigrams) that are case insensitive and logs counts of each word-     emotion association

  Should have a function to return the frequency of each emotion for an individual word normalized by the base rates for the emotions (i.e. how frequently is a specific   categorized as each emotion, after accounting for how frequent each emotion is in the dataset)

  Plot these distributions for the words that 1) appear more than 100 times but 2) have the emotion distributions that are the most different from the base rates of each   emotion (based on whatever metric you like)

4.Are the sentence vectors useful in predicting the emotion labels (1024 dim vectors in the last column)? Make your case either way.
In addition to statistical evidence, show some data visualization to show how the vector does or doesn’t map to emotion labels
