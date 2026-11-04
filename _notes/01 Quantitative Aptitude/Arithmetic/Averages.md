---
title: "Averages"
destination: "01 Quantitative Aptitude/Arithmetic/Averages.md"
subject: Quantitative Aptitude
topic: Arithmetic
subtopic: Averages
tags:
  - CAT
  - Quantitative-Aptitude
  - Arithmetic
  - Averages
---

# Averages

## Concepts

<!-- CAT-UPDATE-ID: 6bcf9af71495d346 -->
### Average as equal sharing

The arithmetic average is the sum of the observations divided by their count:

$$
\text{Average}=\frac{\text{Sum of observations}}{\text{Number of observations}}
$$

Rearranging:

$$
\text{Total}=\text{Average}\times\text{Number of observations}
$$

The total-sum method is useful when observations are added to or removed from a group.

> [!abstract] Core idea
> Convert an average into a total, update the total and count, and then calculate the new average.

### Average adjustment

When one value is added to a group, adjust the old average by the difference between the new value and the old average.

**Example:** The average of 8 numbers is 25. A ninth number, 34, is added.

Original total:

$$
8\times25=200
$$

New total:

$$
200+34=234
$$

New average:

$$
\frac{234}{9}=\boxed{26}
$$

**Shortcut — average adjustment**

$$
\boxed{\text{New average}=\text{Old average}+\frac{\text{New value}-\text{Old average}}{\text{New count}}}
$$

$$
25+\frac{34-25}{9}=\boxed{26}
$$

The denominator is the new group size.

### Deviation method

Instead of adding large values, choose a convenient assumed average and add the deviations from it.

**Example:** Find the average of 48, 52, 55, 60 and 65. Assume 50.

| Number | Deviation from 50 |
|---:|---:|
| 48 | −2 |
| 52 | +2 |
| 55 | +5 |
| 60 | +10 |
| 65 | +15 |
| **Total** | **+30** |

Therefore:

$$
\text{Actual average}=50+\frac{30}{5}=\boxed{56}
$$

**General formula**

$$
\boxed{\text{Actual average}=\text{Assumed average}+\frac{\text{Sum of deviations}}{n}}
$$

Choose an assumed average close to the given values to keep the deviations small.
<!-- /CAT-UPDATE-ID: 6bcf9af71495d346 -->

## Average adjustment

When one value is added to a group, adjust the old average by the difference between the new value and the old average.

**Example:** The average of 8 numbers is 25. A ninth number, 34, is added.

Original total: $$8\\times25=200$$

New total: $$200+34=234$$

New average: $$234/9=\\boxed{26}$$

**Shortcut — average adjustment**

$$\\boxed{\\text{New average}=\\text{Old average}+\\frac{\\text{New value}-\\text{Old average}}{\\text{New count}}}$$

$$25+\\frac{34-25}{9}=\\boxed{26}$$

The denominator is the new group size.

## Deviation method

Choose a convenient assumed average, then add the deviations from it.

**Example:** Find the average of 48, 52, 55, 60 and 65. Assume 50.

| Number | Deviation from 50 |
|---:|---:|
| 48 | −2 |
| 52 | +2 |
| 55 | +5 |
| 60 | +10 |
| 65 | +15 |
| **Total** | **+30** |

$$\\text{Actual average}=50+\\frac{30}{5}=\\boxed{56}$$

**General formula**

$$\\boxed{\\text{Actual average}=\\text{Assumed average}+\\frac{\\text{Sum of deviations}}{n}}$$

Choose an assumed average close to the given values to keep deviations small.

## Alligation — the cross method

Alligation finds the mixing ratio of two components when their values and the desired mean are known.

**Example:** Rice costing ₹40/kg and ₹60/kg is mixed to obtain a mixture worth ₹45/kg.

Traditional equation, with quantities x and y:

$$\\frac{40x+60y}{x+y}=45$$

$$40x+60y=45x+45y$$

$$15y=5x\\Rightarrow x:y=3:1$$

**Shortcut — cross differences**

$$\\boxed{\\text{Cheaper : Dearer}=(\\text{Dearer}-\\text{Mean}):(\\text{Mean}-\\text{Cheaper})}$$

$$=(60-45):(45-40)=15:5=\\boxed{3:1}$$

Use alligation for two components with different prices, concentrations or averages. The target mean must lie between the two component values for a positive mixing ratio. Do not use the simple cross method blindly when there are additional losses, reactions, non-additive quantities, multiple stages or more than two components.

