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


# Working Papers

**The Potential of Recommender Systems for Directing Job Search: A Large-Scale Experiment** (with L. Behaghel, M. Gurgand, S. Dromundo and T. Zuber). *Conditionally accepted, Econometrica*. <br/>
<small>[ <a href="#/" onclick="visib('lbb-job-search')">Abstract</a> | [Draft][2] ] </small>

<div id="lbb-job-search" style="display: none; text-align: justify; line-height: 1.2" ><small>
We analyze the employment effects of directing job seekers’ applications toward establishments likely to recruit. We run a two-sided randomization design involving about 800,000 job seekers and 40,000 establishments, based on an empirical model that recommends each job seeker to firms so as to maximize total potential employment. Our intervention induces a 1% increase in job finding rates for short term contracts. This impact comes from a targeting effect combining (i) a modest increase in job seekers’ applications to the very firms that were recommended to them, and (ii) a high success rate conditional on applying to these firms. Indeed, the success rate of job seekers’ applications varies considerably across firms: the efficiency of applications sent to recommended firms is 2.7 times higher than the efficiency of applications to the average firm. This suggests that there can be substantial gains from better targeting job search, leveraging firm-level heterogeneity.
</small><br><br/></div>
[2]: {{ site.baseurl }}{% link assets/files/LBB-draft.pdf %}


**Improving LATE Estimation in Experiments with Imperfect Compliance** (with S. Loewe). <br/>
<small>[ <a href="#/" onclick="visib('improve-late')">Abstract</a> | [Draft][1] ]  </small>

<div id="improve-late" style="display: none; text-align: justify; line-height: 1.2" ><small>
The evaluation of many policies of interest (e.g., educational and training programs) inevitably face incomplete treatment group take-up. Estimation of causal effects in these controlled or natural ``experiments with imperfect compliance’’ usually relies on an Instrumental Variable (IV) strategy, which often yields imprecise and thus possibly uninformative inference when compliance rates are low. We tackle this problem by proposing a Test-and-Select estimator that exploits covariate information to restrict estimation to a subpopulation with non-zero compliance. We derive the asymptotic properties of our proposed estimator under standard and weak-IV-like asymptotics, and study its finite sample properties in Monte Carlo simulations. We provide conditions under which it dominates the usual 2SLS estimator in terms of precision. Under an assumption on the degree of treatment effect heterogeneity, our estimator remains first-order unbiased with respect to the Local Average Treatment Effect (LATE) estimand, setting it apart from alternatives in the burgeoning literature on the use of first-stage heterogeneity to improve the precision of IV estimators. This robustness to treatment effect heterogeneity and the potential for precision gains is illustrated using Monte Carlo simulations and two empirical applications. Applying our methodology to the returns to schooling example (where compulsory schooling laws serve as instruments for educational attainment), we document that our methodology reduces standard errors by 12% to 48% depending on specifications.
</small><br><br/></div>
[1]: {{ site.baseurl }}{% link assets/files/LATEPS_JMP.pdf %}

**Who With Whom? Learning Optimal Matching Policies** (with T. Kitagawa). <br/>
<small>[ <a href="#/" onclick="visib('EWM-opt-match')">Abstract</a> | [Draft][whowithwho-arxiv] ] </small>

<div id="EWM-opt-match" style="display: none; text-align: justify; line-height: 1.2" ><small>
There are many economic contexts where the productivity and welfare performance of institutions and policies depend on who matches with whom. Examples include caseworkers and job seekers in job search assistance programs, medical doctors and patients, teachers and students, attorneys and defendants, and tax auditors and taxpayers, among others. Although reallocating individuals through a change in matching policy can be less costly than training personnel or introducing a new program, methods for learning optimal matching policies and their statistical performance are less studied than methods for other policy interventions. This paper develops a method to learn welfare optimal matching policies for two-sided matching problems in which a planner matches individuals based on the rich set of observable characteristics of the two sides. We formulate the learning problem as an empirical optimal transport problem with a match cost function estimated from training data, and propose estimating an optimal matching policy by maximizing the entropy regularized empirical welfare criterion. We derive a welfare regret bound for the estimated policy and characterize its convergence. We apply our proposal to the problem of matching caseworkers and job seekers in a job search assistance program, and assess its welfare performance in a simulation study calibrated with French administrative data.
</small><br><br/></div>
[whowithwhom-arxiv]: https://arxiv.org/pdf/2507.13567

- - -

# Selected Work in Progress


