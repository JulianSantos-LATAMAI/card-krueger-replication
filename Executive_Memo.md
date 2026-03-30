# Card & Krueger (1994) Minimum Wage Study — Replication & Extension
**Julián Santos | ECON 5200 | Spring 2026**

---

## Bottom Line Up Front

New Jersey's 1992 minimum wage increase from $4.25 to $5.05 produced 
near-uniform compliance across all fast food store types — franchised 
($5.08) and company-owned ($5.07) NJ stores converged just above the 
new floor regardless of ownership structure or regional political lean. 
A Phase 4 extension finds that conservative-region NJ stores, which 
started at lower pre-mandate wages ($4.56 vs $4.69), experienced a 
larger absolute wage increase — consistent with the mandate being more 
binding where wages were most compressed — but no ownership-type 
heterogeneity was detected.

---

## How We Simulated a Randomized Experiment

Running a true experiment on minimum wage policy is impossible — you cannot randomly assign a wage law to some restaurants and not others. Card and Krueger's insight was to use geography as a natural experiment. When New Jersey raised its minimum wage in April 1992 and Pennsylvania did not, the state border became the dividing line between a treatment group and a control group — not unlike a clinical drug trial where one group receives the medication and the other receives a placebo.

The key assumption is that, absent the wage increase, employment trends in New Jersey and Pennsylvania restaurants would have moved together. The pre-policy data supports this: starting wages and staffing levels were nearly identical across both states before the law took effect. This makes the post-policy divergence in outcomes attributable to the minimum wage itself, not to pre-existing differences between the two states.

The extension layer adds a second question on top of this: within New Jersey, did the treatment land differently depending on ownership structure or local political context? To test this, interaction terms were introduced into the baseline models — essentially asking whether the treatment effect varied systematically across subgroups.

---

## Key Visual Evidence


<img width="1389" height="593" alt="image" src="https://github.com/user-attachments/assets/52c6fe52-4390-421f-8d2f-899b9469b0e6" />

**Figure 6** Figure 6 shows mean starting wages before and after the mandate, split by state and ownership type. Before the policy (left panel), the two NJ groups clustered tightly between $4.62 and $4.68 — well below the incoming $5.05 floor — while PA stores showed a notable split: franchisees at $4.61 and company-owned stores already paying a premium at $4.79, suggesting corporate ownership carried a pre-existing wage advantage in the control state. After the policy (right panel), both NJ groups — franchised and company-owned alike — jump sharply to just above $5.05 ($5.084 and $5.072 respectively), while Pennsylvania stores barely move. The near-identical post-mandate wages across NJ ownership types is the core finding of the extension: the legal floor crowded out any structural differences that might otherwise have produced heterogeneous wage responses, compressing what was a meaningful ownership gap in Pennsylvania into statistical noise on the New Jersey side of the border.

---

## Policy Implications

**For policymakers:** This evidence suggests that a binding minimum wage floor produces broad, uniform compliance across fast food establishments — regardless of ownership structure or local political climate. Concerns that franchisee operators would lag in compliance, or that politically resistant regions would absorb the mandate more slowly, are not supported by this data. Enforcement does not appear to require differentiation by store type.

**For business stakeholders:** Company-owned and franchised stores faced the same wage pressure and responded identically, suggesting that the structural advantages of corporate ownership (cross-subsidization, deeper capital reserves) did not translate into meaningfully different labor cost strategies at the store level.

**The key caveat:** These results hold for a single, well-studied policy shock in the fast food industry in 1992. They should not be mechanically extrapolated to larger minimum wage increases, different industries, or modern labor markets without further analysis. Additionally, since 1992, the culture around minimum wage has changed significantly. When Card & Krueger conducted their studies, a minimum wage was livable. Nowadays, it is more taboo because prices have increased so quickly. 

