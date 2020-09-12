# Sentiment Analysis using Natural Language Processing
What is Sentiment Analysis?


It is a context-based mining of text which extracts and identifies subjective information from text or sentence provided.
It is a most common text classification technique that analyses the incoming text and interpretes whether the underlying sentiment is positive, negative or neutral.
Sentiment Analysis helps business to understand the social sentiment of their brands, services or products from the online conversation happening on various social media platforms like Twitter, Facebook etc. Through this Sentiment Analysis companies have an edge over their competitors by knowing how customers are reacting to their products. This analysis is improved by using RNN algorithms.

The project will show a bar chart where all the emotions with its respective percentage in the text is displayed. Also, it will display the most dominant emotion as well as 
the overall sentiment of the text(positve, negative or neutral).

# Using NLP Concepts
1. Cleaning Text- Convert all to lowercase and remove punctuations.
2. Tokenisation and stop words- Splitting the sentences into words and removing the words which don't add any meaning(e.g I) respectively.
3. NLP emotion algorithm-
(i) Check if the word in the final word list is also present in emotion.txt 
  -> Open the emotion file.
  -> Loop through each line and clear it.
  -> Extract the word and emotion using split.
 (ii) If the word is present-> Add emotion to the emotion list.
 (iii) Finally count each emotion in the emotion list.
4. Count the frequency of the emotion to determine the dominant emotion.





