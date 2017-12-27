+++
# Date this page was created.
date = "2010-12-01"

# Project title.
title = "Exploitation-Resistant Reputation Systems"

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "rating-system.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "group-decision", "preference-learning"]`
# tags =  ["trust", "reputation", "decision-making"]
tags = []

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/rep-wide1.jpg"
caption = "Reputation Systems"

+++

Reputation systems---by supporting users' decision making in selecting "reliable strangers"---are examples of intelligent decision systems. We are often required to interact with or even _trust_ strangers in online applications. Examples are in electronic commerce (e.g., eBay and Amazon), car pooling (e.g., Uber), swapping and bartering websites (e.g., Swapsity and SwapStyle), and accommodation for travelers (e.g., Airbnb and CouchSurfing). To minimize the risk of our interactions in such applications, we must identify reliable partners (e.g., sellers, swappers, drivers, or renters). Thus, computational models of trust and reputation,
which learn how trustworthy a user is given her previous transactions, are instrumental in our decision making for selecting reliable partners. Their impact on marketplaces is significant as mistrust and uncertainty can cause a market failure. They also heavily impact the chance of these markets' failure as mistrust and uncertainty can cause a market failure.


Focusing on the possibility that fraudulent users might exploit a trust model itself---to be perceived trustworthy and reliable by others---our research argues that _exploitation resistance_ is a crucial feature of trust models, where they are impervious to the adversaries who aim to abuse them. We develop a `game-theoretic testbed` for modelling attacks and evaluating trust model performance. We demonstrate how prominent trust models can be exploited, by the _con-man attack_---a simple cyclical behaviour where a period of good transactions would be followed by a single bad transaction (e.g., a fraudulent seller sells $1$ faulty product after every $9$ working products and still keep his reputation high at least $90\\%$. We
propose new intelligent algorithms to prevent such exploitation, and demonstrate their utility.
