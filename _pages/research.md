---
title: 
layout: single
classes: wide
permalink: /research/
---
<br/> 


# <center> Working Papers </center>
- - -

**Identifying Prediction Mistakes in Observational Data**. 2021.<br/>
<small>[ <a href="#/" onclick="visib('identifying-prediction-mistakes')">Abstract</a> | [Draft w/ Theory Only][identifying-prediction-mistakes] | Complete Draft Coming Soon! ]</small>

<div id="identifying-prediction-mistakes" style="display: none; text-align: justify; line-height: 1.2" ><small>
Decision makers, such as judges, doctors, and managers, make consequential choices based on predictions of unknown outcomes. Do these decision makers make systematic prediction mistakes based on the available information? In empirical settings, the preferences and information sets of decision makers are unknown to researchers, which makes uncovering systematic prediction mistakes a difficult identification problem. I develop an econometric framework to tackle this challenge and provide conditions under which systematic prediction mistakes can be identified. I show that exclusion restrictions on which observable characteristics of decisions may directly affect the decision maker's preferences and quasi-experimental variation together are sufficient to identify systematic prediction mistakes. Based on these identification results, I develop a tractable test for whether a decision maker makes systematic prediction mistakes, and methods to characterize the types of systematic prediction mistakes being made. These results are applicable to empirical settings such as pretrial release, medical testing, and many others. Future drafts will apply the theory to empirically analyze pretrial release decisions in the criminal justice system.
</small><br><br/></div>

[identifying-prediction-mistakes]:{{ site.baseurl }}{% link assets/files/asheshr_identifyingPredictionMistakes_theoryOnly_August2021.pdf %}

**An Economic Approach to Regulating Algorithms** (with [Jon Kleinberg][jkleinberg], [Jens Ludwig][jludwig] and [Sendhil Mullainathan][smullainathan]). 2021.<br/>
<small>[ <a href="#/" onclick="visib('regulatingalgorithms')">Abstract</a> | [Draft][regulatingalgorithms-nberwp] | [Slides][regulatingalgorithms-slides] ]</small>

<div id="regulatingalgorithms" style="display: none; text-align: justify; line-height: 1.2" ><small>
There is growing concern about "algorithmic bias" - that predictive algorithms used in decision-making might bake in or exacerbate discrimination in society. We argue that such concerns are naturally addressed using the tools of welfare economics. This approach overturns prevailing wisdom about the remedies for algorithmic bias. First, when a social planner builds the algorithm herself, her equity preference has no effect on the training procedure. So long as the data, however biased, contain signal, they will be used and the learning algorithm will be the same. Equity preferences alone provide no reason to alter how information is extracted from data - only how that information enters decision-making. Second, when private (possibly discriminatory) actors are the ones building algorithms, optimal regulation involves algorithmic disclosure but otherwise no restriction on training procedures. Under such disclosure, the use of algorithms strictly reduces the extent of discrimination relative to a world in which humans make all the decisions. 
</small><br><br/></div>

[jkleinberg]: https://www.cs.cornell.edu/home/kleinber/
[jludwig]: https://voices.uchicago.edu/jensludwig/
[smullainathan]: https://sendhil.org/
[regulatingalgorithms-nberwp]:{{ site.baseurl }}{% link assets/files/rklm-regulatingalgorithms-nberwp.pdf %}
[regulatingalgorithms-slides]:{{ site.baseurl }}{% link assets/files/rklm-regulatingalgos-slides.pdf %}

.

[//]: This java script is the button to show abstract
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
