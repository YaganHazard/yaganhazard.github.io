---
title: 
layout: single
classes: wide
permalink: /research/
---
<br/> 

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PNS829G"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->


# Econometrics 

**Improving LATE estimation in experiments with imperfect compliance** (with S. Loewe). *Submitted*. <br/>
<small>[ <a href="#/" onclick="visib('improve-late')">Abstract</a> | [Draft][1] ]  </small>

<div id="improve-late" style="display: none; text-align: justify; line-height: 1.2" ><small>
The evaluation of many policies of interest (e.g., educational and training programs) inevitably face incomplete treatment group take-up. Estimation of causal effects in these controlled or natural ``experiments with imperfect compliance’’ usually relies on an Instrumental Variable (IV) strategy, which often yields imprecise and thus possibly uninformative inference when compliance rates are low. We tackle this problem by proposing a Test-and-Select estimator that exploits covariate information to restrict estimation to a subpopulation with non-zero compliance. We derive the asymptotic properties of our proposed estimator under standard and weak-IV-like asymptotics, and study its finite sample properties in Monte Carlo simulations. We provide conditions under which it dominates the usual 2SLS estimator in terms of precision. Under an assumption on the degree of treatment effect heterogeneity, our estimator remains first-order unbiased with respect to the Local Average Treatment Effect (LATE) estimand, setting it apart from alternatives in the burgeoning literature on the use of first-stage heterogeneity to improve the precision of IV estimators. This robustness to treatment effect heterogeneity and the potential for precision gains is illustrated using Monte Carlo simulations and two empirical applications. Applying our methodology to the returns to schooling example (where compulsory schooling laws serve as instruments for educational attainment), we document that our methodology reduces standard errors by 12% to 48% depending on specifications.
</small><br><br/></div>
[1]: {{ site.baseurl }}{% link assets/files/LATEPS_JMP.pdf %}

