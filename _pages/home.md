---
layout: single
permalink: /
author_profile: true
classes: wide
---

Hi ! My name is Augustin Godinot and I am currently a student at French school [Ecole Normale Paris-Saclay](https://ens-paris-sacaly.fr). 
I’m mainly interested in the applied mathematics side of Electrical Engineering and how abstract models can help to improve “real-world” systems.  

Recently, I have been working with [Fabien Tarissan](https://www-complexnetworks.lip6.fr/~tarissan) on diversity in Recommender Systems. More precisely, I am studying Recommender Systems in the music streaming industry. Via simulations of basic recommendation algorithms, I try to understand what parameters play a role on the diversity of the suggested songs.

When I am not working, I like to travel France and Europe by bike (it’s called biketouring !). 

#### Last projects

{% for project in site.projects reversed %}<!---
    -->[{{ project.title }}]( {{ project.url }}), <!---
    {% increment i_project %}
    -->{% if i_project == 2 %}{% break %}{% endif %}
{% endfor %}<!---
-->[{{ site.projects[-3].title }}]( {{ site.projects[-3].url }}) ... [others](/projects/)

#### Interests
* Applied mathematics / Signal Processing
* Machine Learning on Graphs
* Embedded Systems
