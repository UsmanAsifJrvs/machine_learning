# Machine Learning
# History
In 1642, one of the first mechanical adding machine was designed by **Blaise Pascal**. It used a system of gears and wheels similar to those found in odometers and other counting devices. Pascal's adder also known as **Pascaline**, could both add and subtract and was invented to calculate taxes.

In 1694 **Gottfried Wilhelm Von Lebniez** produced a similar machine to that of **Pascaline**, that was more accurate and could perform all four arithematic functions. Lebneiz also created **binary system** used by all modern computers. 

**Storing data** was the next challenge to be met. In 1801 the first use of storing data was in a weaving loom invented by **Joseph Marie Jacquard** that used metal cards punched with holes to position threads. A collection of these cards coded a program that directed the loom. This allowed for a process to be repeated with a consistent result every time.

In 1847, **George Boole** created a way of representing this using **Boolean operators (AND, OR, NOR)** and having responses represented by true or false, yes or no, and represented in binary as 1 or 0. Web searches still use these operators today.

In **1890 Herman Hollerith** created the first combined system of mechanical calculation and punch cards to rapidly calculate statistics gathered from millions of people.

In 1945 **Mark I** built at **IBM** and designed by **Howard Aiken**, was the first combined electric and mechanical computer. The **Mark I** could **store 72 numbers** and it could perform complex multiplication in 6 seconds and division in 16.

In 1946 the first **fully electronic computer** was built by **John Mauchly** and **John Eckert** and named **ENIAC**, short for *Electronic Numerical Integrator and Computer*.

In 1952 **Arthur Samuel** was an **IBM** scientist who used the game of **checkers** to create the **first learning program**. His program became a better player after many games against itself and a variety of human players in a **'supervised learning mode'**. The program observed which moves were winning strategies and adapted its programming to incorporate those strategies. 

In 1957 **Frank Rosenblatt** designed the perceptron which is a type of *neural network*. A neural network acts like your brain; the brain contains billions of cells called neurons that are connected together in a network. The perceptron connects a web of points where simple decisions are made that come together in the larger program to solve more complex problems.
In 1967 the first **pattern regonition program** were designed based on a type of algorithm called the *nearest neighbour*. An algorithm is a sequence of instructions and steps. When the program is given a new object it compares this with data from the training set and classifies the object to the *nearest neighbour*, or most similar object in memory.

In 1981 **Gerald Dejong** introduced *explanation based learning*, prior knowledge of the world is provided by training examples which makes this a type of supervised learning. The program analyzes the training data and discards irrelevant information to form a general rule to follow. For example in chess if the program is told that it needs to focus on the queen, it will discard all piesces that don't have immediate effect upon her.

In 1990's Machine learning applications in *data mining, adaptive software and web applications, text learning , and language learning* were started. Advances continued in machine learning algorithms within the general areas of supervised learning and unsupervised learning. As well, reinforcement learning algorithms were developed.

In 2000's the new millenium brought an explosion of *adaptive programming*. Anywhere adaptive programs are needed, machine learning  is there. These programs are capable of recognizihng patterns, learning from experience, abstracting new information from data, and optimizing the efficiency and accuracy of its processing and output.

## Time Line of MACHINE LEARNING History 

![Sample diagram](assets/history_of_ml.SVG)


# Machine Learning: 

### Definition

Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it to learn for themselves.
"Machine learning is defined as field of study that gives computers the ability to learn without being explicitly programmed"- Arthur Samauel
“Machine Learning at its most basic is the practice of using algorithms to parse data, learn from it, and then make a determination or prediction about something in the world.” – Nvidia 
“Machine learning is the science of getting computers to act without being explicitly programmed.” – Stanford
“Machine learning is based on algorithms that can learn from data without relying on rules-based programming.”- McKinsey & Co.
“Machine learning algorithms can figure out how to perform important tasks by generalizing from examples.” – University of Washington
“The field of Machine Learning seeks to answer the question “How can we build computer systems that automatically improve with experience, and what are the fundamental laws that govern all learning processes?” – Carnegie Mellon University

## Types of Machine Learning
![Sample Diagram](assets/ML_DIAGRAM1.SVG)

### Supervised machine learning 

These algorithms can apply what has been learned in the past to new data using labeled examples to predict future events. Starting from the analysis of a known training dataset, the learning algorithm produces an inferred function to make predictions about the output values. The system is able to provide targets for any new input after sufficient training. The learning algorithm can also compare its output with the correct, intended output and find errors in order to modify the model accordingly.


