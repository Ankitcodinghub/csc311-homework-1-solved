# csc311-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [CSC311 Homework 1 Solved](https://www.ankitcodinghub.com/product/csc311-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91524&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC311 Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1.&nbsp; Nearest Neighbours and the Curse of Dimensionality. In this question, you will verify the claim from lecture that “most” points in a high-dimensional space are far away from each other, and also approximately the same distance. There is a very neat proof of this fact which uses the properties of expectation and variance. If it’s been a long time since you’ve studied these, you may wish to review the Tutorial 1 slides3, or the Metacademy resources4.

(a)&nbsp; For each choice of dimension d ∈ [20, 21, 22, …, 210], sample 100 points from the unit cube, and record the average squared Euclidean distance between all pairs of points, as well as the standard deviation of the squared Euclidean distances. (Recall that squared Euclidean distance is defined as ∥x − y∥2 = 􏰂j(xj − yj)2.) Plot both the average and the standard deviation as a function of d. (You may wish to use np.mean and np.std to compute the statistics, and matplotlib for plotting. You may find numpy.random.rand helpful in sampling from the unit cube.) Include the output figure in your solution PDF (hw1_writeup.pdf).

(b)&nbsp; In this question, we aim to verify our simulations in (a) by deriving the analytical

form of averaged distance and variance of distance. Suppose we sample two points X

and Y independently from a unit cube in d dimensions and define the squared Euclidean

distance R = Z1+···+Zd with Zi = (Xi−Yi)2. Given that E[Zi] = 1 and Var[Zi] = 7 , 6 180

determine E[R] and Var[R] using the properties of expectation and variance. You may give your answer in terms of the dimension d.

Basic rule of expectation and variance: E[Zi +Zj] = E[Zi]+E[Zj] and if we further know Zi and Zj are independent, then Var[Zi + Zj] = Var[Zi] + Var[Zj].

1https://markus.teach.cs.toronto.edu/csc311-2021-09

2 http://www.cs.toronto.edu/~rgrosse/courses/csc311_f21/syllabus.pdf

3 https://www.cs.toronto.edu/~rgrosse/courses/csc311_f21/tutorials/tut01.pdf 4 https://metacademy.org/graphs/concepts/expectation_and_variance

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
(c) [Optional, 0pts] In probability theory, one can derive that P(|Z − E[Z]| ≥ a) ≤ Var[Z] a2

for any random variable Z. (This fact is known as Markov’s Inequality.) Based on your answer to part (b), explain why does this support the claim that in high dimensions, “most points are far away, and approximately the same distance”?

2. Decision Trees. This question is taken from a project by Lisa Zhang and Michael Guerzhoy.

In this question, you will use the scikit-learn decision tree classifier to classify real vs. fake news headlines. The aim of this question is for you to read the scikit-learn API and get comfortable with training/validation splits.

We will use a dataset of 1298 “fake news” headlines (which mostly include headlines of articles classified as biased, etc.) and 1968 “real” news headlines, where the “fake news” headlines are from https://www.kaggle.com/mrisdal/fake-news/data and “real news” headlines are from https://www.kaggle.com/therohk/million-headlines. The data were cleaned by removing words from fake news titles that are not a part of the headline, removing special characters from the headlines, and restricting real news headlines to those after October 2016 containing the word “trump”. For your interest, the cleaning script is available as clean_script.py on the course web page, but you do not need to run it. The cleaned-up data are available as clean_real.txt and clean_fake.txt on the course web page.

Each headline appears as a single line in the data file. Words in the headline are separated by spaces, so just use str.split() in Python to split the headlines into words.

You will build a decision tree to classify real vs. fake news headlines. Instead of coding the decision trees yourself, you will do what we normally do in practice — use an existing implementation. You should use the DecisionTreeClassifier included in sklearn. Note that figuring out how to use this implementation is a part of the assignment.

Here’s a link to the documentation of sklearn.tree.DecisionTreeClassifier: http:// scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier. html

All code should be included in the file hw1_code.py which you submit through MarkUs.

