# Data-Bias
Bias and Fairness Assessment of Models 

In this analysis, I will analyze if Perspective API is capable of detecting less commonly used harmful words(slurs, curse words, etc.) by finding the toxicity percentages of those words, and comparing the top 5 frequently used toxic words' toxicity percentages in the Sample_labaled_data.csv with the least commonly used curse words toxicity percentages. I am only using a small sample, which will not ensure the accuracy of the results for other instances and tests ran with the Perspective API. I used 5 words that came up as "least common curse words" on Google Search Engine, and with those words I tested the toxicity percentages in 5 ways. First is the word itself, second was the word capitalized, third was the words combined with the word "you" to show it being used directly against someone, next, I incorporated words that hid/undermined the meaning of the harmful words, and lastly, I used the less harmful word combinations with "you" again. The data provided in Jupyter will show the results of the analysis.

Hypothesis:
I will be testing two hypothesis in this project with Perspective API.

  1) The top 5 toxic words(most frequently used in the sampled data csv) will have higher toxicity percentages than the 5 least used  curse words(sourced from google search engine).

  2) The 5 Least Common Used Curse Words will have the highest percentages when it is directed towards someone than in other      instances.
    -  testing the word itself, the word capitalized, the word with "you', the word with other words, the word with "you" and other          words.

Less commonly used curse words used(5 examples from google):
Arse, Cunt, Turd, Cow, Bugger

Analysis/Report:
There was a lot of variance with the toxicity percentages in both lists(toxic words and least commonly used curse words), but the toxic word list had the highest percentage with the word "bitch". 

The tests with the LCU(Least Commonly Used curse words) showed that there are differences with the words being non-capitalized or capitalized, but there is slight variance in all of them where some increase(turd) and some decrease(cunt, cow, bugger, and arse). The LCU used with "you" increase the toxcitiy percentage exponentially for all words, as it is being directed to another person. LCU being used with words that try to cover up its meaning showed that some percentages decreased even more than the original word itself (cow and bugger), and some were lower than it being used with you but not lower than itself(turd, cunt, arse). The LCU with you and the words that cover up its meaning are higher percentages than the word itself and the LCu with just the words covering up its meaning, but most are lower than the percentages with just "you"(turd, cunt, cow, and bugger) except arse.

Conclusion: 
- Not all of the words from the top 5 toxic words lists(frequently used) were not all higher than the 5 Least commonly used curse words list.

- For the majority, the 5 Least commonly used curse words did have the highest percentage with the word "you" except for one, which was 'arse', and its highest percentage was 78.57% when it was with the word "you" and others, so using the other word just amplified it more.