## Dilution — constant-solute method

When water is added to an alcohol or salt solution, the amount of solute remains constant, assuming no spillage or reaction.

**Example:** A 40-litre solution contains 25% alcohol. How much water must be added to reduce the concentration to 20%?

Initial alcohol:

$$40\\times\\frac{25}{100}=10\\text{ L}$$

At 20% concentration, 10 L must be 20% of the final volume:

$$\\text{Final volume}=\\frac{10}{0.20}=50\\text{ L}$$

Water added:

$$50-40=\\boxed{10\\text{ L}}$$

**Shortcut:** Find the solute quantity first, keep it unchanged, calculate the final total from the required concentration, then subtract the initial volume.

## Repeated replacement

If a container initially holds a pure liquid, and a fixed volume is removed and replaced with another liquid, the original liquid's fraction is multiplied by the same retention factor at every operation.

$$\\boxed{\\text{Original liquid remaining}=V\\left(1-\\frac{x}{V}\\right)^n}$$

where V is the container volume, x is the volume removed and replaced each time, and n is the number of operations.

The formula assumes thorough mixing before each removal and that the container is restored to volume V after every replacement.

## Average speed

Average speed is always:

$$\\boxed{\\text{Average speed}=\\frac{\\text{Total distance}}{\\text{Total time}}}$$

It is not automatically the arithmetic mean of the speeds.

### Equal distances

For two equal-distance journeys at speeds u and v:

$$\\boxed{\\text{Average speed}=\\frac{2uv}{u+v}}$$

This is the harmonic mean.

**Example:** A car travels 60 km at 30 km/h and another 60 km at 60 km/h.

$$t_1=60/30=2\\text{ h},\\qquad t_2=60/60=1\\text{ h}$$

$$\\text{Average speed}=120/(2+1)=\\boxed{40\\text{ km/h}}$$

### Equal times

If a vehicle travels for equal amounts of time at speeds u and v:

$$\\boxed{\\text{Average speed}=\\frac{u+v}{2}}$$

This is the arithmetic mean. Identify whether distance or time is equal before choosing a shortcut.
<!-- /CAT-UPDATE-ID: 9166c0bc7c561b93 -->

## Formulas / rules

<!-- CAT-UPDATE-ID: 36f5eb381c077685 -->
### Core average formulas

$$
\text{Average}=\frac{\text{Total}}{\text{Number of observations}}
$$

$$
\text{Total}=\text{Average}\times\text{Number of observations}
$$

### When a new observation joins

If n observations have average A and a new value x joins:

$$
\text{New average}=\frac{nA+x}{n+1}
$$

Equivalent adjustment form:

$$
\boxed{\text{New average}=A+\frac{x-A}{n+1}}
$$

If the average remains unchanged:

$$
\frac{nA+x}{n+1}=A\Rightarrow x=A
$$

Thus, if one new observation joins without changing the average, that observation must equal the old average.

### Deviation formula

$$
\boxed{\text{Actual average}=\text{Assumed average}+\frac{\sum \text{deviations}}{n}}
$$
<!-- /CAT-UPDATE-ID: 36f5eb381c077685 -->

## Quick formula sheet

| Situation | Formula |
|---|---|
| Average | Total of observations ÷ number of observations |
| Total | Average × number of observations |
| Add x to n observations with old average A | New average = A + (x − A)/(n + 1) |
| Deviation method | Actual average = assumed average + (sum of deviations ÷ n) |
| Alligation, cheaper : dearer | (Dearer − mean) : (Mean − cheaper) |
| Dilution | Solute quantity remains constant |
| Repeated replacement | Original liquid remaining = V(1 − x/V)^n |
| Equal-distance average speed | 2uv/(u + v) |
| Equal-time average speed | (u + v)/2 |

**CAT decision rule:** Identify what remains constant—total, deviation balance, solute quantity, original-liquid fraction, distance or time. The appropriate shortcut usually follows from that invariant.
<!-- /CAT-UPDATE-ID: b458c53b75f456a7 -->

## Worked examples

<!-- CAT-UPDATE-ID: efa9792632e7d6ed -->
### Example 1 — Average adjustment

The average of 8 numbers is 25. If one more number, 34, is added, find the new average.

**Traditional method**

Original total:

$$
8\times25=200
$$

New total:

$$
200+34=234
$$

New average:

$$
\frac{234}{9}=\boxed{26}
$$