<ol>
<li>(a) &nbsp;[2pt] Write a function load_data which loads the data, preprocesses it using a vectorizer (http://scikit-learn.org/stable/modules/classes.html#module-sklearn.feature_ extraction.text), and splits the entire dataset randomly into 70% training, 15% vali- dation, and 15% test examples.</li>
<li>(b) &nbsp;[2pt] Write a function select_model which trains the decision tree classifier using at least 5 different values of max_depth, as well as two different split criteria (in- formation gain and Gini coefficient), evaluates the performance of each one on the validation set, and prints the resulting accuracies of each model. You should use DecisionTreeClassifier, but you should write the validation code yourself. Include the output of this function in your solution PDF (hw1_writeup.pdf).</li>
<li>(c) &nbsp;[1pt] Now let’s stick with the hyperparameters which achieved the highest validation accuracy. Extract and visualize the first two layers of the tree. Your visualization may look something like what is shown below, but it does not have to be an image: it is perfectly fine to display text. It may be hand-drawn. Include your visualization in your solution PDF (hw1_writeup.pdf).</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CSC311 Fall 2021 Homework 1

</div>
</div>
<div class="layoutArea">
<div class="column">
(d) [3pts] Write a function compute_information_gain which computes the information gain of a split on the training data. That is, compute I(Y,xi), where Y is the random variable signifying whether the headline is real or fake, and xi is the keyword chosen for the split.

Report the outputs of this function for the topmost split from the previous part, and for several other keywords.

3. [8pts] Regularized Linear Regression. For this problem, we will use the linear regression model from the lecture:

D

y = 􏰃 wj xj + b.

j=1

In lecture, we saw that regression models with too much capacity can overfit the training data and fail to generalize. We also saw that one way to improve generalization is regularization: adding a term to the cost function which favors some explanations over others. For instance, we might prefer that weights not grow too large in magnitude. We can encourage them to stay small by adding a penalty:

j=1

penalties in each dimension. The formulation would be: 1􏰃N􏰆 􏰇21􏰃D

Jβ (w)= y(i)−t(i) + reg2N 2jj

i=1 j=1

</div>
</div>
<div class="layoutArea">
<div class="column">
λ λ􏰃D

</div>
</div>
<div class="layoutArea">
<div class="column">
R ( w ) = 2 w ⊤ w = 2

to the cost function, for some λ &gt; 0. It is also possible to apply different regularization

</div>
</div>
<div class="layoutArea">
<div class="column">
w j2

</div>
</div>
<div class="layoutArea">
<div class="column">
βw2,

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰊 􏰉􏰈 􏰋

=J

</div>
<div class="column">
􏰊 􏰉􏰈 􏰋

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
=R

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
CSC311 Fall 2021 Homework 1

</div>
</div>
<div class="layoutArea">
<div class="column">
where i indexes the data points, βj ≥ 0 for all j, and J is the same squared error cost function from lecture. Note that in this formulation, there is no regularization penalty on the bias parameter. Also note that when βj = 0, you don’t apply any regularization on j-th dimension. For this question, show your work in detail as most points are allocated in showing how you obtained your answer.

(a) [3pts] Determine the gradient descent update rules for the regularized cost function J β . Your answer should have the form:

wj ←··· b←···

</div>
</div>
<div class="layoutArea">
<div class="column">
reg

</div>
</div>
<div class="layoutArea">
<div class="column">
This form of regularization is sometimes called “weight decay”. Based on this update rule, why do you suppose that is?

(b) [3pts] It’s also possible to solve the regularized regression problem directly by setting the partial derivatives equal to zero. In this part, for simplicity, we will drop the bias term from the model, so our model is:

D

y = 􏰃 wj xj .

j=1

It is possible to derive a system of linear equations of the following form for J β :

</div>
</div>
<div class="layoutArea">
<div class="column">
reg

(c) [2pts] Based on your answer to part (b), determine formulas for A and c, and derive a closed-form solution for the parameter w. Note that, as usual, the inputs are organized into a design matrix X with one row per training example.

</div>
</div>
<div class="layoutArea">
<div class="column">
∂Jβ D

reg =􏰃Ajj′wj′ −cj =0.

</div>
</div>
<div class="layoutArea">
<div class="column">
∂wj j′=1 Determine formulas for Ajj′ and cj.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
