---
title: "Profit, Loss & Discount"
destination: "01 Quantitative Aptitude/Arithmetic/Profit, Loss & Discount.md"
subject: Quantitative Aptitude
topic: Arithmetic
subtopic: Profit, Loss & Discount
tags:
  - CAT
  - Quantitative-Aptitude
  - Arithmetic
  - Profit-Loss-Discount
---

# Profit, Loss & Discount

## Concepts

### Cost price, selling price and marked price

- **Cost Price (CP):** Amount paid by the shopkeeper to acquire the item.
- **Selling Price (SP):** Amount at which the item is sold.
- **Marked Price (MP):** Displayed price before discount.
- **Profit:** SP − CP, when SP is greater than CP.
- **Discount:** MP − SP.

Profit percentage is calculated on cost price; discount percentage is calculated on marked price.

> [!abstract] Core idea
> Keep the reference bases separate: **profit % uses CP; discount % uses MP**.

<!-- CAT-UPDATE-ID: 0d9400a9daa026ec -->
### Trick: Same selling price, one profit and one loss

A shopkeeper sells two articles at the same selling price. On one article, the gain is x%; on the other, the loss is x%.

For equal selling prices and equal profit/loss percentages, the overall result is always a loss:

$$
\text{Overall loss}\%=\frac{x^2}{100}
$$

**Example: 20% gain and 20% loss**

$$
\text{Loss}\%=\frac{20^2}{100}=4\%
$$

The result is not zero because the two articles have different cost prices. The article sold at a loss has the higher cost price.

### Trick: False weights

A dishonest seller may charge for 1 kg but supply only 900 g, while claiming to sell at cost price.

Assume the cost of 1 kg is ₹100. The seller collects ₹100 but supplies goods costing only ₹90.

$$
\text{Profit}\%=\frac{100-90}{90}\times100=11.11\%
$$

**Shortcut:** When the seller charges for the stated quantity but supplies less, calculate profit using the cost of the actual quantity supplied as the denominator.

### Trick: Reverse calculations

If SP and profit percentage are known:

$$
CP=\frac{SP}{1+p/100}
$$

If SP and loss percentage are known:

$$
CP=\frac{SP}{1-l/100}
$$

If SP and discount percentage are known:

$$
MP=\frac{SP}{1-d/100}
$$

Here, p = profit percentage, l = loss percentage and d = discount percentage.

### Trick: Markup followed by discount

If MP is 40% above CP and a discount of 25% is offered:

$$
SP=CP\times1.4\times0.75
$$

$$
SP=1.05CP
$$

Therefore, profit = 5%.

**General shortcut:** Convert every percentage change into a multiplier and multiply the factors. Do not add successive percentage changes directly.
<!-- /CAT-UPDATE-ID: 0d9400a9daa026ec -->

## Formulas / rules

For a profit of p%:

$$
SP=CP\left(1+\frac{p}{100}\right)
$$

For a discount of d%:

$$
SP=MP\left(1-\frac{d}{100}\right)
$$

When both are given, equate the two expressions for SP:

$$
CP\left(1+\frac{p}{100}\right)=MP\left(1-\frac{d}{100}\right)
$$

Therefore:

$$
\frac{MP}{CP}=\frac{1+p/100}{1-d/100}
$$

## Worked examples

### Q17. Marked price above cost price

**Question**

A shopkeeper gives a discount of 25% on the marked price but still earns a profit of 20%. By what percentage is the marked price above the cost price?

**Concept being tested**

Discount is calculated on marked price, whereas profit is calculated on cost price. Convert both statements into selling-price relationships and equate them.

**Step-by-step solution**

Assume CP = 100.

A profit of 20% gives:

$$
SP=100\times1.20=120
$$

A discount of 25% means SP is 75% of MP:

$$
120=0.75MP
$$

$$
MP=\frac{120}{0.75}=160
$$

The marked price is 60 above the cost price of 100:

$$
\frac{160-100}{100}\times100=60\%
$$

> [!success] Final answer
> **The marked price is 60% above the cost price.**

> [!tip] CAT shortcut
> Since SP is 120% of CP and 75% of MP:

$$
\frac{MP}{CP}=\frac{120}{75}=1.6
$$

Thus MP is 160% of CP, i.e. 60% higher.

> [!warning] Common trap
> Do not subtract the 25% discount from the 20% profit. These percentages have different bases.

<!-- CAT-UPDATE-ID: 726c2035fb9c25c5 -->
### Example: Marked price and discount

An article is marked 60% above CP. A discount of 25% is offered. Find the profit percentage.

