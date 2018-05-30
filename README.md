# Machine Learning Basics

### Introduction

Machine Learning is the science of getting computers to learn, without being explicitly programmed. It has grown out of AI (Artificial Intelligence). Few uses of ML are database mining, applications that cannot be programmed by hand i.e. handwriting recognition, NLP, computer vision; self-customizing applications, to understand human learning. According to Tom Mitchell 
>"A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E."

### Machine Learning Algorithms
* Supervised Learning
* Unsupervised Learning  
Others: Reinforcement Learning, recommender systems

#### Supervised Learning
The machine learns from a set of data where correct output is known. When the predicted result is from continuous output i.e. input is given to a continuous function, it is called regression, and when the predicted result is from a set of discrete output, it is called classification. <br>
A training set is fed to a learning algorithm which returns a function which is called hypothesis, denoted by _h_. During prediction, input (x)(also called input feature) is fed to to h and an output (extimated value of y)(also called target) is obtained. The set (x,y) is denoted by m, called the training set.

**Linear Regression**<br>
The data set output is represented as a linear equation represented by:<br>
**h<sub>theta</sub>x = theta<sub>0</sub> + theta<sub>1</sub>x**

where theta0 and theta1 are constants and h is the hypothesis, sometimes also written as h(x).

#### Unsupervised Learning
Unsupervised learning approaches problems with little or no idea what the results should look like. Given a data set, a structure of data is to be predicted. Data points are not labeled. Here data is divided into clusters based on their nature. This is called clustering. <br>
One example is cocktail party problem algorithm. It is an example of unsupervised learning without clustering. This algorithm is about two microphones installed in two different parts of the room in a cocktail party. Both record mixture of two voices. Unsupervised learning is used to separate one voice from another. The "Cocktail Party Algorithm" is used to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).
