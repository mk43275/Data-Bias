# Data-Bias
Bias and Fairness Assessment of Models 

In this analysis, I will analyze if Perspective API is capable of detecting less commonly used harmful words(slurs, curse words, etc.). I am only using a small sample, which will not ensure the accuracy of the results for other instances and tests ran with the Perspective API. I used 5 words that came up as "least common curse words" on Google Search Engine, and with those words I tested the toxicity percentages in 4 ways. First is the word itself, second was the words combined with the word "you" to show it being used directly against someone, thirdly, I incorporated words that hid/undermined the meaning of the harmful words, and lastly, I used the less harmful word combinations with "you" again. The data provided in Jupyter will show the results of the analysis.

Hypothesis:
Perspective API will fail to detect less commonly used curse words/slurs in english.

Less commonly used curse words used(5 examples from google):
Arse, Cunt, Turd, Cow, Bugger

Analysis/Report:
