# Updated Bayesian Thinking and Workflow for Political Science 

An aspirational project outline for a "post-PhD debrief" about Bayesian lessons learned. 
The idea here is to memorialize the [_shadow dissertation_](https://twitter.com/mikedecr/status/1281304803109412868), all of the things I learned about doing Bayesian statistics that are totally banal in the world of applied Bayesian researchers, but almost entirely absent from applied political science.
Political science has classic Bayesian texts (Jackman, Gill...) but they are a little dated.
A new generation of lessons for Bayesian research from statistics, biological sciences, and psychology is absent from political science except implicitly in individual papers.
Since these lessons come from other fields, papers and books that discuss the innovations unto themselves use different notational conventions and unfamiliar jargon, and the modeling intuitions aren't always easy to connect to political science applications.

The intent for this project is to center a conversation on new Bayesian thinking and methods in political science venues using political science problems as motivation.
It envisions two papers that discuss Bayesian approaches (broadly) separately from pragmatic advice for Bayesian implementation.


## 1. Revisiting Bayesian Foundations in Political Science.

The "ideas" paper. Reframing of Bayesian modeling ideas for a new era.

- We also have new ways to talk about what Bayesian modeling _is_, information without invoking hazy notions of "belief." 
- New pedagogy for discussing what Bayes is. "Merely conditional probability," generative modeling, running model forward/backward, "Bayesian inference without frequentist language" to unify the machinery of priors to the same machinery we use all the time in MLE (but careful not to make Bayes sound like MLE-plus-prior).
- We have new computational tools for estimating models that change our calculations for what things can be feasibly modeled and how.
- New insights about model parameterization, properties of prior distributions, likelihood context for priors, new models altogether, and so on.
- Basically none of this stuff is available in the classic Bayesian tomes in PS. 


## 2. Updating the Bayesian Modeling Workflow for Political Science.

The "how-to" paper. Tricks of the trade for thinking about, building, and checking Bayesian models. Again, things NOT FOUND in Jackman or Gill.

- Discuss the software innovations since the canonical Bayesian texts in polisci (Stan, Hamiltonian Monte Carlo, VBI, ADVI) and how they affect model building, diagnosis, and validation (mainly focused on Stan, HMC, divergences, new R-hat...). 
- New thinking about prior strategy: revisiting the value of conjugacy, entropy, "objectivity", ins and outs of each and why you might/not want each. Implied priors for functions of parameters. 
- Model building: parameterization (non-centering, beta-binomial, etc.), regularizing priors (Normal/T/Cauchy), covariance matrix priors (LKJ), Cholesky, sparsity-inducing priors, simplexes and other generative modeling ideas. 
- Workflow: prior checks, implied priors, posterior checking, LOO



