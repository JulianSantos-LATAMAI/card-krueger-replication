# Replication: Card & Krueger (1994)

**Track A — Difference-in-Differences**

**Paper:** Card, D., & Krueger, A. B. (1994). Minimum Wages and Employment: 
A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania. 
*American Economic Review*, 84(4), 772–793.

## Causal Question
The paper examines whether a minimum wage increase in New Jersey caused 
a reduction in fast-food employment. Using Pennsylvania as a control group, 
the authors apply a Difference-in-Differences design to compare employment 
changes before and after New Jersey's 1992 wage hike.

## Data Source
Raw data obtained from David Card's Berkeley data archive:
https://davidcard.berkeley.edu/data_sets.html
```
# Card & Krueger (1994) Minimum Wage Study — Replication & Extension Executive Memo
**Julián Santos | ECON 5200 | Spring 2026**

---

## Bottom Line Up Front

New Jersey's 1992 minimum wage increase from $4.25 to $5.05 did not reduce employment at fast food restaurants — if anything, employment rose slightly relative to Pennsylvania, the control state. A Phase 4 extension tested whether this result masked hidden differences across store ownership type (company-owned vs. franchised) and regional political environment, and found no statistically meaningful heterogeneity along either dimension: the mandate acted as a hard floor that compressed wage-setting behavior uniformly, regardless of who owned the store or how the surrounding community voted.

---

## How We Simulated a Randomized Experiment

Running a true experiment on minimum wage policy is impossible — you cannot randomly assign a wage law to some restaurants and not others. Card and Krueger's insight was to use geography as a natural experiment. When New Jersey raised its minimum wage in April 1992 and Pennsylvania did not, the state border became the dividing line between a treatment group and a control group — not unlike a clinical drug trial where one group receives the medication and the other receives a placebo.

The key assumption is that, absent the wage increase, employment trends in New Jersey and Pennsylvania restaurants would have moved together. The pre-policy data supports this: starting wages and staffing levels were nearly identical across both states before the law took effect. This makes the post-policy divergence in outcomes attributable to the minimum wage itself, not to pre-existing differences between the two states.

The extension layer adds a second question on top of this: within New Jersey, did the treatment land differently depending on ownership structure or local political context? To test this, interaction terms were introduced into the baseline models — essentially asking whether the treatment effect varied systematically across subgroups.

---

## Key Visual Evidence

![Figure 6 — Starting Wage by State and Ownership Type](fig6_wage_by_ownership.png)

**Figure 6** shows mean starting wages before and after the mandate, split by state and ownership type. Before the policy (left panel), all four groups cluster between $4.56 and $4.63 — well below the incoming $5.05 floor. After the policy (right panel), both New Jersey groups — franchised and company-owned alike — jump sharply to just above $5.05, while Pennsylvania stores barely move. The near-identical post-mandate wages across ownership types is the core finding of the extension: the legal floor crowded out any structural differences that might otherwise have produced heterogeneous wage responses.

---

## Policy Implications

**For policymakers:** This evidence suggests that a binding minimum wage floor produces broad, uniform compliance across fast food establishments — regardless of ownership structure or local political climate. Concerns that franchisee operators would lag in compliance, or that politically resistant regions would absorb the mandate more slowly, are not supported by this data. Enforcement does not appear to require differentiation by store type.

**For business stakeholders:** Company-owned and franchised stores faced the same wage pressure and responded identically, suggesting that the structural advantages of corporate ownership (cross-subsidization, deeper capital reserves) did not translate into meaningfully different labor cost strategies at the store level.

**The key caveat:** These results hold for a single, well-studied policy shock in the fast food industry in 1992. They should not be mechanically extrapolated to larger minimum wage increases, different industries, or modern labor markets without further analysis.

---

## Repository Structure
