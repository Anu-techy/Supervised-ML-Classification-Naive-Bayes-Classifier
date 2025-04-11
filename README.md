# Supervised-ML-Classification-Naive-Bayes-Classifier

Used mainly in text classifying


**Conditional probability**

P(A|B) is probability of event A knowing that event B has already occured


**1. What is the probability of getting a queen in cards**

**Soln:** There are 4 queens out of 52 cards. 

Hence p(queen) = 4/52 = 1/13


**2. What is the probability of getting a diamond in cards**

**Soln:** There are 13 diamonds out of 52 cards.

Hence p(diamond) = 13/52 = 1/4


**3. You pick a random card, its a diamond. now What is the probability of that card being a queen?**

**Soln:** Total diamonds = 13, Queen = 1

Hence p(queen|diamond) = 1/13              

This is a Conditional Probability 


**4. You pick a card, it is a queen, What is the probability of that card being diamond?**

**Soln1:** There are 4 queens, out off which diamond queen is 1

Hence p(diamond|queen) = 1/4

This is a Conditional Probability 


**Soln2:** Using Bayes' Theorem

    p(diamond|queen) = [ p(queen|diamond) * p(diamond) ] / p(queen) 

                     = [ 1/13 * 1/4 ] / 1/13

                     = 13/52

                     = 1/4