**Shortcut**

$$
25+\frac{34-25}{9}=\boxed{26}
$$

### Example 2 — Average remains unchanged

The average of 10 students is 60. A new student joins without changing the average. Find the new student's marks.

**Traditional method**

Original total:

$$
10\times60=600
$$

New total for 11 students at the same average:

$$
11\times60=660
$$

New student's marks:

$$
660-600=\boxed{60}
$$

**Shortcut:** If adding one value leaves the average unchanged, the added value must equal the old average.

### Example 3 — Deviation method

Find the average of 48, 52, 55, 60 and 65.

Assume 50. The deviations are −2, +2, +5, +10 and +15. Their sum is +30.

$$
\text{Average}=50+\frac{30}{5}=\boxed{56}
$$
<!-- /CAT-UPDATE-ID: efa9792632e7d6ed -->

## Worked examples — mixture and average-speed applications

### Adding water to a solution

A 40-litre solution contains 25% alcohol. Find the water required to make it 20%.

$$\\text{Alcohol}=40\\times0.25=10\\text{ L}$$

$$\\text{Final volume}=10/0.20=50\\text{ L}$$

$$\\text{Water added}=50-40=\\boxed{10\\text{ L}}$$

**Shortcut insight:** Water changes total volume and concentration, but not the amount of alcohol.

### Equal-distance versus equal-time journeys

For equal distances, more time is spent at the lower speed, so use the harmonic mean. For equal times, more distance is covered at the higher speed, so use the arithmetic mean. Always identify the condition before applying a formula.
<!-- /CAT-UPDATE-ID: 301904aeb5f0f651 -->

## Common traps

<!-- CAT-UPDATE-ID: f8ce93ac22eca3af -->
- **Do not confuse average with total.** A change in the average does not directly tell you the change in the total unless the group size is known.
- **Update the count.** When one observation joins n existing observations, the new count is n + 1.
- **Use the new group size** in the average-adjustment shortcut.
- **Deviation signs matter.** Values below the assumed average have negative deviations; values above it have positive deviations.
- **Average unchanged does not mean total unchanged.** If one observation joins, the total rises by exactly the old average.
- **Choose a convenient assumed average** to keep deviations small and calculations quick.
<!-- /CAT-UPDATE-ID: f8ce93ac22eca3af -->

## Common CAT traps

- **Wrong denominator in average adjustment:** after adding one observation, divide the revised total by n + 1.
- **Deviation signs:** values below the assumed average have negative deviations; values above it have positive deviations.
- **Alligation order:** cross-differences give the opposite component's quantity. Cheaper quantity is paired with (dearer − mean).
- **Alligation validity:** for a positive two-component mixture, the target mean must lie between the component values.
- **Dilution:** adding water does not change the amount of alcohol or salt already present.
- **Repeated replacement:** every removal takes out some of the original liquid and some replacement liquid. Do not subtract x litres of original liquid each round.
- **Mixing assumption:** repeated-replacement formula requires thorough mixing before each removal.
- **Average speed:** use total distance ÷ total time. Equal distances call for the harmonic mean; equal times call for the arithmetic mean.
- **Units:** keep distance, time, speed, volume and concentration units consistent.
- **Salt added to solution:** aptitude questions may assume additive quantities. In a physical mixture, salt is measured by mass and density/volume effects may matter; follow the question's intended convention.
<!-- /CAT-UPDATE-ID: 5b5d7846f8caa02e -->

## Practice and mistakes

<!-- CAT-UPDATE-ID: fd9f373d14987dff -->
- [ ] I can convert an average into a total.
- [ ] I update the observation count when a value joins or leaves.
- [ ] I can use the average-adjustment shortcut.
- [ ] I can identify the new value when the average remains unchanged.
- [ ] I can use positive and negative deviations correctly.
<!-- /CAT-UPDATE-ID: fd9f373d14987dff -->

## CAT practice — detailed solutions and shortcuts

### Question 23 — Repeated replacement

**Question:** A 100-litre container contains milk. Twenty litres are removed and replaced with water. This process is repeated three times. Find the quantity of milk remaining.

**Step 1: Fraction retained in one operation**

$$1-\\frac{20}{100}=\\frac45$$

**Step 2: Apply the retention factor three times**

$$\\text{Milk remaining}=100\\left(\\frac45\\right)^3$$

$$=100\\times\\frac{64}{125}=\\boxed{51.2\\text{ litres}}$$