**Exploiting Bounded Treatment Effect Heterogeneity for Improved Inference in (Quasi-)Experiments with Imperfect Compliance** (with X. D'Haultfoeuille, P. Ketz and S. Loewe). <br/>
<small>[ <a href="#/" onclick="visib('bias-aware-late')">Abstract</a> ] </small>

<div id="bias-aware-late" style="display: none; text-align: justify; line-height: 1.2" ><small>
As a follow-up research project to Hazard and Loewe (2024), this work consider the same setting while adding a bounded treatment effect heterogeneity assumption. Relying on the constraints imposed by the LATE (Angrist and Imbens, 1994) identifying assumption on the joint distribution of the reduced form and first-stage estimands, we propose a novel estimator based on a projection of empirical moments on the constraint with a high potential for reduction in RMSE. Inference results based on resampling methods---taking into account the bias of the estimator as well as the challenge raised by inference at the border of the parameter space---are currently being developed, with encouraging results in Monte-Carlo simulations and candidate applications.
</small><br><br/></div>


**The Impact of Retraining Programs on Firms’ Labor Demand and Occupational Mobility** (with G. Azmat, L. Behaghel, R. Rathelot and J. Sultan). *Draft coming soon*. <br/>
<small>[ <a href="#/" onclick="visib('CS-study-training')">Abstract</a> ] </small>

<div id="CS-study-training" style="display: none; text-align: justify; line-height: 1.2" ><small>
We investigate the value of retraining programs in facilitating the mobility of workers into occupations in high demand. By sending 5,000 fictitious job applications to firms posting ads in six tight labor market occupations, we randomly vary the candidates' training and experience to compare labor demand for four profiles, all aged 21: an \textit{incumbent} with both initial training and experience in the posted occupation, and three \textit{movers} who initially trained and worked in a neighboring, less tight occupation. The movers differ by the extent of retraining they have undergone for the target occupation. Callback rates vary significantly, with the \textit{incumbent} receiving the highest callbacks, closely followed by the \textit{long-retraining mover} who underwent several weeks or months of retraining (59\% and 51\% callback rates, respectively). \textit{Untrained movers} and \textit{short-retraining movers} have significantly lower callback rates (30\%). We develop and test a matching model, predicting that the effect of retraining on callbacks should increase and then decrease with labor market tightness. Using geographic variation in tightness, we find that even in the tight labor markets studied, the effect of retraining on callbacks continues to increase with rising tightness.
</small><br><br/></div>


**Measuring Occupational Distances and the Aggregate Potential of Training Policies for Labor Force Reallocation** (with D. Mayaux, K. M. Frick and T. Zuber). *Draft coming soon*. <br/>
<small>[ <a href="#/" onclick="visib('occ-distance-training')">Abstract</a> ] </small>

<div id="occ-distance-training" style="display: none; text-align: justify; line-height: 1.2" ><small>
How related are different jobs in terms of skills? To what extent training programs allow to move across jobs that differ in skills, and to what extent can this reduce the ``mismatch'' unemployment --- i.e., the unemployment due to unbalances in labor demand vs. supply across occupations? The existing literature often answered the first question based on expert knowledge and existing job classification systems (O*NET, ROME classification in France etc.). Instead, we propose to build new measures of skill proximity across jobs based on job descriptions from vacancy data --- using state-of-the-art Natural Language Processing (NLP) techniques. Making use of the skill distance measure produced, we describe the labor supply reallocations associated with the use of training programs by french job seekers --- using comprehensive administrative data on unemployment spells, training use and employer-employee data. Comparing such occupational transitions in relationship with labor market tightness measures, we aim to assess the extent to which public funded training programs contribute to the reduction of mismatch unemployment.
</small><br><br/></div>


**Evaluating the Effect of Training Programs for the Unemployed: an Examiner Design Approach** (with L. Behaghel, M. Gurgand, U. Oyon Lerga).<br/>
<small>[ <a href="#/" onclick="visib('RCT-foad')">Abstract (early stage project) </a> ] </small>

<div id="RCT-foad" style="display: none; text-align: justify; line-height: 1.2" ><small>
We exploit the random allocation of caseworkers to job seekers in France---and the heterogeneity in caseworkers' propensity to place individuals in training programs---in order to build an instrument for entering a training program while unemployed. To alleviate threats to the exclusion restriction assumption, we are currently developing an identification approach combining (i) the intuition behind of so-called ``zero-first-stage'' falsification test, (ii) an identification-at-infinity argument and (iii) a single-index assumption imposed on caseworkers' direct impact on individuals' job finding rate (violating the exclusion restriction of the instrument). Our framework lends itself nicely to the use of machine-learning predictions in a first step to identify the zero-first-stage subgroups that are essential for our identification-at-infinity approach.
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
