# Bayesian Optimization
 This is an Exploratory work on Bayesian Optimization

 I found that the Bayesian Optimization works best when you have a function to
 minimize but you don't actually know the function or evaluating the function
 is expensive. In my notebook, I used it to find the optimal hyperparameters for
 a Random Tree Classifier. The Bayesian Optimization process works well and fast.
 It found the optimal tree number and max depth in 30 loops while taking into
 account the interaction between these two hyperparameters.

 I actually had a misunderstanding of this method before. I thought that this is
 supposed to tell us whether a treatment is effective by giving us a probability.
 But instead, I think it would actually make more sense to use some other model
 to tell the probability and use Bayesian Optimization to tune the hyperparameters
 of the model.

 At least this is what I am thinking based on what I have seen online. Maybe
 there are some other ways to apply this method, but we probably need to talk
 about it with some statisticians to further make sure how are we going use it.
 For now I will just leave it like this.
