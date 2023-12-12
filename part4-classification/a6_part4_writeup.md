# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
The models accuracy score decreases significantly because of all the predicted y values are now 0. 

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
Its much more accurate because the values are scaled compared to when they are not. when they are not scaled the accuracy score can drop into 0.50's while with the standardscaler it can reach high 0.80's. Given the case, I think it would be more accurate for this given case?

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The model was prett accurate, but it did a few times did not predict a purchase that did happen or the opposite of this but the it wasn't 100% accurate to begin with. 

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
no

