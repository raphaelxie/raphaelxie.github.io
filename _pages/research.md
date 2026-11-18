---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---

## Network cognition in generative agents

*Research with Tyler H. McCormick, University of Washington*

How closely do AI agents' beliefs about their social networks match the interactions that take place? I study this question in a simulated town where language-model agents form memories, make plans, and talk to one another. I developed four survey instruments covering perceived ties, centrality, brokerage, and communities, along with a pipeline that compares their responses with recorded conversation networks. Surveys run on saved snapshots so that asking questions does not alter the agents' subsequent interactions.

A 25-agent pilot compared a control condition with two conditions that prevented a selected agent from starting or receiving new conversations. Agents' reported social connections showed limited agreement with recorded conversations, and they frequently ranked themselves as the most central person. Each condition contains one simulation trajectory, with three survey repeats per snapshot, so these results are descriptive. The survey asks about social connections broadly, while evaluation uses recorded conversations.

[Research code](https://github.com/raphaelxie/Generative_Agent_Cognitive_Network)

## Making expert taste computable

*Symbolic Boundaries and the Discursive Production of Value in Whisky Reviews*

*With E. Hock. Lightning talk presented at New Directions in Analyzing Text as Data (TADA), University of California, Berkeley, October 2026.*

How do experts turn sensory experiences into evaluations that others can understand? Using 11,149 whisky reviews, I built text-based models of numerical scores and compared a domain-specific sensory dictionary with generic sentiment analysis and a TF-IDF/ridge model. The sensory dictionary predicted scores better than generic sentiment analysis, while the TF-IDF/ridge model achieved the strongest predictive performance. Section-level analysis located much of the score-related variation in descriptions of smell, taste, and finish.

The project also examines how words associated with flaws convey distinctions between the natural and the artificial. It connects interpretable text analysis with questions about cultural evaluation and symbolic boundaries.

[Published papers]({{ '/publications/' | relative_url }})
