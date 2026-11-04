---
title: "Mixtures & Alligation"
---

# Mixtures & Alligation

> [!note] Topic workspace
> Add your concept notes, solved examples, CAT-level practice, shortcuts and mistakes here.

## Concepts

<!-- CAT-UPDATE-ID: d2649d91f0a1d425 -->
### Mixtures and weighted averages

A mixture combines two or more components. If the quantities are measured on a common additive basis, the mixture's value or concentration is a weighted average of the component values.

For two components:

$$
\text{Mean value}=\frac{q_1v_1+q_2v_2}{q_1+q_2}
$$

where q represents quantity and v represents price, concentration or another comparable measure.

### Alligation — the cross method

Alligation is a shortcut for finding the ratio in which two components must be mixed to obtain a target mean.

**Example:** Rice costing ₹40/kg and ₹60/kg is mixed to obtain a mixture worth ₹45/kg.

Traditional equation, with cheaper and dearer quantities x and y:

$$
\frac{40x+60y}{x+y}=45
$$

$$
40x+60y=45x+45y
$$

$$
15y=5x\Rightarrow x:y=3:1
$$

**Shortcut — cross differences**

$$
\boxed{\text{Cheaper : Dearer}=(\text{Dearer}-\text{Mean}):(\text{Mean}-\text{Cheaper})}
$$

$$
=(60-45):(45-40)=15:5=\boxed{3:1}
$$

The cross-differences are paired with the opposite component: the cheaper quantity is paired with (dearer − mean).

Use alligation for two components with different prices, concentrations or averages. For a positive two-component mixture, the target mean must lie between the two component values.

### Dilution — constant-solute method

When water is added to an alcohol or salt solution, the amount of solute remains constant, assuming no spillage or chemical reaction.

**Example:** A 40-litre solution contains 25% alcohol. How much water must be added to reduce the concentration to 20%?

Initial alcohol:

$$
40\times\frac{25}{100}=10\text{ L}
$$

At 20% concentration, 10 L must be 20% of the final volume:

$$
\text{Final volume}=\frac{10}{0.20}=50\text{ L}
$$

Water added:

$$
50-40=\boxed{10\text{ L}}
$$

**Shortcut:** Find the solute quantity, keep it unchanged, calculate the final total from the required concentration, then subtract the initial volume.

### Repeated replacement

If a container initially holds a pure liquid, and a fixed volume is removed and replaced with another liquid, the original liquid's fraction is multiplied by the same retention factor at every operation.

The original liquid remaining after n operations is:

$$
\boxed{V\left(1-\frac{x}{V}\right)^n}
$$

where:
- V = container volume,
- x = volume removed and replaced each time,
- n = number of operations.

This assumes thorough mixing before each removal and that the container is restored to volume V after every replacement.
<!-- /CAT-UPDATE-ID: d2649d91f0a1d425 -->

## Formulas / rules

<!-- CAT-UPDATE-ID: 280e1516fe441ab0 -->
### Formula sheet

| Situation | Formula |
|---|---|
| Two-component mixture mean | (q₁v₁ + q₂v₂)/(q₁ + q₂) |
| Alligation, cheaper : dearer | (Dearer − Mean) : (Mean − Cheaper) |
| Dilution with water | Solute quantity remains constant |
| Final volume after dilution | Solute quantity ÷ required concentration |
| Repeated replacement | V(1 − x/V)ⁿ |

### Adding pure solute

If a solution has initial total quantity M and solute fraction c, and x units of pure solute are added on the same mass/additive basis, then:

$$
\frac{cM+x}{M+x}=r
$$

where r is the required final concentration.

**Important:** Keep units consistent. For a physical salt solution, concentration is normally mass-based. A statement that gives the solution in litres but asks for a mass of solid salt to be added is incomplete unless density or an intended aptitude-test convention is specified.
<!-- /CAT-UPDATE-ID: 280e1516fe441ab0 -->

## Worked examples

<!-- CAT-UPDATE-ID: 4686e823b3f08ebc -->
### Example 1 — Rice alligation

Rice costing ₹40/kg and ₹60/kg is mixed to obtain a mixture worth ₹45/kg. Find the ratio of cheaper to dearer rice.

$$
\text{Cheaper : Dearer}=(60-45):(45-40)
$$

$$
=15:5=\boxed{3:1}
$$

### Example 2 — Dilution by adding water

A 40-litre solution contains 25% alcohol. How much water must be added to make it 20% alcohol?

Alcohol quantity remains:

$$
40\times0.25=10\text{ L}
$$

Final volume:

$$
10/0.20=50\text{ L}
$$

Water added:

$$
50-40=\boxed{10\text{ L}}
$$

### Example 3 — Repeated replacement

A 100-litre container contains milk. Twenty litres are removed and replaced with water. This process is repeated three times. Find the milk remaining.

Fraction of milk retained in one operation:

$$
1-\frac{20}{100}=\frac45
$$

After three operations:

$$
100\left(\frac45\right)^3
=100\times\frac{64}{125}
=\boxed{51.2\text{ litres}}
$$

**Shortcut:** Repeated replacement is multiplication, not repeated subtraction. Multiply the original quantity by the retention fraction raised to the number of operations.

### Example 4 — Tea alligation

A shopkeeper mixes tea costing ₹400/kg and ₹600/kg to obtain a mixture worth ₹480/kg. Find the ratio of cheaper to dearer tea.

$$
\text{Cheaper : Dearer}=(600-480):(480-400)
$$

$$
=120:80=\boxed{3:2}
$$

**Interpretation:** The mean is ₹80 above the cheaper tea price and ₹120 below the dearer price. The cheaper tea must therefore be used in the larger quantity.
<!-- /CAT-UPDATE-ID: 4686e823b3f08ebc -->

## Common traps

<!-- CAT-UPDATE-ID: 55508df6c4bea73f -->
- **Alligation order:** Cross-differences are paired with the opposite component. Cheaper quantity = dearer − mean.
- **Target mean:** For a positive two-component mixture, the target mean must lie between the component values.
- **Weighted average:** Do not take the simple average unless the component quantities are equal.
- **Dilution:** Adding water changes the total volume and concentration, but not the amount of solute.
- **Repeated replacement:** Each removal takes out some of the original liquid and some replacement liquid. Do not subtract x litres of original liquid on every round.
- **Mixing assumption:** The repeated-replacement formula requires thorough mixing before each removal.
- **Unit consistency:** Do not mix litres and kilograms in one equation without density or a clearly stated exam convention.
- **Chemical reactions or losses:** Simple alligation and dilution shortcuts do not account for reactions, evaporation, spillage or non-additive volume changes.
<!-- /CAT-UPDATE-ID: 55508df6c4bea73f -->

## Practice and mistakes

<!-- CAT-UPDATE-ID: 4a60ebb237b6122f -->
### CAT practice — detailed solutions

### Question 23 — Repeated replacement

**Question:** A 100-litre container contains milk. Twenty litres are removed and replaced with water. This process is repeated three times. Find the quantity of milk remaining.

**Step 1: Fraction retained in one operation**

$$
1-\frac{20}{100}=\frac45
$$

**Step 2: Apply the retention factor three times**

$$
\text{Milk remaining}=100\left(\frac45\right)^3
$$

$$
=100\times\frac{64}{125}=\boxed{51.2\text{ litres}}
$$

**Shortcut:** Multiply the original quantity by the retention fraction raised to the number of operations.

**Answer: 51.2 litres of milk.**

### Question 27 — Alligation

**Question:** A shopkeeper mixes two varieties of tea costing ₹400/kg and ₹600/kg to obtain a mixture worth ₹480/kg. Find the ratio of cheaper tea to dearer tea.

**Traditional method:** Let the quantities be x and y kg.

$$
\frac{400x+600y}{x+y}=480
$$

$$
400x+600y=480x+480y
$$

$$
120y=80x\Rightarrow x:y=3:2
$$

**Shortcut — alligation**

$$
\text{Cheaper : Dearer}=(600-480):(480-400)
$$

$$
=120:80=\boxed{3:2}
$$

**Answer: 3 : 2.**

### Question 29 — Adding pure salt

**Question as supplied:** A vessel contains 80 litres of a 25% salt solution. How much pure salt should be added to make the solution 40% salt?

> [!warning] Unit issue in the question
> A litre is a volume unit, while pure salt is normally measured by mass. A physically precise question needs density information or should state the solution and added salt in compatible mass units. The standard CAT-style algebra below assumes the quantities are on a common additive basis.

**Step 1: Initial salt quantity under the intended convention**

$$
80\times\frac{25}{100}=20
$$

**Step 2: Let x be the quantity of pure salt added**

The salt quantity becomes 20 + x and the total mixture becomes 80 + x.

$$
\frac{20+x}{80+x}=\frac{40}{100}
$$

**Step 3: Solve**

$$
20+x=32+0.4x
$$

$$
0.6x=12
$$

$$
x=\boxed{20}
$$

**Answer under the common additive-quantity convention: 20 units.**

For a physically consistent version, state: “A vessel contains 80 kg of a 25% salt solution. How much pure salt by mass must be added to make the mixture 40% salt?” Under that version, the answer is **20 kg**.

## Answer key

| Question | Answer |
|---:|---|
| 23 | 51.2 litres of milk |
| 27 | 3 : 2 |
| 29 | 20 units under the stated additive-quantity convention; 20 kg if the initial solution is 80 kg |
<!-- /CAT-UPDATE-ID: 4a60ebb237b6122f -->

## Related notes

<!-- CAT-UPDATE-ID: 0f63f0745fb61744 -->
- [[Averages]]
- [[Ratios & Proportions]]
- [[Percentages]]
<!-- /CAT-UPDATE-ID: 0f63f0745fb61744 -->