![Sample Diagram](assets/ML_DIAGRAM2.SVG)


### Unsupervised machine learning 

These algorithms are used when the information used to train is neither classified nor labeled. Unsupervised learning studies how systems can infer a function to describe a hidden structure from unlabeled data. The system doesn’t figure out the right output, but it explores the data and can draw inferences from datasets to describe hidden structures from unlabeled data.
![Sample Diagram](assets/ML_DIAGRAM3.SVG)

### Reinforcement machine learning 

These algorithms are learning methods that interacts with its environment by producing actions and discovers errors or rewards. Trial and error search and delayed reward are the most relevant characteristics of reinforcement learning. This method allows machines and software agents to automatically determine the ideal behavior within a specific context in order to maximize its performance. Simple reward feedback is required for the agent to learn which action is best; this is known as the reinforcement signal.

![Sample Diaggram](assets/ML_DIAGRAM4.SVG)

## Other Machine learning Algorithms

 ### Nearest Neighbour Classification

Nearest Neighbors is one of the most basic yet essential classification algorithms in Machine Learning. It belongs to the supervised learning domain and finds intense application in *pattern recognition, data mining and intrusion detection*.

It is widely disposable in real-life scenarios since it is non-parametric, meaning, it does not make any underlying assumptions about the distribution of data (as opposed to other algorithms such as GMM, which assume a Gaussian distribution of the given data).

# Linear Regression
Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an explanatory variable, and the other is considered to be a dependent variable. For example, a modeler might want to relate the weights of individuals to their heights using a linear regression model.

Before attempting to fit a linear model to observed data, a modeler should first determine whether or not there is a relationship between the variables of interest. This does not necessarily imply that one variable causes the other (for example, higher SAT scores do not cause higher college grades), but that there is some significant association between the two variables. 

A scatterplot can be a helpful tool in determining the strength of the relationship between two variables. If there appears to be no association between the proposed explanatory and dependent variables (i.e., the scatterplot does not indicate any increasing or decreasing trends), then fitting a linear regression model to the data probably will not provide a useful model. A valuable numerical measure of association between two variables is the correlation coefficient, which is a value between -1 and 1 indicating the strength of the association of the observed data for the two variables.

A linear regression line has an equation of the form Y = a + bX, where X is the explanatory variable and Y is the dependent variable. The slope of the line is b, and a is the intercept (the value of y when x = 0).

## Least-Squares Regression
Linear least squares (LLS) is the least squares approximation of linear functions to data. It is a set of formulations for solving statistical problems involved in linear regression, including variants for ordinary (unweighted), weighted, and generalized (correlated) residuals. 

Numerical methods for linear least squares include inverting the matrix of the normal equations and orthogonal decomposition methods.

### Explanation
In statistics and mathematics, linear least squares is an approach to fitting a mathematical or statistical model to data in cases where the idealized value provided by the model for any data point is expressed linearly in terms of the unknown parameters of the model. The resulting fitted model can be used to summarize the data, to predict unobserved values from the same system, and to understand the mechanisms that may underlie the system.

Mathematically, linear least squares is the problem of approximately solving an overdetermined system of linear equations A x = b, where b is not an element of the column space of the matrix A. The approximate solution is realized as an exact solution to A x = b', where b' is the projection of b onto the column space of A. 

The best approximation is then that which minimizes the sum of squared differences between the data values and their corresponding modeled values. The approach is called linear least squares since the assumed function is linear in the parameters to be estimated. Linear least squares problems are convex and have a closed-form solution that is unique, provided that the number of data points used for fitting equals or exceeds the number of unknown parameters, except in special degenerate situations. In contrast, non-linear least squares problems generally must be solved by an iterative procedure, and the problems can be non-convex with multiple optima for the objective function. If prior distributions are available, then even an underdetermined system can be solved using the Bayesian MMSE estimator.

In statistics, linear least squares problems correspond to a particularly important type of statistical model called linear regression which arises as a particular form of regression analysis. One basic form of such a model is an ordinary least squares model. The present article concentrates on the mathematical aspects of linear least squares problems, with discussion of the formulation and interpretation of statistical regression models and statistical inferences related to these being dealt with in the articles just mentioned. See outline of regression analysis for an outline of the topic.

# What is Artificial Intelligence (AI)?

Artificial intelligence (AI) refers to the simulation of human intelligence in machines that are programmed to think like humans and mimic their actions. The term may also be applied to any machine that exhibits traits associated with a human mind such as learning and problem-solving.