Assume CP = ₹100.

- MP = ₹160.
- SP = ₹160 × 0.75 = ₹120.
- Profit = ₹20.

Therefore, profit = 20%.

**Shortcut:**

$$
SP=CP\times1.6\times0.75=1.2CP
$$

### Example: Find the required discount

An article is marked 50% above CP. What discount should be offered to earn 20% profit?

Assume CP = ₹100.

- MP = ₹150.
- Required SP = ₹120.
- Discount amount = ₹30.

$$
\text{Discount}\%=\frac{30}{150}\times100=20\%
$$

**Answer: 20% discount.**

### Example: Two successive transactions

A person sells an article at 20% profit. The buyer resells it at a 10% loss. Find the final selling price as a percentage of the original CP.

Assume original CP = ₹100.

- First SP = ₹120.
- Second SP = ₹120 × 0.9 = ₹108.

$$
\text{Final SP}=100\times1.2\times0.9=108
$$

The final selling price is 108% of original CP. Overall increase = 8%.

### Example: Same SP, one profit and one loss

A shopkeeper sells two articles at the same selling price. On one he earns 20% profit and on the other he suffers 20% loss. Find the overall profit/loss.

Assume SP of each article = ₹120.

$$
CP_1=\frac{120}{1.2}=₹100
$$

$$
CP_2=\frac{120}{0.8}=₹150
$$

Total CP = ₹250; total SP = ₹240; loss = ₹10.

$$
\text{Loss}\%=\frac{10}{250}\times100=4\%
$$

**Shortcut:**

$$
\text{Loss}\%=\frac{20^2}{100}=4\%
$$

**Answer: 4% loss.**

### Example: Markup and discount

Suppose MP is 40% above CP and a discount of 25% is offered.

$$
SP=CP\times1.4\times0.75=1.05CP
$$

**Answer: 5% profit.**
<!-- /CAT-UPDATE-ID: 726c2035fb9c25c5 -->

## Common traps

- Profit percentage is not calculated on selling price.
- Discount percentage is not calculated on cost price.
- A discount and a profit can coexist if the marked price is sufficiently above cost price.
- When percentages refer to different bases, use multipliers and equate the selling price.

<!-- CAT-UPDATE-ID: ebf92a75e3ed80ad -->
### Common traps and quick checks

- **Same SP does not mean same CP.** For equal SP with equal gain/loss percentages, the loss-side article has the higher CP.
- **Do not cancel equal gain and loss percentages.** Equal SP with 20% gain and 20% loss gives 4% overall loss.
- **False-weight denominator:** Use the cost of the actual quantity supplied when calculating the dealer's real profit.
- **Discount is on MP; profit/loss is on CP.**
- **Successive discounts are multiplicative.** A 15% discount followed by 20% is 32%, not 35%.
- **Changed CP and SP:** If both change, express the new CP and SP relative to the original CP before forming the equation.
- **Weighted profit/loss:** Use weights proportional to CP contribution. If CP per unit is uniform, stock proportions can be used directly.
<!-- /CAT-UPDATE-ID: ebf92a75e3ed80ad -->

## Practice and mistakes

- [ ] I can distinguish CP, SP and MP.
- [ ] I calculate profit percentage on CP.
- [ ] I calculate discount percentage on MP.
- [ ] I can equate two expressions for SP.

<!-- CAT-UPDATE-ID: 684ef58cf7b32232 -->
## Level 3 — Difficult CAT applications

### Q17. Successive discounts

A shopkeeper offers successive discounts of 20% and 10%. If the final selling price is ₹720, find MP.

**Solution — multiplier method**

After the two discounts, the customer pays 80% × 90% of MP.

$$
720=MP\times0.8\times0.9
$$

$$
MP=\frac{720}{0.72}=\boxed{₹1,000}
$$

**Shortcut — equivalent discount**

$$
D=20+10-\frac{20\times10}{100}=28\%
$$

SP is 72% of MP, so MP = ₹1,000.

**Answer: ₹1,000.**

### Q18. Difference in selling prices

An article is sold at 25% profit. If it had been sold for ₹100 more, profit would have been 35%. Find CP.

**Solution**

Let CP = x.

$$
1.35x-1.25x=100
$$

$$
0.10x=100\Rightarrow x=\boxed{₹1,000}
$$

**Shortcut:** The profit rate increases by 10 percentage points. That increase in SP is 10% of CP.

$$
CP=\frac{100\times100}{10}=₹1,000
$$

**Answer: ₹1,000.**

### Q19. CP and SP both reduced

