---
title:  "Diversity of music recommender sytems"
updated: 22/05/2020
excerpt: "Study of the diversity of algorithmic music recommendation."
header:
    teaser: /assets/images/projects/recodiv/tripartite.png
---

**Are the music recommendations locking you in a particular genre ?**

During this five month project with [Fabien Tarissan](https://www-complexnetworks.lip6.fr/~tarissan/), I studied the diversity of the recommendations made by music recommender systems.
We built upon a [diversity measure in heterogeneous networks](https://arxiv.org/abs/2001.01296) and applied it to study the algorithm from [Collaborative Filtering For Implicit Datasets](https://ieeexplore.ieee.org/document/4781121).

The main result ? The more diverse a user is, the more diverse will his recommendations be. However, for the fast majority of the users listening to recommendations reduces their diversity.

<figure style="width: 40em" class="align-center">
    <img src="/assets/images/projects/recodiv/reco_vs_organic_diversity.png" alt="User diversity prior to versus after the recommendations" class="center">
    <figcaption>User diversity increase after recommendation with respect to their original diversity. The color of each user’s dot represent the user volume of listening. Each user listened to 50 recommendations</figcaption>
</figure>

The project report is available [here](/assets/files/projects/recodiv/Studying the diversity of Recommender Systems.pdf)