The ideal characteristic of artificial intelligence is its ability to rationalize and take actions that have the best chance of achieving a specific goal.

When most people hear the term artificial intelligence, the first thing they usually think of is robots. That's because big-budget films and novels weave stories about human-like machines that wreak havoc on Earth. But nothing could be further from the truth.

Artificial intelligence is based on the principle that human intelligence can be defined in a way that a machine can easily mimic it and execute tasks, from the most simple to those that are even more complex. The goals of artificial intelligence include learning, reasoning, and perception.

As technology advances, previous benchmarks that defined artificial intelligence become outdated. For example, machines that calculate basic functions or recognize text through optimal character recognition are no longer considered to embody artificial intelligence, since this function is now taken for granted as an inherent computer function.

AI is continuously evolving to benefit many different industries. Machines are wired using a cross-disciplinary approach based in mathematics, computer science, linguistics, psychology, and more.

**AI will have a huge impact on all industries**

13 trillion dollars business of AI in all industries by 2019 as shown below



## Applications of Artificial Intelligence
The applications for artificial intelligence are endless. The technology can be applied to many different sectors and industries. AI is being tested and used in the healthcare industry for dosing drugs and different treatment in patients, and for surgical procedures in the operating room.

Other examples of machines with artificial intelligence include computers that play chess and self-driving cars. Each of these machines must weigh the consequences of any action they take, as each action will impact the end result. In chess, the end result is winning the game. For self-driving cars, the computer system must account for all external data and compute it to act in a way that prevents a collision.

Artificial intelligence also has applications in the financial industry, where it is used to detect and flag activity in banking and finance such as unusual debit card usage and large account deposits—all of which help a bank's fraud department. Applications for AI are also being used to help streamline and make trading easier. This is done by making supply, demand, and pricing of securities easier to estimate.

## Types of Artificial Intelligence
### Artificial Narrow Intelligence (ANI) or Weak AI
It is a type of intelligence in which we make any model, robot or machine which can perform single task only.

o	Narrow AI is a type of AI which is able to perform a dedicated task with intelligence.The most common and currently available AI is Narrow AI in the world of Artificial Intelligence.

o	Narrow AI cannot perform beyond its field or limitations, as it is only trained for one specific task. Hence it is also termed as weak AI. Narrow AI can fail in unpredictable ways if it goes beyond its limits.

o	Apple Siriis a good example of Narrow AI, but it operates with a limited pre-defined range of functions.

o	IBM's Watson supercomputer also comes under Narrow AI, as it uses an Expert system approach combined with Machine learning and natural language processing.

o	Some Examples of Narrow AI are playing chess, purchasing suggestions on e-commerce site, self-driving cars, speech recognition, and image recognition.

o	Lots of progress has been done in ANI

### Artificial General Intelligence
It is a type of intelligence in which a single model can perform multiple tasks. It can see, hear, speak like our brain is a model of AGI. A single model can have all the functionalities.

o	General AI is a type of intelligence which could perform any intellectual task with efficiency like a human.

o	The idea behind the general AI to make such a system which could be smarter and think like a human by its own.

o	Currently, there is no such system exist which could come under general AI and can perform any task as perfect as a human.

o	The worldwide researchers are now focused on developing machines with General AI.

o	As systems with general AI are still under research and it will take lots of efforts and time to develop such systems.

o	Achieving AGI will take time. AGI is exciting goal for researchers to work on but it requires many breakthroughs before we get there and it may be decades or hundreds of years away.

o	It can do anything like a human or even maybe super intelligent than human  can do.

o	Almost no progress till now.

# Current Uses of AI:

Although artificial intelligence evokes thoughts of science fiction, artificial intelligence already has many uses today, for example:

## Email filtering:
 Email services use artificial intelligence to filter incoming emails. Users can train their spam filters by marking emails as “spam”.
## Personalization: 
Online services use artificial intelligence to personalize your experience. Services, like Amazon or Netflix, “learn” from your previous purchases and the purchases of other users in order to recommend relevant content for you.
## Fraud detection:
 Banks use artificial intelligence to determine if there is strange activity on your account. Unexpected activity, such as foreign transactions, could be flagged by the algorithm.
## Speech recognition: 
Applications use artificial intelligence to optimize speech recognition functions. Examples include intelligent personal assistants, e.g. Amazon’s “Alexa” or Apple’s “Siri”.


