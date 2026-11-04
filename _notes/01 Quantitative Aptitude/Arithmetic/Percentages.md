---
title: "Percentages"
destination: "01 Quantitative Aptitude/Arithmetic/Percentages.md"
subject: Quantitative Aptitude
topic: Arithmetic
subtopic: Percentages
tags:
  - CAT
  - Quantitative-Aptitude
  - Arithmetic
  - Percentages
---

# Percentages

## Practice questions — application of percentages

*The following are original practice questions. Suggested times are intended as pacing targets.*

### Q2. Expenditure unchanged after a price decrease

**Question**

The price of sugar decreases by 20%. By what percentage can a consumer increase consumption so that expenditure remains unchanged?

<text>Suggested time: 75 seconds</text>

**Concept being tested**

When expenditure remains constant:

$$
\text{Price} \times \text{Quantity} = \text{Constant}
$$

A decrease in price must therefore be offset by an increase in quantity.

**Step-by-step solution**

Assume the original price is 100 per unit and the original consumption is 1 unit.

- Original expenditure = 100 × 1 = 100.
- New price after a 20% decrease = 80.
- To keep expenditure at 100, new consumption must be:

$$
\text{New consumption} = \frac{100}{80}=1.25
$$

The consumer can consume 1.25 times the original quantity.

$$
\text{Percentage increase}=(1.25-1)\times100=25\%
$$

> [!success] Final answer
> **25% increase in consumption.**

> [!warning] Common trap
> A 20% decrease in price does not mean consumption can increase by 20%. The increase is calculated on the reduced price.

### Q3. Finding maximum marks from two students' results

**Question**

A student scores 30% marks and fails by 12 marks. Another student scores 40% marks and gets 18 marks more than the passing marks. Find the maximum marks.

<text>Suggested time: 120 seconds</text>

**Concept being tested**

Both students' scores are measured against the same maximum marks and the same passing-mark threshold. The difference between their scores can be found by combining their distances from the passing marks.

**Step-by-step solution**

- The first student is 12 marks below the passing marks.
- The second student is 18 marks above the passing marks.
- Therefore, the difference between their scores is:

$$
12+18=30\text{ marks}
$$

Their percentage scores differ by:

$$
40\%-30\%=10\%
$$

Thus, 10% of the maximum marks equals 30 marks.

$$
\text{Maximum marks}=\frac{30\times100}{10}=300
$$

> [!success] Final answer
> **300 marks.**

> [!tip] CAT approach
> When two scores lie on opposite sides of the same passing threshold, add the shortfall and the excess to obtain the difference between the scores.

### Q4. Reversing a percentage comparison

**Question**

A's income is 20% higher than B's. B's income is what percentage of A's income?

<text>Suggested time: 45 seconds</text>

**Concept being tested**

A percentage comparison depends on its reference base. If A is 20% higher than B, the 20% is calculated on B, not on A.

**Step-by-step solution**

Assume B's income is 100.

Then A's income is:

$$
100\times1.20=120
$$

B's income as a percentage of A's income is:

$$
\frac{100}{120}\times100
=\frac{5}{6}\times100
=83\frac{1}{3}\%
$$

> [!success] Final answer
> **83⅓%.**

> [!warning] Common trap
> Do not say 80%. The 20% increase is based on B's income, whereas the required percentage is based on A's income.

### Q5. Reversing successive population changes

**Question**

The population of a city increases by 25% and then decreases by 20%. If the final population is 60,000, what was the initial population?

<text>Suggested time: 90 seconds</text>

**Concept being tested**

Successive percentage changes must be applied using multipliers. To recover the initial value, divide the final value by the product of the multipliers.

**Step-by-step solution**

The multiplier for a 25% increase is 1.25.

The multiplier for a 20% decrease is 0.80.

Therefore, the overall multiplier is:

$$
1.25\times0.80=1
$$

The final population is exactly equal to the initial population.

$$
\text{Initial population}=\frac{60,000}{1}=60,000
$$

> [!success] Final answer
> **60,000.**

> [!tip] CAT shortcut
> A 25% increase followed by a 20% decrease produces no net change because:

$$
1.25\times0.80=1
$$

### Q11. Reverse percentage comparison — salary

**Question**

A's salary is 25% higher than B's salary. By what percentage is B's salary lower than A's?

**Concept being tested**

The percentage increase from B to A is measured on B. The reverse decrease from A to B is measured on A. Since the reference base changes, the reverse percentage is not 25%.

**Step-by-step solution**

Assume B's salary is 100.

A's salary is:

$$
100\times1.25=125
$$

The difference between the salaries is:

$$
125-100=25
$$

The question asks how much lower B is as a percentage of A. Therefore, use A's salary as the denominator:

$$
\frac{125-100}{125}\times100
=\frac{25}{125}\times100
=20\%
$$

> [!success] Final answer
> **B's salary is 20% lower than A's.**

> [!warning] Common trap
> Do not answer 25%. The original increase is based on B, whereas the requested decrease is based on A.

> [!tip] CAT shortcut
> If A is x% more than B, then B is:

$$
\frac{x}{100+x}\times100\%
$$

less than A. For x = 25:

$$
\frac{25}{125}\times100=20\%
$$

---

## Part E. Percentages revision sheet

Use this section for quick daily revision. The formulas below assume the percentage is applied to the stated reference value.

### Core formulas

| Concept | Formula |
|---|---|
| x% of N | xN/100 |
| Percentage change | (Change / Original value) × 100 |
| x% increase | Multiply by (1 + x/100) |
| x% decrease | Multiply by (1 − x/100) |
| Original value after an increase of x% | Final value / (1 + x/100) |
| Original value after a decrease of x% | Final value / (1 − x/100) |

### Successive percentage changes

For two successive changes of a% and b%, take increases as positive and decreases as negative.

$$
\text{Net percentage change}=a+b+\frac{ab}{100}
$$

This formula gives the net change as a percentage of the original value.

For three or more changes, multiplying the individual factors is generally safer:

$$
\text{Final value}
=
\text{Initial value}
\prod_i\left(1+\frac{r_i}{100}\right)
$$

Here, each rᵢ is positive for an increase and negative for a decrease.

### Comparing two quantities

| Given relationship | Reverse relationship |
|---|---|
| A is x% more than B | B is 100x/(100 + x)% less than A |
| A is x% less than B | B is 100x/(100 − x)% more than A |

**Conditions**

- In the second relationship, x must be less than 100 because A is a positive quantity that is less than B.
- The reverse percentage is calculated using the other quantity as its base.
- Do not assume that reversing a percentage change uses the same percentage.

### Quick checks

> [!important] Reference-base rule
> Always identify the quantity on which the percentage is calculated. A percentage is not meaningful without its reference base.

> [!summary] Daily revision
> 1. Convert increases and decreases into multipliers.
> 2. Multiply factors for successive changes.
> 3. Divide by the relevant multiplier to reverse a change.
> 4. For constant expenditure, price × quantity remains unchanged.
> 5. For comparisons such as “A is x% more than B”, keep track of whether the base is A or B.
> 6. Use the two-change shortcut only with signed percentage changes.

## Related notes

- [[Successive Percentage Change]]
- [[Profit, Loss & Discount]]
- [[Ratios & Proportions]]
- [[Averages]]