A trader sells an article at 20% profit. If both CP and SP were ₹100 lower, the profit percentage would be 25%. Find original CP.

**Solution**

Let original CP = x. Original profit = 20% of x. Reducing both CP and SP by ₹100 leaves the absolute profit unchanged.

$$
0.2x=0.25(x-100)
$$

$$
0.2x=0.25x-25
$$

$$
0.05x=25\Rightarrow x=\boxed{₹500}
$$

**Shortcut:** Since the absolute profit remains the same, equate the original profit amount to 25% of the reduced CP.

**Answer: ₹500.**

### Q20. Markup followed by discount

A shopkeeper marks an article 80% above CP and offers a discount of 25%. What is the profit percentage?

**Solution**

Assume CP = ₹100.

- MP = ₹180.
- SP = ₹180 × 0.75 = ₹135.
- Profit = ₹35.

**Shortcut:**

$$
\frac{SP}{CP}=1.8\times0.75=1.35
$$

**Answer: 35% profit.**

### Q21. Same selling price, one gain and one loss

A trader sells two articles for ₹1,200 each. He gains 20% on the first and loses 20% on the second. Find his total loss.

**Solution**

$$
CP_1=\frac{1200}{1.2}=₹1,000
$$

$$
CP_2=\frac{1200}{0.8}=₹1,500
$$

Total CP = ₹2,500; total SP = ₹2,400. Loss = ₹100.

$$
\text{Loss}\%=\frac{100}{2500}\times100=4\%
$$

**Shortcut — equal SP and equal gain/loss rate:**

$$
\text{Loss}\%=\frac{20^2}{100}=4\%
$$

**Answer: ₹100 loss, or 4%.**

### Q22. Different quantities sold at different rates

A person purchases 100 articles for ₹80 each. He sells 60 articles at 25% profit and the remaining at 10% loss. Find total profit percentage.

**Solution**

Total CP = 100 × ₹80 = ₹8,000.

First 60 articles:

$$
CP_1=60\times80=₹4,800
$$

$$
SP_1=4800\times1.25=₹6,000
$$

Remaining 40 articles:

$$
CP_2=40\times80=₹3,200
$$

$$
SP_2=3200\times0.9=₹2,880
$$

Total SP = ₹8,880. Profit = ₹880.

$$
\text{Profit}\%=\frac{880}{8000}\times100=11\%
$$

**Shortcut — weighted average, since CP per article is uniform:**

$$
0.60(25\%)+0.40(-10\%)=15\%-4\%=11\%
$$

**Answer: 11% profit.**

### Q23. Equivalent single discount

A shopkeeper gives two successive discounts of 15% and 20%. Find the single equivalent discount.

**Solution**

$$
\text{Price factor}=0.85\times0.80=0.68
$$

The customer pays 68% of MP, so the discount is 32%.

**Shortcut:**

$$
D=15+20-\frac{15\times20}{100}=32\%
$$

**Answer: 32%.**

### Q24. Required markup after discount

A trader wants to earn 30% profit after offering a 20% discount. By what percentage should MP exceed CP?

**Solution**

Assume CP = ₹100. Required SP = ₹130.

$$
130=0.8MP
$$

$$
MP=\frac{130}{0.8}=₹162.50
$$

Markup = ₹62.50, so markup percentage = 62.5%.

**Shortcut:**

$$
\frac{MP}{CP}=\frac{1.30}{0.80}=1.625
$$

**Answer: 62.5% markup.**

## Level 4 — Challenge

### Q25. Dishonest dealer: loss on price, gain through short weight

A dishonest dealer sells goods at 10% loss but uses a weight that is 20% less than the stated weight. Find actual profit/loss percentage.

**Solution**

Assume the cost of 1 kg is ₹100.

At 10% loss on the stated 1 kg, the dealer collects:

$$
SP=100\times0.9=₹90
$$

But he supplies only 800 g. The actual cost of 800 g is:

$$
CP_{\text{actual}}=100\times0.8=₹80
$$

Actual profit = ₹90 − ₹80 = ₹10.

$$
\text{Actual profit}\%=\frac{10}{80}\times100=12.5\%
$$

**Shortcut — compare revenue with actual cost:**

$$
\frac{SP}{CP_{\text{actual}}}=\frac{0.9}{0.8}=1.125
$$

**Answer: 12.5% actual profit.**

**Trap:** The 10% loss is on the stated quantity's price. Actual cost is for the smaller quantity supplied.

### Q26. Changed CP and changed SP

