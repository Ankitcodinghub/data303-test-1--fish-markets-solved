# data303-test-1--fish-markets-solved
**TO GET THIS SOLUTION VISIT:** [DATA303 Test 1- Fish markets Solved](https://www.ankitcodinghub.com/product/data303-test-1-fish-markets-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101393&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DATA303 Test 1- Fish markets Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
DATA 303/473 Test 1: Fish markets

1 April 2021

1. Data were collected on 158 fish of some species commonly sold in fish markets. dataset are:

<ul>
<li>species: Name of fish species</li>
<li>weight: Weight of fish in grams</li>
<li>vert.len: Vertical length in cm</li>
<li>diag.len: Diagonal length in cm</li>
<li>cross.len: Cross length in cm</li>
<li>height: Height in cm</li>
<li>width: Diagonal width in cm</li>
</ul>
</div>
<div class="column">
The variables in the

</div>
</div>
<div class="layoutArea">
<div class="column">
A marine scientist is interested in developing a model that can be used to predict the weight of a fish with species, vert.len, diag.len, cross.len, height and width as potential predictors. Part of the analysis carried out is shown below. Use the results to answer the questions that follow.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>fish&lt;-read.csv("fishmarket.csv", header=T, stringsAsFactors = TRUE)
summary(fish)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##       species       weight          vert.len        diag.len
##  Bream    :35   Min.   :   5.9   Min.   : 7.50   Min.   : 8.40
##  Parkki   :11   1st Qu.: 121.2   1st Qu.:19.15   1st Qu.:21.00
##  Perch    :56   Median : 281.5   Median :25.30   Median :27.40
##  Pike     :17   Mean   : 400.8   Mean   :26.29   Mean   :28.47
##  Roach    :19   3rd Qu.: 650.0   3rd Qu.:32.70   3rd Qu.:35.75
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##  Smelt    :14   Max.   :1650.0   Max.   :59.00
##  Whitefish: 6
##    cross.len         height           width
##  Min.   : 8.80   Min.   : 1.728   Min.   :1.048
##  1st Qu.:23.20   1st Qu.: 5.941   1st Qu.:3.399
##  Median :29.70   Median : 7.789   Median :4.277
##  Mean   :31.28   Mean   : 8.987   Mean   :4.424
##  3rd Qu.:39.67   3rd Qu.:12.372   3rd Qu.:5.587
##  Max.   :68.00   Max.   :18.957   Max.   :8.142
##
</pre>
</div>
<div class="column">
Max. :63.40

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>fit1&lt;-lm(weight~species+ vert.len + diag.len + cross.len +
           height + width, data=fish)
</pre>
<pre>library(pander)
pander(summary(fit1), caption="")
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Estimate (Intercept) -912.7

speciesParkki 160.9 speciesPerch 133.6 speciesPike -209 speciesRoach 104.9 speciesSmelt 442.2

</div>
<div class="column">
Std. Error

127.5 75.96 120.6 135.5 91.46 119.7

</div>
<div class="column">
t value

-7.161 2.119 1.107 -1.543 1.147 3.695

</div>
<div class="column">
Pr(&gt;|t|)

3.638e-11 0.03582 0.27 0.1251 0.2532 0.0003108

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
speciesWhitefish vert.len diag.len cross.len height width

Observations 158

<pre>BIC(fit1)
## [1] 1937.243
</pre>
(Intercept) speciesParkki speciesPerch

</div>
<div class="column">
Estimate

91.57 -79.84 81.71 30.27 5.807 -0.7819

Residual Std. Error 93.95

Estimate

2.427 0.1541 0.1668

</div>
<div class="column">
Std. Error

96.83 36.33 45.84 29.48 13.09 23.95

R2 0.9358

Std. Error

</div>
<div class="column">
t value

0.9456 -2.198 1.783 1.027 0.4435 -0.03265

</div>
<div class="column">
Pr(&gt;|t|)

0.3459 0.02955 0.07675 0.3062 0.6581 0.974

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>fit2&lt;-lm(log(weight)~species+ vert.len + diag.len + cross.len +
           height + width, data=fish)
</pre>
<pre>pander(summary(fit2), caption="")
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
speciesPike 0.05541

</div>
<div class="column">
0.2937 0.175 0.2779 0.3122 0.2108 0.2758 0.2231 0.08372 0.1056 0.06794 0.03017 0.05518

</div>
<div class="column">
t value

8.263 0.8803 0.6002 0.1775 0.6039 -4.097 1.427 1.18 -1.024 0.9321 2.239 3.575

</div>
<div class="column">
Adjusted R2 0.931

Pr(&gt;|t|)

7.889e-14 0.3801 0.5493 0.8594 0.5468 6.921e-05 0.1558 0.2401 0.3078 0.3528 0.0267 0.0004756

Adjusted R2 0.9733

</div>
</div>
<div class="layoutArea">
<div class="column">
speciesRoach speciesSmelt speciesWhitefish vert.len diag.len cross.len height width

Observations

158 0.2165

<pre>BIC(fit2)
## [1] 18.19266
</pre>
<pre>##
## Family: gaussian
## Link function: identity
##
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
0.1273 -1.13 0.3183 0.09876 -0.1081 0.06333 0.06754 0.1973

</div>
</div>
<div class="layoutArea">
<div class="column">
Residual Std. Error

</div>
<div class="column">
R2 0.9752

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>library(mgcv)
gam1&lt;-gam(log(weight)~species+ s(vert.len) + s(diag.len) + s(cross.len) +
</pre>
<pre>           s(height) + s(width), data=fish, method="REML")
summary(gam1)
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>## Formula:
## log(weight) ~ species + s(vert.len) + s(diag.len) + s(cross.len) +
##     s(height) + s(width)
##
## Parametric coefficients:
</pre>
<pre>##
## (Intercept)
## speciesParkki
## speciesPerch
## speciesPike
## speciesRoach
## speciesSmelt     -0.21700    0.15076  -1.439   0.1524
## speciesWhitefish  0.23760    0.10467   2.270   0.0248 *
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
##
## Approximate significance of smooth terms:
##                edf Ref.df      F  p-value
## s(vert.len)  1.000  1.000  1.553 0.214862
## s(diag.len)  1.000  1.000  0.050 0.823955
## s(cross.len) 7.700  8.496 11.347  &lt; 2e-16 ***
## s(height)    3.128  3.999  5.486 0.000404 ***
## s(width)     3.189  4.151  7.133 2.62e-05 ***
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
##
## R-sq.(adj) =  0.996   Deviance explained = 99.6%
## -REML = -123.27  Scale est. = 0.0075377  n = 158
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Estimate Std. Error t value Pr(&gt;|t|)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>5.32479    0.09485  56.139
</pre>
<pre>                     1.395
                     1.301
                     0.696
                     1.034
</pre>
</div>
<div class="column">
<pre>&lt;2e-16 ***
0.1652
0.1953
0.4875
0.3032
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>0.12221    0.08759
0.17259    0.13261
0.11770    0.16907
0.10859    0.10506
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>par(mfrow=c(2,2))
gam.check(gam1)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
−0.2 −0.1 0.0 0.1 0.2

theoretical quantiles

Histogram of residuals

−0.4 −0.2 0.0 0.2

Residuals

</div>
<div class="column">
Resids vs. linear pred.

2 3 4 5 6 7

linear predictor

Response vs. Fitted Values

2 3 4 5 6 7

Fitted Values

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##
## Method: REML
## full convergence after 10 iterations.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Optimizer: outer newton
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Frequency

</div>
<div class="column">
deviance residuals

</div>
</div>
<div class="layoutArea">
<div class="column">
0 30 60

</div>
<div class="column">
−0.4 0.0

</div>
</div>
<div class="layoutArea">
<div class="column">
Response

</div>
<div class="column">
residuals

</div>
</div>
<div class="layoutArea">
<div class="column">
2 4 6

</div>
<div class="column">
−0.4 0.0

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<pre>## Gradient range [-4.641604e-05,9.053582e-05]
## (score -123.2722 &amp; scale 0.007537743).
## Hessian positive definite, eigenvalue range [2.131058e-05,73.19175].
## Model rank =  52 / 52
##
## Basis dimension (k) checking results. Low p-value (k-index&lt;1) may
## indicate that k is too low, especially if edf is close to k'.
##
##                k'  edf k-index p-value
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>## s(vert.len)  9.00 1.00
## s(diag.len)  9.00 1.00
## s(cross.len) 9.00 7.70
</pre>
</div>
<div class="column">
<pre>0.92    0.14
0.97    0.34
1.03    0.62
1.03    0.60
0.92    0.12
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>## s(height)
## s(width)
</pre>
</div>
<div class="column">
<pre>9.00 3.13
9.00 3.19
</pre>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>gam2&lt;-gam(log(weight)~species+ s(cross.len) + s(height) + s(width),
         data=fish,method="REML")
</pre>
<pre>gam3&lt;-gam(log(weight)~species+ cross.len + height + width,
          data=fish, method="REML")
</pre>
<pre>modname&lt;-c("GAM1", "GAM2", "GAM3")
mod.compare&lt;-data.frame(modname,
</pre>
<pre>                        c(AIC(gam1), AIC(gam2),AIC(gam3)),
</pre>
<pre>                        c(BIC(gam1), BIC(gam2), BIC(gam3)))
names(mod.compare)&lt;-c("Model", "AIC", "BIC")
</pre>
<pre>library(pander)
pander(mod.compare,round=3, align='c')
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Model

GAM1 GAM2 GAM3

</div>
<div class="column">
AIC

-296.7 -298 -24.07

</div>
<div class="column">
BIC

-216.9 -223.9 9.615

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>[2 marks] Based on the summary output for the model in fit1 which species had the lowest expected weight? Explain your answer briefly.</li>
<li>[2 marks] Does it make practical sense to interpret the intercept of the model in fit1? Explain your answer briefly.</li>
<li>[2 marks] Using the fit1 model equation, predict weight for a fish with the following characteristics: species=Bream, vert.len=7.5, diag.len= 28.4, cross.len=29.0, height=7.8, and width=4.2.</li>
<li>[2 marks] BIC values for models fit1 and fit2 are calculated as shown above. If the analyst said that based on these results, the preferred model is the one with the lower BIC value, would you agree? Explain your answer briefly.</li>
<li>[3 marks] Give a mathematical interpretation of the effect of speciesPike on weight for the model in fit2.</li>
<li>[3 marks] A GAM is fitted as shown in gam1. Comment on the non-linearity and significance of smooth terms.</li>
<li>[3 marks] Is there evidence that more basis functions are required for any of the smooth terms? Explain your answer briefly.</li>
<li>[3 marks] AIC and BIC values are calculated for three models and presented in a table as shown above. State the preferred model according to each criterion. Given that the aim of this modeling exercise is to make accurate predictions of weight, which of the three models would you choose as your preferred model? Explain your answer briefly.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
2. Write TRUE or FALSE about the following statements. Where you select FALSE, explain why you think the statement is not true.

<ol>
<li>[2 marks] Log transformations of the response variable are mainly used to deal with violation of the assumption of normality.</li>
<li>[2 marks] Preservation of hierarchy is required for polynomial and log transformations.</li>
<li>[2 marks] The following model equation is an example of a local basis function:
Y =β0 +β1(1/X1)+β2X2 +β3X2 +ε.
</li>
<li>[2 marks] In a linear model, checking of model assumptions can be carried out using the response variable Y instead of the residuals.</li>
<li>[2 marks] The following model is an example of a non-linear model:

Y =β0 +β1(1/X1)+β2log(X2)+β3X3 +ε.</li>
</ol>
Test total: 30 marks

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
