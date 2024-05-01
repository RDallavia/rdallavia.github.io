---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S., Finance, University of Wisconsin - Madison
* B.A., <i>cum laude</i>, Sociology - Complex Organizations, William & Mary

Projects
======
* Pricing analytics for ski-resort seeking an increase in ROA through a potential price hike and insight into the beneficent effects of a recent investment on company performance. <strong> Results of random-forest model indicated ticket prices could be increased by over 30%. </strong> Addressed research questions using internal company data and external data from comparable resorts.  Workflow consisted of data wrangling, exploratory data analysis, preprocessing, and modelling.  Generated random forest model.  Technologies used included Python, Scikit-Learn, NumPy, Seaborn, & Matplotlib.

* “Is There Anything On?” <strong> This low-rank, collaborative movie recommendation engine yielded 10 movie recommendations of which 70% were consistent with user preferences versus a hierarchical clustering approach that produced only 3 recommendations out of 10 that deemed watchable. </strong> The low-rank approach relies on the family of matrix decomposition techniques popularized during the Netflix recommendation engine challenge of 2006. Technology used included Python, SciPy, NumPy, Pandas, Seaborn, Matplotlib.

* “That’s Unusual.”  This Gaussian anomaly detection model was used to identify networked servers worthy of inspection.  <strong> Several non-obvious servers were tagged as anomalous, which would allow a sys admins to intervene before the server malfunction. </strong>  Given a training set, we constructed a model to predict the probability that any one server is anomalous.  The servers are tagged as anomalous if the probability of one of the servers being anomalous is below a threshold, epsilon  This technology can be used in fraud detection. Technology used included Python, SciPy, NumPy, Pandas, Seaborn, Matplotlib.

* "Who's Who in our Database?" Hierarchical and k-means clustering models were used to segment an airline customer database to search for similarities among users.  6 groups were chosen based on a dendrogram, and the shared characteristics within each cohort were noted.  Though this type of unsupervised learning does not result in a prediction, <strong> the insights it yielded could be used as the foundation for a targeted marketing campaign. </strong>  Written in R and relying primarily on tidyverse and caret.

*	Code 312: Non-profit, volunteer organization of software developers in the Chicago area.  Currently expanding the site for The Chicago Council on Science and Technology and migrating said site to GitHub Pages.


Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
