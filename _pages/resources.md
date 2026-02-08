---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---

<style type="text/css">
  .gallery img {
  display: block; /* Makes the margin work as expected */
  margin-bottom: 15px; /* Adjust the space below each image */
  width: 100%; /* Example to control image width, adjust as needed */
  }
</style>


This page contains some links to material that I've found useful over the years and that I think may be useful for others. Inclusion doesn't imply endorsement but merely flags the work as interesting, insightful, or generally helpful in some way. 

<!-- ## Advice for starting your PhD in (bio)statistics -->

## General advice

[Sherri Rose](https://drsherrirose.org/resources) has great posts and many links on her resources page. 

[Shomir Wilson](https://shomir.net/advice.html) has written many advice posts for the different stages of an academic career (starting with the undergraduate level up to tenured professors). 

I found this [aggregation](https://sites.google.com/view/econgradadvice/) of advice for Econ PhD students while searching for the links to include on this page. Have not read many of these links but looks super helpful! Also, a note for (bio)statistics students, a lot of this advice will be relevant to you too. And since there isn't much stat-specific advice out there, I think these are valuable. 


## Causal inference materials

### Textbooks

There have been many recent textbooks introducing causal inference. Below are a few that are freely available online (as of 2026-02):

- [*What If?*](https://miguelhernan.org/whatifbook) by Miguel Hernán and James Robins. Probably the most relevant textbook for those interested in epidemiology applications since it covers topics like time-varying confounding and right-censoring. 
- [*Causal Inference: A Statistical Learning Approach*](https://web.stanford.edu/~swager/causal_inf_book.pdf) by Stefan Wager. As the name suggests, there is a focus on using machine learning. Also includes specialized topics common in social sciences such as identification arguments for observational studies (regression discontinuity, difference-in-differences, synthetic controls), policy learning, and interference / spillovers. 
- [*Applied Causal Inference Powered by ML and AI*](https://causalml-book.org/) by Victor Chernozhukov, Christian Hansen, Nathan Kallus, Martin Spindler, Vasilis Syrgkanis. Econometrics focused and includes discussion of LLMs and other AI tools. 
- [*Targeted Learning in R*](https://tlverse.org/tlverse-handbook/) by Mark van der Laan, Jeremy Coyle, Nima Hejazi, Ivana Malenica, Rachael Phillips, and Alan Hubbard. A handbook that provides R code using `tlverse` packages. 


### Difference-in-differences

Wonderful [introduction](https://diff.healthpolicydatascience.org/) to difference-in-differences by Bret Zeldow, Thomas Leavitt and Laura Hatfield. May have to play around with browsers and/or browser settings to get the math to render properly. Works on a clean install of Google Chrome for me. 

Somewhat recent review [article](https://www.sciencedirect.com/science/article/abs/pii/S0304407623001318) (arXiv [link](https://arxiv.org/abs/2201.01194)) on developments in difference-in-differences. 

Practitioner's [guide](http://arxiv.org/abs/2503.13323) to using difference-in-differences, utilizing the "forward-engineering" approach to causal inference where you start with the causal estimand, show identification, and then propose an estimator (in contrast to the approach of interpreting parameters in a statistical model, e.g., linear model with two-way fixed effects). 

[Jonathan Roth](https://www.jonathandroth.com/did-resources/) and [Pedro Sant'Anna](https://psantanna.com/did-resources/) have resources such as slides on their websites. 


## Blogs I like

[DiD Digest](https://www.diddigest.xyz/): Blog run by Beatriz Gietner that collects and summarizes papers related to difference-in-differences. 

[Statistical Modeling, Causal Inference, and Social Science](https://statmodeling.stat.columbia.edu/): Andrew Gelman's blog (with occasional posts from others). Daily posts on all things statistics and, sometimes, cats. Highly influential for me personally in developing my statistical philosophy and motivating me to pursure a career in statistics. 

<!-- [Chris Blattman's blog](https://chrisblattman.com/blog/): Currently inactive (as of 2026-02) blog by an economist/political scientist who studies violence and conflict, especially in developing countries.  -->


## AI tools

There are lots of AI tools popping up these days. You probably know about LLMs but there are other tools that may be helpful. Some links that may be helpful:

- https://johannesschmitt.gitlab.io/AI_applications.html
- https://instats.org/seminar/ai-tools-for-researchers-free-seminar-1