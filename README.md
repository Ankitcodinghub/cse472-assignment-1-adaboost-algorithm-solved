# cse472-assignment-1-adaboost-algorithm-solved
**TO GET THIS SOLUTION VISIT:** [CSE472 Assignment 1-AdaBoost algorithm Solved](https://www.ankitcodinghub.com/product/cse472-assignment-1-adaboost-algorithm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96553&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE472&nbsp;Assignment 1-AdaBoost algorithm Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
CSE472&nbsp;Assignment 1: Ensemble Learning

In ensemble learning, we combine decisions from multiple weak learners to solve a classification problem. It is expected that the combined decision will perform better than the individual models in the process of one model correcting the errors of the other. There are many ensemble methods such as stacking, bagging and boosting. In this assignment you will implement the <strong>AdaBoost</strong> algorithm. The necessary details are as follows.

<ol>
<li>As the weak/base learner use decision stump. A decision stump is a decision tree of depth one (i.e., it branches on only one attribute and then makes decision).</li>
<li>There are several implementations of AdaBoost algorithm. Follow the pseudocode given in the class.</li>
<li>You should make your code as modular as possible. Namely, your main module of Ada-Boosting should treat the base learner as a blackbox (in this case a decision stump) and communicate with it via a generic interface that inputs weighted examples and outputs a classifier, which then can classify any instances.</li>
<li>To incorporate effect of weighted dataset, create <em>training</em> data by sampling with replacement strategy. Use information-gain as the evaluation criterion.</li>
<li>For each stump check if the total weighted error is less than .5 to proceed to next step.</li>
<li>Use original data as <em>test</em> set and update weight vector for <em>test</em></li>
<li>To train and test your model, use the file bank-additional-full.csv from the following link <a href="https://archive.ics.uci.edu/ml/datasets/Bank+Marketing">https://archive.ics.uci.edu/ml/datasets/Bank+Marketing</a>. The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict whether the client will subscribe a term deposit (variable y) or not.</li>
<li>Analyze the expected performance of your model using k-fold cross validation for k=5, 10 and 20. Use <a href="https://en.wikipedia.org/wiki/F1_score">F1 score</a> as your evaluation metric.</li>
</ol>
&nbsp;

<strong>Instructions for Report Writing</strong>

&nbsp;

<ol>
<li>Your final report will contain the following points:</li>
</ol>
<ol>
<li style="list-style-type: none;">
<ol>
<li>Expected accuracies obtained using k-fold cross validation for k=5, 10 and 20.</li>
<li>Compare the accuracies obtained by decision stump and boosting with 30 rounds.</li>
</ol>
</li>
</ol>
<ol>
<li>Compare the accuracies obtained by boosting with 5, 10 and 20 rounds.</li>
</ol>
<ol start="2">
<li>Just answer the questions precisely. Make it as simple as possible.</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

<strong>Special Instructions</strong>

<ul>
<li>Don’t Copy anything! If you do copy from internet or from any other person or from any other source, you will be severely punished and it is obvious. More than that, we expect Fairness and honesty from you. Don’t disappoint us!</li>
<li>The report should be in *.pdf (No hardcopy is required). Write in your own language.</li>
<li>You are encouraged to bring your computer in the sessional to avoid any hassle. But in that case, ensure an internet connection as you have to instantly download your code from the moodle and show it.</li>
</ul>