# What is Data in machine learning?
The goal of data acquisition is to find datasets that can be
used to train machine learning models. There are largely
three approaches in the literature: data discovery, data augmentation, and data generation. Data discovery is necessary
when one wants to share or search for new datasets and
has become important as more datasets are available on the
Web and corporate data lakes. Data augmentation
complements data discovery where existing datasets are
enhanced by adding more external data. Data generation
can be used when there is no available external dataset,
but it is possible to generate crowdsourced or synthetic
datasets instead. 

As machine learning becomes more widely used, it becomes
more important to acquire large amounts of data and label
data, especially for state-of-the-art neural networks. Traditionally, the machine learning, natural language processing,
and computer vision communities has contributed to this
problem – primarily on data labeling techniques including
semi-supervised learning and active learning. Recently, in
the era of Big data, the data management community is also
contributing to numerous subproblems in data acquisition,
data labeling, and improvement of existing data. In this
survey, we have investigated the research landscape of how
all these technique complement each other and have provided guidelines on deciding which technique can be used
when. Finally, we have discussed interesting data collection
challenges that remain to be addressed. In the future, we
expect the integration of Big data and AI to happen not only
in data collection, but in all aspects of machine learning.

# Data Science VS Machine Learning

![Sample Diagram](Reference/AI_1.SVG)

## Data Science
We all know that every single tech company out there is collecting huge amounts of data. And data is revenue. Why is that? That’s because of data science. The more data you have, the more business insights you can generate. Using data science, you can uncover patterns in data that you didn’t even know existed. 

Companies are using data science to build recommendation engines, and predicting user behaviour, and much more. All of this is only possible when you have enough amount of data so that various algorithms could be applied on that data to give you more accurate results.

There is also something called as prescriptive analytics in data science, which does pretty much the same predictions that we talked about in the rich tourist example above. But as an added benefit, prescriptive analytics will also tell you what kind of luxury tours to Venice a person might be interested in. For example, one person might want to fly first class but would be fine with a three star accommodation, whereas another person could be ready to fly economy but definitely needs the most luxurious stay and cultural experience. So even though both these people will be your rich clients, both of them have different requirements. So you can use prescriptive analytics for this.

You might be wondering, hey, that sounds a lot like artificial intelligence. And you’re not entirely wrong, actually. Because running these machine learning algorithms on huge datasets is again a part of data science. Machine learning is used in data science to make predictions and also to discover patterns in the data. This again sounds like we’re adding intelligence to our system. That must be artificial intelligence. 
## Artificial Intelligence
Artificial intelligence is the ability that can be imparted to computers which enables these machines to understand data, learn from the data, and make decisions based on patterns hidden in the data, or inferences that could otherwise be very difficult (to almost impossible) for humans to make manually. AI also enables machines to adjust their “knowledge” based on new inputs that were not part of the data used for training these machines.

Another way of defining AI is that it’s a collection of mathematical algorithms that make computers understand relationships between different types and pieces of data such that this knowledge of connections could be utilised to come to conclusions or make decisions that could be accurate to a very high degree.

## Machine Learning
Machine Learning (ML) is considered a sub-set of AI. ML is used in situations where we want the machine to learn from the huge amounts of data we give it, and then apply that knowledge on new pieces of data that streams into the system. 

There are different ways of making a machine learn. Different methods of machine learning are supervised learning, non-supervised learning, semi-supervised learning, and reinforced machine learning. In some of these methods, a user tells the machine what are the features or independent variables (input) and which is the dependent variable (output). So the machine learns the relationship between the independent and dependent variables present in the data that is provided to the machine. This data which is provided is called the training set. And once the learning phase or the training is complete, the machine, or the ML model, is tested on a piece of data which the model has not encountered before. This new dataset is called the test dataset. There are different ways in which you can split your existing dataset between the training and the test dataset. Once the model is mature enough to give reliable and high accuracy results, the model will be deployed to a production setup where it will be used against absolutely new datasets for problems such as predictions or classification.

## Deep Learning
Deep Learning (DL) is an advancement of ML. Even though ML is super powerful for most applications, there are situations where ML leaves a lot to be desired. That is where deep learning steps in. It is generally believed that if your training dataset is relatively small, you go with ML. But if you have huge amounts of data on which you can train a model, and if the data has too many features, and if accuracy is super important (accuracy is always important though), you take the deep learning route.

It is also important to note that deep learning requires much powerful hardware to run on (mostly GPUs are used), it takes significantly more time to train your models, and it is generally more difficult to implement compared to ML. But these are some of the compromises that you have to live with when the problem you’re trying to solve is that much more complex.

![Sample Diagram](Reference/NN_1.SVG.Draw.io)
