---
title: Luther Yap
layout: template
---

# Luther Yap
## Welcome

Hi! I am a PhD candidate at Princeton University. My research interests are econometrics and applied microeconomics. You can view my CV [here](https://lutheryap.github.io/files/CV_Jan2022.pdf). Email: lyap@princeton.edu


## Working Papers

### Sensitivity Analysis of Policy Relevant Treatment Effects to Failures of Monotonicity

Researchers and policy makers are often interested in the external validity of a study's conclusions. An object of interest that addresses concerns of external validity is the policy-relevant treatment effect (PRTE), the average treatment effect of people who respond to the instrument in a different policy environment. This paper provides a method for bounding PRTE without functional forms or monotonicity, and gives a novel interpretation for PRTE without monotonicity as treatment effects of various subpopulations. The bounding framework uses the proportion of defiers relative to compliers as a sensitivity parameter and formulates the problem as a linear program. This method can thus be used to assess the sensitivity of various treatment effects to violations of the monotonicity assumption when using instrumental variables to make inferences on causal effects for various subpopulations. Bounds are sharp for binary outcomes and can be consistently estimated. I illustrate this method with an empirical application where defiers are present. The framework can be extended to multivalued instruments, and to parameterizing the problem using distributions to obtain quantile objects and sharp bounds. The method has many applications in applied work, including constructing nonparametric bounds on causal objects in counterfactual environments, allowing the researcher to flexibly incorporate restrictions, and testing model specification.

[Draft](https://lutheryap.github.io/files/TEBounds (4).pdf)

### Variance Estimation with Clustered Sampling and Clustered Assignment on Different Dimensions

When running OLS regressions, economists often report standard errors that are clustered on units. Apart from a model-based justification, it is often difficult to justify why one should cluster on some dimensions, such as state, and not others, such as gender. This paper provides a design-based framework where there is clustered sampling on one dimension and clustered assignment to treatment on a different dimension. Clustered sampling occurs when clusters are first sampled from a population of clusters, and units are sampled from the sampled clusters. Clustered assignment occurs when the probability that a unit is assigned treatment differs between clusters. Since assignment and sampling occur on different dimensions, it appears intuitive to use multiway clustering procedures like that proposed by Cameron, Gelbach and Miller (2011) (CGM). This paper argues that the CGM estimator is in general conservative, and there are conditions where we do not need to cluster. 

### Design-Based Justification for Clustering with Multiway Assignment

In causal inference, it is often not obvious what standard errors a researcher should report, and what dimensions a researcher should cluster the standard errors by, if at all. This paper provides a design-based perspective to when researchers should cluster when doing inference on the sample average treatment effect (ATE). By using the potential outcomes model, the researcher can be agnostic about the data generating process for the outcome and only has to consider randomness in the assignment mechanism to treatment, which is often better understood. The practical takeaway is that, when we are interested in the sample ATE, the only consideration on whether to cluster and which dimensions to cluster on is determined by assignment. Notably, this does not depend on the structure of the error term as is commonly argued in literature. Cluster on a particular dimension if and only if it affects assignment. Standard errors are conservative if we cluster on more dimensions than we have to. I illustrate the findings with a simple simulation and show consistency and asymptotic normality of standard estimators in this design-based framework.


### Market Design, Subsidies, and Supply: Interventions for Efficient and Equitable Public Housing
(with [Andrew Ferdowsian](https://app.scholarsite.io/andrew-ferdowsian) and [Kwok-Hao Lee](https://kwokhao.io/))

We study how public housing can be allocated more efficiently and equitably, comparing market design interventions to subsidies and changing the mix of apartments available. To this end, we combine tools from Urban Economics and Industrial Organization to formulate a dynamic choice model over housing lotteries. Our model is estimated on novel public housing data from the Singaporean mechanism, in which bigger apartments are sold at larger markdowns from their resale price to ensure affordability. We find that each rich household receives an average of 1.5 times the amount of subsidy that poor households receive, precisely because they opt for these larger apartments. Then, we simulate outcomes for households applying for apartments under various counterfactual mechanisms. We find that: first, if the social planner does not expand supply, it is difficult to reduce wait times in this mechanism. Second, to raise match rates for the poor, the government should subsidize them and increase prices on the largest apartments; in this policy regime, subsidies are redistributed 1-for-1 from the rich to the poor. Third, by prioritizing the poor, the government can improve their “match quality” without worsening that of the rich. Finally, building more, smaller apartments (in lieu of larger ones) results in congestion, raising wait times for the rich and lowering match rates for the poor. 


### Build to Order: Endogenous Supply in Centralized Mechanisms
(with [Andrew Ferdowsian](https://app.scholarsite.io/andrew-ferdowsian) and [Kwok-Hao Lee](https://kwokhao.io/))

How should the supply of public housing be optimally curated? Queuing mechanisms in the literature treat the supply of goods as exogenous. However, in practice, designers can often control the inflow of goods as well. We study a dynamic matching model based on the Singaporean housing allocation process. We show that endogenous supply radically changes the nature of the optimal mechanism. In this mechanism, a key feature is that under-demanded housing is overproduced relative to the static benchmark. Though competition leads to a decrease in efficiency when supply is exogenous, competition instead improves matching when supply is endogenous. Competition can be artificially generated through increasing the thickness of the market by batching applications. We show that doing so is a key feature of the optimal mechanism when the planner places a high weight on match quality.

[Draft](https://app.scholarsite.io/andrew-ferdowsian/articles/build-to-order-endogenous-supply-in-centralized-mechanisms)

## Works in Progress
“Valid t-ratio in Overidentified Two-Stage Least Squares Instrumental Variables Designs”. With David Lee, Justin McCrary, Marcelo Moreira, and Jack Porter.
 
“Bias-Aware Inference in Regression Kink Designs”. With Michal Kolesar.
 
“Identification for Dynamic Logit Models with Market Share Data”. With Kwok-Hao Lee