A shopkeeper sells an article at 10% profit. If he had purchased it at 10% less and sold it for ₹20 less, his profit would have been 20%. Find original CP.

**Solution**

Let original CP = x. Original SP = 1.1x.

New CP = 0.9x. New SP = 1.1x − 20.

The new profit is 20% on the new CP:

$$
1.1x-20=1.2(0.9x)
$$

$$
1.1x-20=1.08x
$$

$$
0.02x=20\Rightarrow x=\boxed{₹1,000}
$$

**Shortcut — compare both SPs as percentages of original CP:**

New SP = 120% × 90% = 108% of original CP. Original SP = 110%. Difference = 2% of original CP = ₹20.

$$
CP=\frac{20\times100}{2}=₹1,000
$$

**Answer: ₹1,000.**

### Q27. Different portions of stock sold at different rates

A trader sells 40% of his stock at 20% profit, 30% at 10% loss and the remaining at 15% profit. Find overall profit percentage, assuming uniform CP per unit.

**Solution — weighted average**

$$
0.40(20\%)+0.30(-10\%)+0.30(15\%)
$$

$$
=8\%-3\%+4.5\%=9.5\%
$$

**Verification:** Assume total CP = ₹100.

| Portion | CP | Profit/loss | SP |
|---|---:|---:|---:|
| 40% | ₹40 | +₹8 | ₹48 |
| 30% | ₹30 | −₹3 | ₹27 |
| 30% | ₹30 | +₹4.50 | ₹34.50 |
| **Total** | **₹100** | **+₹9.50** | **₹109.50** |

**Answer: 9.5% profit.**

**Shortcut condition:** Weighted average by stock percentage is valid here because CP per unit is uniform.

### Q28. Discount offered but profit maintained

A trader offers 20% discount on MP and still earns 25% profit. Find markup percentage over CP.

**Solution**

Assume CP = ₹100. For 25% profit, SP = ₹125.

$$
125=0.8MP
$$

$$
MP=\frac{125}{0.8}=₹156.25
$$

Markup = ₹56.25, so markup percentage = 56.25%.

**Shortcut:**

$$
\frac{MP}{CP}=\frac{1.25}{0.8}=1.5625
$$

**Answer: 56.25% markup.**

### Q29. Changed CP and SP with a new profit rate

A shopkeeper sells an article at 20% profit. If he had bought it at 20% less and sold it for ₹10 less, he would have earned 40% profit. Find original CP.

**Solution**

Let original CP = x. Original SP = 1.2x.

New CP = 0.8x. New SP = 1.2x − 10.

$$
1.2x-10=1.4(0.8x)
$$

$$
1.2x-10=1.12x
$$

$$
0.08x=10\Rightarrow x=\boxed{₹125}
$$

**Shortcut — compare percentages of original CP:**

New SP = 140% × 80% = 112% of original CP. Original SP = 120%. Difference = 8% of original CP = ₹10.

$$
CP=\frac{10\times100}{8}=₹125
$$

**Answer: ₹125.**

### Q30. Same selling price, 25% gain and 25% loss

A seller sells two articles at the same selling price. He gains 25% on one and loses 25% on the other. Find overall loss percentage.

**Shortcut — equal SP and equal gain/loss rate:**

$$
\text{Overall loss}\%=\frac{x^2}{100}
=\frac{25^2}{100}=6.25\%
$$

**Traditional verification:** Assume SP of each article = ₹100.

$$
CP_1=\frac{100}{1.25}=₹80
$$

$$
CP_2=\frac{100}{0.75}=₹133.333\ldots
$$

Total CP = ₹213.333… and total SP = ₹200. Therefore, the overall loss is 6.25%.

**Answer: 6.25% loss.**

**Trap:** This shortcut applies because the selling prices are equal. It is not a general formula for equal cost prices.

## Quick answer key

| Question | Final answer |
|---|---:|
| 17 | MP = ₹1,000 |
| 18 | CP = ₹1,000 |
| 19 | Original CP = ₹500 |
| 20 | 35% profit |
| 21 | ₹100 loss; 4% loss |
| 22 | 11% profit |
| 23 | 32% equivalent discount |
| 24 | 62.5% markup |
| 25 | 12.5% actual profit |
| 26 | Original CP = ₹1,000 |
| 27 | 9.5% profit |
| 28 | 56.25% markup |
| 29 | Original CP = ₹125 |
| 30 | 6.25% loss |
<!-- /CAT-UPDATE-ID: 684ef58cf7b32232 -->

## Related notes

- [[Percentages]]
- [[Successive Percentage Change]]
