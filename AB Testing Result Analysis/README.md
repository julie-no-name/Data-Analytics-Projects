# A/B Testing Result Analysis

### Task description

The goal of this project is to support decision making for an e-commerce company by analyzing the sales funnel and the results of an A/B test. The company needs to decide whether they should implement the new font in their mobile app or keep the old one.

### Project decription

In that project I analysed the sales funnel and investigated the user's path to the purchase. I also analyzed the results of the A/A/B test and checked that the division of traffic is correct, so I could advise to the company what group is better. For that project I’ve used python (pandas, numpy) to clean data and calculate the purchase funnel, plotly to visualize data interactively and scipy to measure the p-value for the experiment (I’ve used z-test)

### Data description

In that project I had the following information for each log:
- name of the event;
- the user ID;
- date of the event;
- experiment ID: 246 and 247 — control groups, 248 — experimental group.