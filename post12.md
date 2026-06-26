---
layout: default
---

# Physics-Informed Neural Networks (PINNs)

![Physics-Informed Neural Networks (PINNs)](assets/img/post12-cover.jpg)
Physics-Informed Neural Networks adapted from [here](https://medium.com/@justygwen/unlocking-the-potential-of-physics-informed-neural-networks-pinns-68976b501415)

PINNs, or Physics-Informed Neural Networks, are a relatively new concept that was first defined under [this name](https://www.sciencedirect.com/science/article/abs/pii/S0021999118307125) in 2017 by Dr. Maziar Raissi and his team through their published papers. They also continued to work on this topic in the following years. To better understand Physics-Informed Neural Networks, as the name suggests, we should use a physical example from nature. Although I know that, as a physician, I am stepping into a frightening world, I will try to overcome my fear and explain it in a way that is understandable using the countless courses available on the internet.

Imagine that we are developing a model in which a neural network is learning the maximum height of a projectile thrown straight upward using a dataset consisting of initial velocities and the corresponding maximum heights.

![image](assets/img/post12-1.jpg)
The mathematical equation of the neural network

You may say that this problem can already be solved using the very old equations that Mr. Newton discovered 400 years ago, shown below, and that there is no need to use neural networks or artificial intelligence in general.

![image](assets/img/post12-2.jpg)
The differential equation of a projectile thrown straight upward (Y only)

However, in reality, besides gravity, other forces also affect the projectile. The simplest of these is friction. You may again say that physics has also provided us with methods to calculate friction. Yes, that is true. But even today in nature, especially when we are talking about very small and microscopic scales, phenomena occur whose general physical behavior we understand, but we are not aware of all the factors that influence them. This is exactly where Physics-Informed Neural Networks help us.

In a simple neural network model, the model makes a prediction based on the input data and assigns weights to the network (in the first attempt, it makes a completely random guess). It then compares the final result with the true value and updates the weights according to the amount of error.

![image](assets/img/post12-3.jpg)
A simple diagram of how a neural network works, adapted from [here](https://towardsdatascience.com/understanding-neural-networks-19020b758230/)

The advantage of Physics-Informed Neural Networks over conventional neural networks is that, in these networks, the correction, or as some texts call it, the penalty, is determined by two things: the amount of error between the network's prediction and the corresponding physical equations, and the amount of error between the prediction and the true value.

![image](assets/img/post12-4.jpg)
Loss calculation in Physics-Informed Neural Networks

Therefore, the model is corrected not only toward the real data but also toward the underlying physical equation. However, you may say that collecting data such as the initial velocity of a projectile and its maximum height is easy, and that with millions of pairs of initial velocities and maximum heights, a neural network without the help of physics can certainly perform excellently (and even better than the differential equation alone without considering friction). I should say that this statement is completely correct, and this is exactly what neural networks do very well. But imagine situations such as predicting the movement of a radiotracer in the human body. The amount of data obtained from nuclear imaging scans of these patients is very limited, and with such a small amount of data, training a neural network becomes very difficult. Therefore, in these situations, Physics-Informed Neural Networks help us, and we can obtain good results even with a small amount of data.

Of course, what I have explained here is a simplified explanation of how Physics-Informed Neural Networks work, but these are the basic principles. You can also easily create your own Physics-Informed Neural Network using hypothetical data with a single prompt and carefully examine its code and what it does step by step.

You can also ask your personal assistant to explain it to you according to your own profession and level of knowledge. And, to be honest, I did exactly the same thing many times while working on my own project until I finally understood it well. But the fact that your assistant explains things to you does not mean that we should stop writing. We will forever strive to prove ourselves superior to our own creations.

[Ref1](https://arxiv.org/abs/1711.10561)
[Ref2](https://www.youtube.com/watch?v=-zrY7P2dVC4)

[back](./)
