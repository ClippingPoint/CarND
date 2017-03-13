# CarND

# Deep learning


## Architecture


### Activation Functions

INPUT layer?

Hidden layers?

OUTPUT layer?

[Softmax vs Sigmoid function in logistic classifier](http://stats.stackexchange.com/questions/233658/softmax-vs-sigmoid-function-in-logistic-classifier)

Sigmoid_function is used for the two-class logistic regression, whereas the softmax_function is used for the multi-class logistic regression

ReLU and vanishing gradient problems

[How does rectilinear activation function soluve the vanishing gradient problems](http://stats.stackexchange.com/questions/176794/how-does-rectilinear-activation-function-solve-the-vanishing-gradient-problem-in)

Interesting point/concept:

"LeakyReLU" 

Note that it's important to have an initialization that corresponds to the type of your activation function. LeakyReLUs need other init that plain ReLUs,for example

Also, mind that ReLU isn't all that "obviously better" than for example, TanH, TanH can probably be better in some cases. Just, so it seems, not in visual recognition.

ELU, for example, has a bit of sigmoid softness to it and one of the best known activation function for visual regonition at the moment. 

Evaluation of popular activation functions
[Systematic evaluation of CNN advances on the ImageNet](https://arxiv.org/pdf/1606.02228.pdf)

Also, in real life, "derivatives" that you pass to the backdrop don't necessarily have to match the actual mathematical derivatives

[Wiki list of activation functions](https://en.wikipedia.org/wiki/Activation_function)



