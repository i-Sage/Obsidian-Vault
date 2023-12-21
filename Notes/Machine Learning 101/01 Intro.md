19-12-2023 <-> 14:20
-> Type : Note
-> Tags : #Machine_Learning 

---
## What is ML
Machine Learning is a field of artificial intelligence(AI) that focuses on developing algorithms and techniques enabling computers to learn from data and make predictions or decisions without being explicitly programmed for each task.

---
### Supervised Learning
>This is the task of relating a set of input variables to a set of output variables, or in lame man terms, just a function $f(x)$ . It requires us to use data that has been labelled with a specific class or a set of classes, so maybe a type of food, specific roles of players e.t.c, so that we can figure out what attributes of the data relate to that class. The resulting formula will be an accurate way of predicting what class or label the input data belongs in based on the attributes it has.

The above paragraph can be broken down into the steps below:
1. Pick your dataset
2. Label your data
3. Model selection(develop your formula ($y = w*x$))
4. Training
5. Try your model with new data (validation)

- Pick your data: To create a model, you first have to pick what type of data you want to be looking at, this might be pictures like 3 Dimensional pictures, a set of variables or information you have about something, and so on. But most importantly, you need to know what type of data you have before you can label it.

- Label your data: Depending on what you want from your model, you many only need to give your data a single label or maybe multiple labels.

- Model Selection: Once your data is labelled, we need to develop a formula that relates these labels to the data. There are a lot of options for doing this, ranging from simple to very complex. The simpler side includes **linear** and **logistic** regression. These map either a straight liner formula or an exponential formula to your data set. Going over the simpler to the more complex side of model selection includes using computational neural networks to derive a non-linear formula that fits your data.

- Training: Training a model involves making an initial guess for the formula that relates the labels to the data, trying it and seeing how right or wrong we were on any particular set of data. From there, we adjust the formula we originally came up with, until we get to the right answer or as close as an approximation we can get to. Many models do this with a method called a *cost function* which is essentially a way to quantify how accurate you were on any given try. For any right answer you get, you don't add any thing to the cost function in most cases, and for every wrong answer you get, you do add to the cost function, so the more you are wrong, the bigger your cost function is going to be. Now there are ways to tweak your cost function, meaning to penalize your model for being wrong on certain types of data.

- Testing: Usually, when we get our data, we usually take about 20% out of it as testing data. This is because a high accuracy on training data does not necessary mean a high on actual data. It can mean that the formula generated is over tuned for the training data, it has been over fit to match exactly the relationships between the input data and the output data. In these cases, these models don't necessary perform well on data it has not actually seen before, because that data doesn't necessary fit into the category of the training data you gave it.

---

### Summary


---
### References
- [Jordan Harrod YouTube]()
- [A visual introduction to machine learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) 

---
19-12-2023 <-> 14:20