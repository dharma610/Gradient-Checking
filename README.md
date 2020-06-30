# Gradient-Checking

Here is a useful method to check whether your **backprpagation is applied correctly**, you can compare each derivatives calculated from backpropgataion with one calculated by numerical approximation method to find specific error which then helps you to debug error easily. Once you debug error then switch off gradient checking as its computationally costly so you should not run it on every iteration of gradient descent 
