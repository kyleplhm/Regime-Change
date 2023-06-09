# Regime-Change

Use this link to view the R Markdown html: https://kyleplhm.github.io/Regime-Change/Online_Regime_Change_Detection.html

This analysis is an anonymized recreation of my contribution to a larger Cal Poly MSBA capstone project in support of a large North American utilities company. Our group was tasked with detecting significant changes in constraint flow beyond normal seasonality also known as regime changes. This model leverages an R package called onlineBcp that uses Bayesian probabilities to detect changes in time-series data in real-time( a.k.a "online").

The data used in this demonstration is a synthetic recreation of time-series energy data for a single constraint.

What is a constraint? What is constraint flow? Why is this important?

In the context of a utilities company, constraints refer to limitations in the power grid, impacting its efficiency and reliability. These constraints can arise from transmission line capacity, generation limitations, network topology, and regulatory or market restrictions. When combined with the term "constraint flow," it refers to the flow of electricity through a constrained part of the power grid, which can be influenced by these factors. Power companies and grid operators work to mitigate these constraints, ensuring stable and cost-effective electricity delivery.

Having a method to detect large, prolonged changes in constraint flow can allow the utilities company to take proactive actions to maintain stability within the power grid instead of reacting when things begin to breakdown, ultimately saving money in the long run.
