# comp9417-homework-1--linear-regression-friends-solved
**TO GET THIS SOLUTION VISIT:** [COMP9417 Homework 1- Linear Regression & Friends Solved](https://www.ankitcodinghub.com/product/comp9417-machine-learning-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121353&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9417 Homework 1- Linear Regression \u0026amp; Friends Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
Homework 1: Linear Regression &amp; Friends

Introduction In this homework, we will explore Linear Regression and its regularized counterparts, LASSO and Ridge Regression, in more depth.

• Question 2 a): 1 mark

• Question 2 b): 1 mark

• Question 2 g): 1 mark

What to Submit

• A single PDF file which contains solutions to each question. For each question, provide your solution in the form of text and requested plots. For some questions you will be requested to provide screen shots of code used to generate your answer — only include these when they are explicitly asked for.

• .py file(s) containing all code you used for the project, which should be provided in a separate .zip file. This code must match the code provided in the report.

1

• You cannot submit a Jupyter notebook; this will receive a mark of zero. This does not stop you from developing your code in a notebook and then copying it into a .py file though, or using a tool such as nbconvert or similar.

• We will set up a Moodle forum for questions on this homework. Please read the existing questions before posting new questions. Please do some basic research online before posting questions. Please only post clarification questions. Any questions deemed to be fishing for answers will be ignored and/or deleted.

• Please check the Moodle forum for updates to this spec. It is your responsibility to check for announcements about the spec.

• Please complete your homework on your own, do not discuss your solution with other people in the course. General discussion of the problems is fine, but you must write out your own solution and acknowledge if you discussed any of the problems in your submission (including their name and zID).

When and Where to Submit

• Submission must be done through Moodle, no exceptions.

Question 1. Simple Linear Regression

(a) Consider a data set consisting of X values (features) X1,…,Xn and Y values (responses) Y1,…,Yn.

Let βˆ0,βˆ1,σˆ be the output of running ordinary least squares (OLS) regression on the data. Now define the transformation:

,

for each i = 1,…,n, where c 6= 0 and d are arbitrary real constants. Let β

e0,βe1,σe be the output of

OLS on the data Xe1,…,Xen and Y1,…,Yn. Write equations for in terms of βˆ0,βˆ1,σˆ (and in terms of c,d), and be sure to justify your answers. Note that the estimate of error in OLS is taken to be:

,

where eˆis the vector of residuals, i.e. with i-the element eˆi = Yi−Yˆi, where Yˆi is the i-th prediction made by the model, and p is the number of features (so in this case p = 2).

(b) Suppose you have a dataset where X takes only two values while Y can take arbitrary real values. To consider a concrete example, consider a clinical trial where Xi = 1 indicates that the i-th patient receives a dose of a particular drug (the treatment), and Xi = 0 indicates that they did not, and

Yi is the real-valued outcome for the i-th patient, e.g. blood pressure. Let Y T and Y P indicate the sample mean outcomes for the treatment group and non-treatment (placebo) group, respectively.

What will be the value of the OLS coefficients βˆ0,βˆ1 in terms of the group means?

What to submit: For both parts of the question, present your solution neatly – photos of handwritten work or using a tablet to write the answers is fine. Please include all working and circle your final answers.

Question 2. LASSO vs. Ridge Regression

In this problem we will consider the dataset provided in data.csv, with response variable Y , and features X1,…,X8.

(a) Use a pairs plot to study the correlations between the features. In 3-4 sentences, describe what you see and how this might affect a linear regression model. What to submit: a single plot, some commentary.

(b) In order for LASSO and Ridge to be run properly, we often rescale the features in the dataset. First, rescale each feature so that it has zero mean, and then rescale it so that where n denotes the total number of observations. What to submit: print out the sum of squared observations of each of the 8 (transformed) features, i.e. Pi Xij2 for j = 1,…,8

(c) Now we will apply ridge regression to this dataset, recall that ridge regression is defined as the solution to the optimisation:

βˆ = argmin .

Run ridge regression with λ = {0.01,0.1,0.5,1,1.5,2,5,10,20,30,50,100,200,300}. Create a plot with x-axis representing log(λ), and y-axis representing the value of the coefficient for each feature in each of the fitted ridge models. In other words, the plot should describe what happens to each of the coefficients in your model for the different choices of λ. For this problem you are permitted to use the sklearn implementation of Ridge regressiom to run the models and extract the coefficients, and base matplotlib/numpy to create the plots but no other packages are to be used to generate this plot. In a few lines, comment on what you see, in particular what do you observe for features 3,4,5?

What to submit: a single plot, some commentary, a screen shot of the code used for this section. Your plot must have a legend, and you must use the following colors: [’red’, ’brown’, ’green’, ’blue’, ’orange’, ’pink’, ’purple’, ’grey’] for the features X1,..,X8 in the plot.

(d) In this part, we will use Leave-One-Out Cross Validation (LOOCV) to find a good value of λ for the ridge problem. Create a fine grid of λ values running from 0 to 50 in increments of 0.1, so the grid would be: 0,0.1,0.2,…,50. For each data point i = 1,…,n, run ridge with each λ value on the dataset with point i removed, find βˆ, then get the leave-one-out error for predicting Yi. Average the squared error over all n choics of i. Plot the leave-one-out error against λ and find the best λ value. Compare your results to standard Ordinary Least Squares (OLS), does the ridge seem to give better prediction error based on your analysis? Note that for this question you are not permitted to use any existing packages that implement cross validation, you must write the code yourself from scratch. You must create the plot yourself from scratch using basic matplotlib functionality.

What to submit: a single plot, some commentary, a screen shot of any code used for this section.

(e) Recall the LASSO problem:

βˆ = argmin .

Repeat part (c) for the LASSO. What to submit: a single plot, some commentary, a screen shot of the code used for this section. You must use the same color scheme as in part (c).

(f) Repeat the leave-one-out analysis of part (d) for the LASSO and for a grid of λ values 0,0.1,…,20. Note that sklearn will throw some warnings for the λ = 0 case which can be safely ignored for our purposes. What to submit: a single plot, some commentary, a screen shot of the code used for this section.

Question 3. Sparse Solutions with LASSO

In this question, we will try to understand why LASSO regression yields sparse solutions. Sparse means that the solution of the LASSO optimisation problem:

βˆ = argmin

(a) Consider the quantity |hY,Xβi|. Show that , where Xj denotes the j-th column of X.

(b) We will now assume that λ is very large, such that it satisfies:

λ ≥ max|XTY |.

j

Using the result of part (a), and the assumption on λ, prove that βˆ = 0p is a solution of the LASSO problem.

(c) In the previous part, we showed that βˆ = 0p is a minimizer of `(β). Prove that βˆ is the unique minimizer of `(β), i.e. if β 6= 0p, then `(β) &gt; `(0p). hint: consider the two cases: kXβk2 = 0 and kXβk2 &gt; 0

What to submit: For all parts of the question, present your solution neatly – photos of handwritten work or using a tablet to write the answers is fine. Please include all working and circle your final answers. Note that if you cannot do part (a), you are still free to use the result of part (a) to complete parts (b) and (c).
