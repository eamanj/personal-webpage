---
layout: page
title: Network Effects on Unequal Outcomes
description: An experimental sutdy on how networks can exacerbate inter-group differences
img: /assets/img/experiment.jpg
importance: 2
category: Current
---

In this project, we study the network effects on unequal outcomes within a controlled lab
environment. In particular, we investigate the conditions under which networks can
exacerbate existing inter-group differences, hence widening any gaps that might exist
betwen two groups. To this end, we develop an online lab experiment to study the network
mechanisms that widen inter-group differences and yield different returns on social
capital to different groups.

We model the network effects on utility in a context with repeated diffusion of a resource (originating from random
sources according to a known distribution) access to which increases one’s utility. The
repeated nature of this diffusion process could amplify individual or group differences in
utility over time. Our goal is to characterize the factors that affect the final
inter-group utility differences. In particular, assume there are two groups in the network
(rich/poor). Members of group 1 and 2 have $$u_1$$ and $$u_2$$ expected utility of
receiving the resource on their own in each round ($$u_1 > u_2$$). Within each round,
nodes can receive extra utility from their neighbors if they also receive the resource
(For example, the resource can diffuse to a limited number of members until it loses its
value). Adding the individual and network components of the utility, members of each group
will have an average total utility of $$a_1$$ and $$a_2$$. We will investigate the
necessary conditions for the network mechanism to result in the following comparison:
$$\frac{a_1}{a_2} > \frac{u_1}{u_2}$$. In other words, what network structures, utility
functions, and group compositions will amplify the the inter-group advantages to be
greater than exogenous individual differences? The extent of this difference will greatly
depend on the network structure, in particular homophily and brokerage. 
We will also investigate the effect of other factors such as rivalrous
vs. non-rivalrous diffusion.

We implement the above setup in an online randomized lab experiment in a manner similar to
[1].  We recruit individuals to play an online collaborative game in which they have to
find and dig gold mines and in the process can pass information to their neighbors
according to the network structure.  The amount of gold they discover during the game,
either by themselves or from their contacts, will determine their final compensation, akin
to their utility.  By randomizing the network structure, and composition of groups with
low and high initial advantage, we aim to generate the processes that lead to unequal
distribution of opportunities to a group, beyond what’s expected by their individual
differences. 

<div class="row justify-content-center">
    <div class="col-sm-11 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/experiment.jpg' | relative_url }}" alt="" title="onlin experiment"/>
    </div>
</div>
<div class="caption">
Figure 1. A screenshot of the multi-player game where the player has received information
about the structure of the map from their contacts and has to decide where to dig for
gold.
</div>



<h2>References</h2>
[1] Winter Mason and Duncan J Watts. Collaborative learning in networks. Pro- ceedings of the
National Academy of Sciences, 109(3):764–769, 2012.
