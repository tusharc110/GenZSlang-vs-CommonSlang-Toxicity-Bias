# GenZ Slang vs. Common Slang Toxicity Bias

### Hypothesis 
I want to test the hypothesis that the Perspective model is less likely to identify toxic content when Gen-Z slang is used compared to when a similar toxic phrase uses general and widely recognized offensive language. I want to test this as the data that the Perspective model is trained on may be biased towards traditional toxic slang phrases and may not account for newer and foreign Gen-Z-esque toxic phrases.

### Results
* The average toxicity score (from 0 to 1) for Gen-Z slang phrases is approximately 0.447
* The average toxicity score (from 0 to 1) for general English slang phrases is approximately 0.364
* 40% of Gen-Z slang phrases were classified as toxic
* 30% of general English slang phrases were classified as toxic

Toxic Gen-Z slang phrases were more frequently classified as toxic than traditional toxic English slang phrases. This outcome, in relation to the dataset, suggests that the Perspective model may not be less likely to identify toxic content if Gen-Z phrases are used, which opposes my hypothesis.

### Biases
As these phrases were developed organically by me, I may be biased with my vocabulary in terms of my cadence and word choice in my phrases, which may not holistically represent the wide variety of lexicons around the world. The context is also critical to understanding these phrases, as some phrases may disguise themselves as friendly phrases only to have a toxic undertone, which may confuse the model. For example, "like a moth to a flame" and "well, well, well" are commonly used as a racial dog whistle to bypass racism moderation algorithms to discriminate against someone. In the same way, these seemingly yet not innocuous phrases can avoid the toxicity algorithm. 

### Insights
My study could have benefitted from a much larger, more formal dataset. With a small dataset of around n = 20, most studies need more data to reach a worthwhile conclusion. If I were to repeat this study, I would use an existing, clean, and transformed dataset to ensure my findings holistically represent the community I am studying. 
 
### DISCLAIMER
The phrases I wrote in the Jupyter Notebook are only for testing and research purposes. The phrases do not represent my personal thoughts or ideals whatsoever, and any relevance to real-life scenarios is purely coincidental. 