**Bias-aware inference on LATE with bounded treatment effect heterogeneity** (with X. D'Haultfoeuille and S. Loewe). <br/>
<small>[ <a href="#/" onclick="visib('bias-aware-late')">Abstract</a> ] </small>

<div id="bias-aware-late" style="display: none; text-align: justify; line-height: 1.2" ><small>
As a follow-up research project, this work consider the setting studied in Hazard and Löwe (2022, see above) under the milder restriction of bounded treatment effect heterogeneity. We consider the use of bias-aware inference techniques, that have received a renewed attention in the recent econometric literature on treatment effect estimation. In the case of LATE estimation with heterogeneous first-stages across groups defined by covariates, our assumption of bounded treatment effect heterogeneity yields a set of restrictions on the relationship between the Intention-to-Treat (ITT) and the first-stage statistics within each group. We (i) derive the worst-case bias of an Anderson-Rubin statistic in this framework, (ii) propose a procedure to create bias-aware Confidence Intervals (CIs) for the LATE by (repeated) test inversion, and (iii) study the properties of the resulting CIs compared to standard inferential procedures.
</small><br><br/></div>


**Empirical welfare maximization and optimal matching policies** (with T. Kitagawa). <br/>
<small>[ <a href="#/" onclick="visib('EWM-opt-match')">Abstract</a> ] </small>

<div id="EWM-opt-match" style="display: none; text-align: justify; line-height: 1.2" ><small>
Suppose a policy maker has to choose (based on quasi-experimental data) how to match two types of individuals (e.g., job seekers and caseworkers, students and teachers etc.) to maximize a given measure of output (job finding rate, grades etc.). Following the empirical welfare maximization principle, a feasible decision rule could be to implement the allocation that would yield the highest possible output as estimated from the sample. How well would perform such a decision rule compared to the actual optimal allocation? Earlier work by T. Kitagawa and A. Tetenov (2018) have already derive finite sample guarantees on the performance of such rules for the choice of a binary treatment —-- but not for the choice of an entire matching policy, as is the goal of this project. Building on the optimal transport literature, we aim at deriving such bounds in this particular setting.
</small><br><br/></div>

- - -

# Labor Economics 

**The Potential of Recommender Systems for Directing Job Search: A Large-Scale Experiment** (with L. Behaghel, M. Gurgand, S. Dromundo and T. Zuber). *Revise and Resubmit, Econometrica*. <br/>
<small>[ <a href="#/" onclick="visib('lbb-job-search')">Abstract</a> | [Draft][2] ] </small>

<div id="lbb-job-search" style="display: none; text-align: justify; line-height: 1.2" ><small>
We analyze the employment effects of directing job seekers’ applications toward establishments likely to recruit. We run a two-sided randomization design involving about 800,000 job seekers and 40,000 establishments, based on an empirical model that recommends each job seeker to firms so as to maximize total potential employment. Our intervention induces a 1% increase in job finding rates for short term contracts. This impact comes from a targeting effect combining (i) a modest increase in job seekers’ applications to the very firms that were recommended to them, and (ii) a high success rate conditional on applying to these firms. Indeed, the success rate of job seekers’ applications varies considerably across firms: the efficiency of applications sent to recommended firms is 2.7 times higher than the efficiency of applications to the average firm. This suggests that there can be substantial gains from better targeting job search, leveraging firm-level heterogeneity.
</small><br><br/></div>
[2]: {{ site.baseurl }}{% link assets/files/LBB-draft.pdf %}



**Evaluating the effect of training programs on occupational transitions: a correspondence study** (with G. Azmat, L. Behaghel, R. Rathelot and J. Sultan).<br/>
<small>[ <a href="#/" onclick="visib('CS-study-training')">Abstract</a> ] </small>

<div id="CS-study-training" style="display: none; text-align: justify; line-height: 1.2" ><small>
To which extent can short and/or long training programs help in moving from slack to tight labor markets? In order to answer this question, we send to firms fake CVs where we manipulate the occupation the applicant used to work in, and the type of training s/he has received related to the occupation firms are hiring in. Preliminary results are encouraging, showing contrasts between the different versions of the CVs tested. We plan on studying the heterogeneity of the effect of training programs on callback rates depending on labor market tightness, and relate it to the theoretical predictions of a search and matching model of the labor market.
</small><br><br/></div>


**Measuring occupational distances and the aggregate potential of training policies for labor force reallocation** (with D. Mayaux, K. M. Frick and T. Zuber).<br/>
<small>[ <a href="#/" onclick="visib('occ-distance-training')">Abstract</a> ] </small>

<div id="occ-distance-training" style="display: none; text-align: justify; line-height: 1.2" ><small>
How related are different jobs in terms of skills? To what extent training programs allow to move across jobs that differ in skills, and to what extent can this reduce the ``mismatch'' unemployment --- i.e., the unemployment due to unbalances in labor demand vs. supply across occupations? The existing literature often answered the first question based on expert knowledge and existing job classification systems (O*NET, ROME classification in France etc.). Instead, we propose to build new measures of skill proximity across jobs based on job descriptions from vacancy data --- using state-of-the-art Natural Language Processing (NLP) techniques. Making use of the skill distance measure produced, we describe the labor supply reallocations associated with the use of training programs by french job seekers --- using comprehensive administrative data on unemployment spells, training use and employer-employee data. Comparing such occupational transitions in relationship with labor market tightness measures, we aim to assess the extent to which public funded training programs contribute to the reduction of mismatch unemployment.
</small><br><br/></div>


**Evaluating the effect of online training programs on employment: a randomized controlled trial** (with P. Arni, L. Behaghel, M. Gurgand, R. Rathelot and T. Zuber).<br/>
<small>[ <a href="#/" onclick="visib('RCT-foad')">Abstract</a> ] </small>

<div id="RCT-foad" style="display: none; text-align: justify; line-height: 1.2" ><small>
Training programs are famously difficult to evaluate in controlled experiments due to the absence of effective and ethical encouragement devices to increase training take-up rates. In this project, we collaborate with the French Public Employment Services (PES) in order to try various encouragement designs to increase the use of online training programs --- that have been massively developed in the wake of the Covid pandemic. In order to maximize statistical power, we design our questionnaires with the aim to identify sub-populations that are more likely to comply to our encouragement --- that is a combination of some information disclosure on tightness across neighboring labor markets and a decrease of the administrative burden associated to training inscription procedures.
</small><br><br/></div>

[//]: This java script is the button to show Abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
