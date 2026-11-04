---
title: "Ratios & Proportions"
destination: "01 Quantitative Aptitude/Arithmetic/Ratios & Proportions.md"
subject: Quantitative Aptitude
topic: Arithmetic
subtopic: Ratios & Proportions
tags:
  - CAT
  - Quantitative-Aptitude
  - Arithmetic
  - Ratios
---

# Ratios & Proportions

## Concepts

### Meaning of a ratio

A ratio compares two quantities of the same kind by division. A:B represents A/B. A ratio of 3:2 means that for every 3 equal parts assigned to A, 2 equal parts are assigned to B.

> [!abstract] Core idea
> Convert percentage statements into an equation, then isolate the required ratio in the requested order.

<!-- CAT-UPDATE-ID: 68934b2c2c1bdd2d -->
### 1. Assume parts — the universal ratio technique

If A:B = 3:5, assume A = 3x and B = 5x. The common multiplier x converts a ratio into actual quantities.

**Example: Boys and girls**

The ratio of boys to girls is 3:5 and the class has 64 students.

Let boys = 3x and girls = 5x.

$$
3x+5x=64\Rightarrow 8x=64\Rightarrow x=8
$$

Boys = 3 × 8 = 24. Girls = 5 × 8 = 40.

**Shortcut:** Add ratio parts, divide the total by their sum to find one part, then multiply each term by that value.

### 2. Ratio transformations

Suppose A:B = 3:4. A increases by 20%, while B decreases by 25%.

$$
A'=3x\times1.2=3.6x
$$

$$
B'=4x\times0.75=3x
$$

$$
A':B'=3.6:3=\boxed{6:5}
$$

**General shortcut:** If A:B = m:n, A changes by x% and B changes by y%, then:

$$
A':B'=m(100\pm x):n(100\pm y)
$$

Use + for an increase and − for a decrease. Simplify the resulting ratio.

### 3. Compound ratio

Suppose A:B = 2:3 and B:C = 4:5. Make the common term B equal.

$$
A:B=2:3=8:12
$$

$$
B:C=4:5=12:15
$$

Therefore:

$$
\boxed{A:B:C=8:12:15}
$$

**General shortcut:** If A:B = m:n and B:C = p:q, then:

$$
\boxed{A:B:C=mp:np:nq}
$$

### 4. Partnership — ratio applied to business

Partnership questions combine capital and the time for which it is invested.

$$
\boxed{\text{Profit share}\propto\text{Capital}\times\text{Time}}
$$

Calculate capital × investment duration for each partner, then form the ratio of those products.

**Example: Different capital and time**

A invests ₹10,000 for 12 months. B invests ₹15,000 for 8 months.

$$
A=10000\times12=120000
$$

$$
B=15000\times8=120000
$$

Therefore, A:B = 1:1.

| Partner | Capital | Time | Capital × Time |
|---|---:|---:|---:|
| A | ₹10,000 | 12 months | 120,000 |
| B | ₹15,000 | 8 months | 120,000 |

**Remember:** If capitals are equal, profit follows the time ratio. If durations are equal, profit follows the capital ratio.

#### Advanced partnership cases

**Example 1: A partner joins late**

A invests ₹20,000 for 12 months. B joins after 4 months with ₹30,000. B invests for only 8 months.

$$
A=20000\times12=240000
$$

$$
B=30000\times8=240000
$$

Profit ratio = 1:1.

**Example 2: Capital changes midway**

A invests ₹10,000 initially and increases it to ₹20,000 after 6 months. B invests ₹15,000 throughout the year.

$$
A=10000\times6+20000\times6=180000
$$

$$
B=15000\times12=180000
$$

Profit ratio = 1:1.

**Example 3: Working partner receives a salary**

A and B invest in the ratio 2:3. A receives ₹5,000 as salary for managing the business. The remaining profit is ₹25,000.

