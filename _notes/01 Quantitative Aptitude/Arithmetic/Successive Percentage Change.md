---
title: Successive Percentage Change
destination: "01 Quantitative Aptitude/Arithmetic/Successive Percentage Change.md"
subject: Quantitative Aptitude
topic: Arithmetic
subtopic: Successive Percentage Change
tags:
  - CAT
  - Quantitative-Aptitude
  - Arithmetic
  - Percentages
---

# Successive Percentage Change

> [!abstract] Core idea
> For successive percentage changes, **convert each change into a multiplier and multiply the multipliers**. Do not simply add or subtract the percentages.

## 1. The multiplier method

| Change | Multiply by |
|---|---:|
| Increase by 10% | **1.10** |
| Increase by 20% | **1.20** |
| Decrease by 10% | **0.90** |
| Decrease by 25% | **0.75** |

**General rule**

- Increase by r%: multiplier = **1 + r/100**
- Decrease by r%: multiplier = **1 − r/100**

Multiply all the multipliers to get the final value as a fraction of the original.

## 2. Worked example

**Question:** A town's population increases by 10% in the first year, increases by 20% in the second year, and decreases by 25% in the third year. Find the overall percentage change.

> [!tip] Choose a convenient starting value
> Assume the initial population is **1,000**. This makes the arithmetic straightforward.

| Stage | Calculation | Population |
|---|---:|---:|
| Initial | — | **1,000** |
| Year 1: +10% | 1,000 × 1.10 | 1,100 |
| Year 2: +20% | 1,100 × 1.20 | 1,320 |
| Year 3: −25% | 1,320 × 0.75 | **990** |

**Find the net percentage change**

$$
\text{Percentage change}
=\frac{\text{Final}-\text{Initial}}{\text{Initial}}\times100
$$

$$
=\frac{990-1000}{1000}\times100=-1\%
$$

> [!success] Answer
> **1% decrease.**

### Shortcut: Multiply the factors

$$
1.10\times1.20\times0.75=0.99
$$

The final population is **99%** of the original.

$$
(0.99-1)\times100=-1\%
$$

**Answer: 1% decrease.**

## 3. Why adding the percentages is wrong

A common mistake is:

$$
10\%+20\%-25\%=5\%
$$

This is incorrect because every change is applied to the **updated value**, not always to the original value.

- Year 1's 10% is applied to 1,000.
- Year 2's 20% is applied to 1,100.
- Year 3's 25% decrease is applied to 1,320.

The multiplier method automatically handles these changing bases.

## 4. CAT shortcut: Same increase and decrease

If a value increases by x% and then decreases by x%, the changes do **not** cancel.

$$
\text{Net decrease}=\frac{x^2}{100}\%
$$

**Example: +20%, then −20%**

$$
1.20\times0.80=0.96
$$

The final value is **96%** of the original.

> [!important] Result
> **Net change: 4% decrease.**

## 5. General formula

For successive changes of a%, b%, c%, use positive values for increases and negative values for decreases.

$$
\text{Final value}
=\text{Initial value}
\left(1+\frac{a}{100}\right)
\left(1+\frac{b}{100}\right)
\left(1+\frac{c}{100}\right)
$$

$$
\boxed{
\text{Overall change (\%)}
=
\left[
\left(1+\frac{a}{100}\right)
\left(1+\frac{b}{100}\right)
\left(1+\frac{c}{100}\right)-1
\right]\times100
}
$$

- Product greater than 1 → overall increase.
- Product less than 1 → overall decrease.
- Product equal to 1 → no change.

## 6. Timed CAT-style practice

*These are original practice questions, not claimed previous-year CAT questions.*

### Q1. Reverse an increase

A number is increased by 40%. By what percentage must the increased number be decreased to return to the original number?

<small>Suggested time: 60 seconds</small>

**Solution**

Assume the original number is 100.

$$
100\times1.40=140
$$

Required decrease = 140 − 100 = **40**.

The decrease percentage is calculated on 140:

$$
\frac{40}{140}\times100
=\frac{2}{7}\times100
\approx28.57\%
$$

> [!success] Answer
> **28.57% decrease (approximately).**

> [!warning] CAT trap
> To reverse a 40% increase, do not decrease by 40%. The base is now 140, not 100.

### Q2. Equal increase and decrease

A quantity increases by 25% and then decreases by 25%. Find the overall percentage change.

**Solution**

$$
1.25\times0.75=0.9375
$$

The final value is **93.75%** of the original.

> [!success] Answer
> **6.25% decrease.**

### Q3. Two successive increases

The price of an item increases by 10% in one month and by 10% in the next month. Find the total percentage increase.

**Solution**

$$
1.10\times1.10=1.21
$$

The final price is **121%** of the original.

> [!success] Answer
> **21% increase.**

## 7. Quick revision

> [!summary] Remember this
> 1. Increase by r% → multiply by 1 + r/100.
> 2. Decrease by r% → multiply by 1 − r/100.
> 3. Multiply the factors in sequence.
> 4. Compare the final factor with 1 to find the net change.
>
> **Never add successive percentages blindly.**

## 8. Self-check

- [ ] I can convert an increase into a multiplier.
- [ ] I can convert a decrease into a multiplier.
- [ ] I know each change applies to the updated value.
- [ ] I can calculate the net percentage change.
- [ ] I can reverse a percentage increase correctly.