**Shortcut:** Repeated replacement is multiplication, not repeated subtraction. Multiply the original quantity by the retention fraction raised to the number of operations.

**Answer: 51.2 litres of milk.**

### Question 25 — Average speed over two journeys

**Question:** A car travels 40 km at 40 km/h and another 80 km at 80 km/h. Find its average speed.

**Step 1: Calculate each time**

$$t_1=40/40=1\\text{ hour}$$

$$t_2=80/80=1\\text{ hour}$$

**Step 2: Total distance and time**

$$D=40+80=120\\text{ km},\\qquad T=1+1=2\\text{ hours}$$

**Step 3: Average speed**

$$\\frac{120}{2}=\\boxed{60\\text{ km/h}}$$

**Shortcut:** The durations are equal, so use the arithmetic mean:

$$\\frac{40+80}{2}=\\boxed{60\\text{ km/h}}$$

**Trap:** The distances are unequal, so do not use the equal-distance harmonic-mean formula.

### Question 27 — Alligation

**Question:** A shopkeeper mixes two varieties of tea costing ₹400/kg and ₹600/kg to obtain a mixture worth ₹480/kg. Find the ratio of cheaper tea to dearer tea.

**Traditional method:** Let the quantities be x and y kg.

$$\\frac{400x+600y}{x+y}=480$$

$$400x+600y=480x+480y$$

$$120y=80x\\Rightarrow x:y=3:2$$

**Shortcut — alligation**

$$\\text{Cheaper : Dearer}=(600-480):(480-400)$$

$$=120:80=\\boxed{3:2}$$

**Answer: 3 : 2.**

**Interpretation:** The mean is ₹80 above the cheaper tea price and ₹120 below the dearer price. The cheaper tea must therefore be used in the larger quantity.

### Question 29 — Adding pure salt

**Question:** A vessel contains 80 litres of a 25% salt solution. How much pure salt should be added to make the solution 40% salt?

**Modelling note:** The standard aptitude treatment assumes the added salt quantity and solution quantity are measured on a common additive basis. Strictly, salt is measured by mass, and a physical volume-based problem would need density information. The calculation below follows the usual textbook percentage-mixture convention.

**Step 1: Initial salt quantity**

$$80\\times\\frac{25}{100}=20$$

**Step 2: Let x be the quantity of pure salt added**

The salt quantity becomes 20 + x and the total mixture becomes 80 + x.

$$\\frac{20+x}{80+x}=\\frac{40}{100}$$

**Step 3: Solve**

$$20+x=32+0.4x$$

$$0.6x=12$$

$$x=\\boxed{20}$$

**Answer: 20 units of pure salt under the additive-quantity convention.**

**Shortcut insight:** Added pure salt increases both the salt quantity and the total quantity. Therefore, x must appear in both numerator and denominator. Do not simply calculate 40% of 80.

### Question 30 — Equal halves of a journey

**Question:** A person travels half of a journey at 30 km/h and the other half at 60 km/h. Find the average speed for the entire journey.

**Step 1: Identify the condition**

The distances are equal, not the times. Use the harmonic mean.

**Step 2: Apply the shortcut**

$$\\text{Average speed}=\\frac{2uv}{u+v}$$

$$=\\frac{2\\times30\\times60}{30+60}=\\boxed{40\\text{ km/h}}$$

**Traditional verification:** Assume the total journey is 120 km, so each half is 60 km.

$$t_1=60/30=2\\text{ hours},\\qquad t_2=60/60=1\\text{ hour}$$

$$\\text{Average speed}=120/(2+1)=\\boxed{40\\text{ km/h}}$$

**Answer: 40 km/h.**

**Trap:** Do not use (30 + 60)/2 = 45 km/h. The arithmetic mean applies to equal-time travel, not equal-distance travel.

## Answer key

| Question | Answer |
|---:|---|
| 23 | 51.2 litres of milk |
| 25 | 60 km/h |
| 27 | 3 : 2 |
| 29 | 20 units of pure salt under the additive-quantity convention |
| 30 | 40 km/h |
<!-- /CAT-UPDATE-ID: c7e4e026e2dc1b59 -->

## Related notes

<!-- CAT-UPDATE-ID: a2a77200c7538b23 -->
- [[Ratios & Proportions]]
- [[Mixtures & Alligation]]
- [[Time, Speed & Distance]]
<!-- /CAT-UPDATE-ID: a2a77200c7538b23 -->
