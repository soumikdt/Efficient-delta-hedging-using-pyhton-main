
# 📈 Efficient Delta Hedging with Transaction Costs

##  Description
This project explores the performance of delta hedging strategies for European call options under the Black-Scholes framework, with a special focus on the effects of transaction costs. We simulate and analyze how different hedging intervals and cost structures affect hedging error and efficiency.

---
##  Objective
- Evaluate the impact of transaction costs on delta hedging strategies.
- Identify optimal hedging intervals that balance cost and hedging error.
- Quantify hedging performance using simulation-based metrics.

---
## Methodology
- **Model**: Black-Scholes framework for option pricing.
- **Instruments**: European call options with simulated underlying asset paths.
- **Hedging Strategy**: Delta hedging at fixed intervals.
- **Transaction Costs**: Proportional cost model applied during rebalancing.
- **Simulation**: Monte Carlo simulations for multiple price paths.
- **Evaluation Metrics**: Hedging error distribution, variance, and cost-efficiency trade-offs.
## Results
- Shorter rebalancing intervals reduce hedging error but significantly increase transaction costs.
- An optimal interval exists where the combined hedging error and cost are minimized.
- The trade-off curve helps visualize the sweet spot between performance and cost.

---
##  Conclusion
Efficient delta hedging must carefully balance between accuracy and cost. Frequent rebalancing reduces risk but becomes costly under realistic trading frictions. A well-chosen hedging frequency can provide near-optimal protection with manageable expenses.

---
##  Implications
- Portfolio managers and traders should incorporate transaction cost models in hedging strategy design.
- Academic studies ignoring costs may overstate the effectiveness of theoretical hedging models.
- This framework can be extended to path-dependent options and alternative market dynamics.

---


 
