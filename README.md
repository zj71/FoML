# FoML
机器学习基础，一些算法，模型，评估标准
#（72/100）
还行好像
# feedback
You only describe logistic regression as your model of choice, but, in fact, have tried other models as well which you later mention in the results section (which you do not explain any further). It’s not entirely clear why opt for LR, as, e. g., the linear discriminant analysis equally achieves high accuracies as shown in the code. Throwing away data with low confidence is not a good idea – it’s better to use weights in your cost function to take them into account (but you also address this shortcoming in your discussion which is good). You do not need to describe the possible reasons for missing data. Generally, you put too much weight in describing how you dealt with missing data. You do not show how changing hyperparameters affect performances (I guess, LR models 1-6 use different parameters, but this is not disclosed). Minor point: The fonts of the figures are way too small. The discussion could have been in more detail. Overall, your report addresses most key aspects, but does so in a rather chaotic way. The code is annotated in the smaller details, but lacks comments regarding major parts (which makes it hard to read).
