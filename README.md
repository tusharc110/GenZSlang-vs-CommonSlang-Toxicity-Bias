# GenZ Slang vs. Common Slang Toxicity Bias

### Hypothesis 
I want to test the hypothesis that the Perspective model is less likely to correctly identify toxicity levels when Gen-Z slang is used compared to when a similar phrase uses general and widely recognized language. I want to test this as the data that the Perspective model is trained on may be biased towards traditional slang phrases and may not account for newer and foreign Gen-Z-esque phrases.

### Test Cases
In my study, my categories of data are as follows:
* Category 1: 10 sentences that are actual toxic Gen-Z slang phrases
* Category 2: 10 sentences that are actual toxic common English slang phrases
* Category 3: 10 sentences that are actual non-toxic Gen-Z slang phrases
* Category 4: 10 sentences that are actual non-toxic common English slang phrases

### Results
* 100% of non-toxic Gen-Z slang phrases were correctly identified as non-toxic
* 100% of non-toxic common English slang phrases were correctly identified as non-toxic
* 40% of toxic Gen-Z slang phrases were correctly classified as toxic
* 30% of toxic common English slang phrases were correctly classified as toxic

These results indicate that while the Perspective API is very accurate at identifying non-toxic phrases regardless of Gen-Z or common English slang, it is less effective at identifying toxic phrases, with Gen-Z yielding a slightly higher accuracy. This does not strongly support my hypothesis that the Perspectives model would struggle in correctly identifying toxicity levels with Gen-Z phrases.

### Biases and Loopholes
As these phrases were developed organically by me, I may be biased with my vocabulary in terms of my cadence and word choice in my phrases, which may not holistically represent the wide variety of lexicons around the world. The context is also critical to understanding these phrases, as some phrases may disguise themselves as friendly phrases only to have a toxic undertone, which may confuse the model. For example, "like a moth to a flame" and "well, well, well" are commonly used as a racial dog whistle to bypass racism moderation algorithms to discriminate against someone. In the same way, these seemingly yet not innocuous phrases can avoid the toxicity algorithm, which may have occurred during testing. 

### Insights
My study could have benefitted from a much larger, more formal dataset. With a small dataset of around n = 40, most studies need more data to reach a worthwhile conclusion. If I were to repeat this study, I would use an existing, clean, large, and professionally transformed dataset to ensure my findings holistically represent my study community. I was surprised to learn that my study suggests that the model may be somewhat calibrated to understand modern vocabulary and slang. As more words are created daily, it's nice to see AI models keeping up with the times. 
 
### DISCLAIMER
The phrases I wrote in the py.ipynb file are only for testing and research purposes. The phrases do not represent my personal thoughts or ideals whatsoever, and any relevance to my personal thoughts or ideals is purely coincidental. 