$$
A\text{'s investment share}=25000\times\frac25=₹10,000
$$

$$
B\text{'s investment share}=25000\times\frac35=₹15,000
$$

A's total receipt = ₹10,000 + ₹5,000 = ₹15,000. B receives ₹15,000.

**Important:** Divide the profit remaining after salary/commission according to the capital-time ratio. Add the salary/commission to the working partner's share afterward.
<!-- /CAT-UPDATE-ID: 68934b2c2c1bdd2d -->

## Formulas / rules

### Equality of percentages

If p% of A equals q% of B:

$$
\frac{pA}{100}=\frac{qB}{100}
$$

Therefore pA = qB, and:

$$
A:B=q:p
$$

<!-- CAT-UPDATE-ID: 8e301f4451f45b59 -->
### Ratio and partnership formula sheet

**Assume parts**

If A:B = m:n:

$$
A=mx,\qquad B=nx
$$

If A + B = T:

$$
x=\frac{T}{m+n}
$$

If A − B = D:

$$
x=\frac{D}{|m-n|}
$$

**Ratio transformation**

$$
A':B'=m(100\pm x):n(100\pm y)
$$

Use + for increase and − for decrease.

**Compound ratio**

$$
A:B=m:n,\quad B:C=p:q
$$

$$
A:B:C=mp:np:nq
$$

**Partnership**

$$
\text{Profit ratio}=C_1T_1:C_2T_2:\cdots
$$

If capital changes during the year:

$$
\text{Contribution}=\sum(\text{Capital in period}\times\text{Duration})
$$

If a working partner receives salary or commission, divide the residual profit by the capital-time ratio, then add that remuneration to the working partner's share.
<!-- /CAT-UPDATE-ID: 8e301f4451f45b59 -->

## Worked examples

### Q9. Ratio from an equality of percentages

**Question**

30% of A is equal to 45% of B. Find the ratio A:B.

**Solution**

$$
\frac{30}{100}A=\frac{45}{100}B
$$

$$
30A=45B
$$

$$
\frac{A}{B}=\frac{45}{30}=\frac{3}{2}
$$

> [!success] Final answer
> **A:B = 3:2.**

> [!tip] CAT shortcut
> If p% of A = q% of B, then A:B = q:p. The coefficients reverse when isolating A/B.

<!-- CAT-UPDATE-ID: cb6ec0a3e33c864c -->
### Example: Future ages using ratios

The present age ratio of A and B is 2:3. After 5 years, their age ratio becomes 3:4. Find their present ages.

Let present ages be 2x and 3x.

$$
\frac{2x+5}{3x+5}=\frac34
$$

$$
4(2x+5)=3(3x+5)
$$

$$
8x+20=9x+15\Rightarrow x=5
$$

Present ages:

- A = 2 × 5 = 10 years.
- B = 3 × 5 = 15 years.

**Answer: 10 years and 15 years.**

**Shortcut — age difference remains constant:** The initial age difference is 3x − 2x = x. Five years later, the ratio is 3:4, whose difference is one part. That future one-part difference must still equal x. Since A's future age is 2x + 5 = 3x, x = 5.
<!-- /CAT-UPDATE-ID: cb6ec0a3e33c864c -->

## Common traps

- Do not write A:B = 30:45; cross-multiply when isolating A/B.
- Preserve the requested order: A:B and B:A are reciprocals.
- Simplify the ratio to its lowest whole-number terms.

<!-- CAT-UPDATE-ID: 7325a46b00733d86 -->
### Common traps in ratio, age and partnership questions

- **A ratio is not an actual quantity.** Convert its terms into mx and nx before using totals or differences.
- **Apply percentage changes to the correct term.** An increase in A and a decrease in B require different multipliers.
- **For compound ratios, equalise the common term.** Do not add corresponding terms.
- **Age differences remain constant.** Both ages increase by the same number of years, but their ratio changes.
- **Partnership depends on capital × time**, not capital alone unless all partners invest for the same duration.
- **A late entrant invests for fewer months.** Count the actual investment duration.
- **When capital changes midway, split the timeline into periods** and add the capital-time products.
- **A working partner's salary is separate from investment-based profit division.** Divide residual profit first, then add salary/commission.
<!-- /CAT-UPDATE-ID: 7325a46b00733d86 -->

## Practice and mistakes

- [ ] I can convert percentage equalities into ratios.
- [ ] I preserve the requested order.
- [ ] I verify the ratio in the original equality.

## Related notes

- [[Percentages]]
- [[Averages]]
- [[Time & Work]]
