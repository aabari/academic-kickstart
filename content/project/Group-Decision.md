+++
# Date this page was created.
date = "2017-12-25"

# Project title.
title = "Group Decision Making on Social Networks"

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "group-small.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "group-decision", "preference-learning"]`
# tags =  ["group-decision"]
tags = []

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/banner1.png"
caption = "Social Network"

+++


This research explores the design and development of *group decision systems*, which address the problem of making a decision for a group of individuals who each have their own preferences. These problems are prevalent: e.g., target advertising to a group of users, when a group of friends choose a movie or a restaurant, or selecting economic or health-care policies for a nation. Many applications that deal with user preferences (e.g., recommender systems, advertisement and marketing mechanisms, etc.) have some sort of group decision problem at their core.

One of the main endeavours in any group decision system is learning user preferences upon which decisions are made. This learning aims to reduce the cognitive and communication burden imposed on users, by requiring as little information as possible to make decisions consistent with user preferences. This is essential to the practicality of decision-support systems with the goal of filtering out irrelevant options and information.

We contend that `social networks provide a natural and informative platform for preference learning and consequently group decision problems`. Our goal is to advance the understanding and mathematical modelling of preference dynamics and correlations over social networks, then exploits the computational and predictive power of these models for developing efficient algorithms of group decision making, with less required user data, and lower cognitive and communication burden. Specific questions direct our research:


1. To what extent are individual preferences correlated in a social network?  
2. What dynamics dictate how preference correlations form in a social network?
3. How should one mathematically model such correlations and dynamics?
4. Can such correlations and dynamics be harnessed for more efficient preference learning, and more effective group decision making?



## Group Recommendation with Empathetic Preferences on Social Networks
We often modify and express preferences similar to those of our friends or families due to our feelings of empathy. Our research was the first to incorporate [the dynamics of empathy into intelligent decision systems]( {{< relref "AAMAS2014.md" >}} ). We created an _empathetic framework_ in which user preferences are derived from both their own _intrinsic_ preferences and _empathetic_ preferences (determined by the satisfaction of their acquaintances)---e.g., friends voting on a movie to watch while considering both their own and others' satisfaction. After studding the theoretical conditions under which empathetic preferences are well-defined (i.e., converge to a fixed-point),
Under this framework, I developed scalable algorithms for group recommendation, which can handle a large-scale population and option space (e.g., millions of users and options).  Our framework and algorithms reduce the burden on users dramatically, as users are no longer required to communicate their preferences to each other.  
Our theoretical and empirical analyses shed light on how preferences become correlated due to the presence of empathy and confirm that neglecting empathy usually yields sub-optimal group decisions.

## Inferring Missing Preferences
 Can an intelligent decision system make an efficient decision when faced with missing preferences? Our research shows this is possible, by capturing preference correlations in social networks and exploiting them to infer missing preferences.To capture preference correlations, we introduce a network formation model called [ranking networks]({{< relref "RankingNet.md">}}). Using this model, we develop machine learning algorithms to [infer missing individual preferences]({{< relref "Recsys2015.md" >}}) given known preferences of others in the social network. Intuitively, if I know something about the preferences of your friends or family, I should be able to more accurately predict your preferences. These predictions are leveraged for group decision making when some group members' preferences are unknown (or even in cases where all group members' preferences are unknown, but we have observed their connections to individuals outside of the group). Using data from a large-scale social network with millions of users, I demonstrated that incorporating social ties can significantly improve preference predictions and group decision making.
