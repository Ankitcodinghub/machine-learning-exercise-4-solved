# machine-learning-exercise-4-solved
**TO GET THIS SOLUTION VISIT:** [Machine Learning Exercise 4 Solved](https://www.ankitcodinghub.com/product/machine-learning-labs-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110193&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Machine Learning Exercise 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
www.epfl.ch/labs/mlo/machine-learning-cs-433

Goals. The goal of this exercise is to

• Implement 4-fold cross-validation.

• Understand the bias-variance decomposition.

Setup, data and sample code. Obtain the folder labs/ex04 of the course github repository

github.com/epfml/ML course

1 Cross-validation

This exercise is partly based on the materials from last week (labs/ex03). If you don’t have it already, please finish the ex03 first. You might directly reuse/copy some of the functions you implemented yourself during previous exercises, e.g., ridge regression(), least squares() and build poly().

Exercise 1:

Implement 4-fold cross-validation.

• Copy your code from last week, and fill in the corresponding templates, i.e., ridge regression() to ridge regression.py, build poly() to build polynomial.py, and least squares() to least squares.py.

In this exercise, please fill in the notebook functions cross validation() and cross validation demo(), and perform 4-fold cross-validation for polynomial degree 7. Plot the train and test RMSE as a function of λ. The resulting figure should look like Figure 1.

• How will you use 4-fold cross-validation to select the best model among various degrees, say from 2 to 10?

Write code to do it in best degree selection().

Figure 1: Effect of λ on training and test errors, calculated using 4-fold cross-validation

2 Visualizing the Bias-Variance Decomposition

Last lecture we introduced model selection, and we saw that the model complexity is crucial to the performance. In this problem, we will further investigate the effect of model complexity with the concept of bias-variance decomposition.

We will implement the figures seen in class representing the tradeoff and also seen in Figure 2 : for a big polynomial degree, the bias is small but the variance is large. The opposite is true for a small polynomial degree (however notice that the variance is still quite important). Choosing an intermediate degree leads to consistent predictions which are close to the true function we want to learn (optimal bias / variance tradeoff).

Exercise 2:

Visualizing the bias-variance trade-off.

• Complete the notebook function bias variance one seed(): for 15 random datapoints, it finds the optimal fit (using the least square formula, with no regularisation λ) for a polynomial expansion of degree 1, 3 and 6.

• you can play around by changing the seed, the number of datapoints, the degree of the polynomial expansion etc.

• Now complete the notebook function bias variance demo() which performs many times the previous experiment but with a new random training set each time. You should obtain something similar to Figure 2. • Comment the figures by explaining how the bias / variance tradeoff is shown in these plots.

• You can play around by changing the function you want to learn, the variance of the gaussian noise σ2, the degree of the polynomial expansion etc.

• BONUS: you can do similar figures but now you fix the degree of the polynomial expansion and add some regularisation λ. You will observe a similar bias / variance tradeoff when changing the magnitude of the regularisation.

Figure 2: Visualizing the Bias-Variance Trade-off.

2
