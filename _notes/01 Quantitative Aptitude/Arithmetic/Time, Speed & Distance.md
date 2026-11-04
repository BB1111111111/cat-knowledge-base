---
title: "Time, Speed & Distance"
destination: "01 Quantitative Aptitude/Arithmetic/Time, Speed & Distance.md"
subject: Quantitative Aptitude
topic: Arithmetic
subtopic: Time, Speed & Distance
tags:
  - CAT
  - Quantitative-Aptitude
  - Arithmetic
  - Time-Speed-Distance
---

# Time, Speed & Distance

## Concepts

### Relationship between speed, distance and time

$$
S=\frac{D}{T}
$$

For a fixed distance, speed and time are inversely proportional. If speed increases, the time required to cover the same distance decreases.

> [!abstract] Core idea
> For a fixed distance, **speed × time = constant**.

<!-- CAT-UPDATE-ID: 5bfa2d5c45fe7e46 -->
### Average speed

Average speed is always total distance divided by total time:

$$
\boxed{\text{Average speed}=\frac{\text{Total distance}}{\text{Total time}}}
$$

It is not automatically the arithmetic mean of the speeds. The correct shortcut depends on whether the journey has equal distances or equal times.
<!-- /CAT-UPDATE-ID: 5bfa2d5c45fe7e46 -->

## Formulas / rules

### Constant distance

When distance remains unchanged:

$$
S_1T_1=S_2T_2
$$

If speed increases by x%, its multiplier is 1 + x/100. The time multiplier is the reciprocal:

$$
\frac{1}{1+x/100}
$$

The percentage decrease in time is:

$$
\frac{x}{100+x}\times100
$$

<!-- CAT-UPDATE-ID: 7a296d64d0c9f5f3 -->
### Average-speed shortcuts

**Two equal-distance journeys**

For two equal-distance journeys at speeds u and v:

$$
\boxed{\text{Average speed}=\frac{2uv}{u+v}}
$$

This is the harmonic mean.

**Two equal-time journeys**

If a vehicle travels for equal amounts of time at speeds u and v:

$$
\boxed{\text{Average speed}=\frac{u+v}{2}}
$$

This is the arithmetic mean.

**Decision rule:** Equal distances → harmonic mean. Equal times → arithmetic mean. If neither is equal, calculate total distance ÷ total time directly.
<!-- /CAT-UPDATE-ID: 7a296d64d0c9f5f3 -->

## Worked examples

### Trick 3. Constant distance — speed increases by 20%

**Question**

A car travels a fixed distance. Its speed increases by 20%. Find the percentage decrease in time.

**Traditional method**

Assume distance = 120 km and original speed = 60 km/h.

Original time:

$$
T_1=\frac{120}{60}=2\text{ hours}
$$

New speed:

$$
60\times1.20=72\text{ km/h}
$$

New time:

$$
T_2=\frac{120}{72}=\frac{5}{3}\text{ hours}
$$

Percentage decrease:

$$
\frac{2-5/3}{2}\times100=16.67\%
$$

> [!success] Answer
> **16.67% decrease in time (approximately).**

**Shortcut**

$$
S_1T_1=S_2T_2
$$

A 20% speed increase makes speed 120% of its original value. Therefore, time becomes 100/120 = 5/6 of its original value.

$$
\left(1-\frac{5}{6}\right)\times100=16.67\%
$$

> [!tip] CAT shortcut
> A 20% increase in speed does not cause a 20% decrease in time. Use the reciprocal factor.

<!-- CAT-UPDATE-ID: beecf83aa0758656 -->
### Example — Equal distances

A car travels 60 km at 30 km/h and another 60 km at 60 km/h.

Times:

$$
t_1=\frac{60}{30}=2\text{ h},\qquad t_2=\frac{60}{60}=1\text{ h}
$$

Average speed:

$$
\frac{120}{2+1}=\boxed{40\text{ km/h}}
$$

**Shortcut — harmonic mean**

$$
\frac{2\times30\times60}{30+60}=\boxed{40\text{ km/h}}
$$

### Question 25 — Unequal distances, equal times

**Question:** A car travels 40 km at 40 km/h and another 80 km at 80 km/h. Find its average speed.

**Step 1: Calculate each time**

$$
t_1=\frac{40}{40}=1\text{ hour}
$$

$$
t_2=\frac{80}{80}=1\text{ hour}
$$

**Step 2: Total distance and time**

$$
D=40+80=120\text{ km},\qquad T=1+1=2\text{ hours}
$$

**Step 3: Average speed**

$$
\frac{120}{2}=\boxed{60\text{ km/h}}
$$

**Shortcut:** The durations are equal, so use the arithmetic mean:

$$
\frac{40+80}{2}=\boxed{60\text{ km/h}}
$$

**Trap:** The distances are unequal, so do not use the equal-distance harmonic-mean formula.

### Question 30 — Equal halves of a journey

**Question:** A person travels half of a journey at 30 km/h and the other half at 60 km/h. Find the average speed for the entire journey.

**Step 1: Identify the condition**

The distances are equal, not the times. Use the harmonic mean.

**Step 2: Apply the shortcut**

$$
\text{Average speed}=\frac{2uv}{u+v}
$$

$$
=\frac{2\times30\times60}{30+60}=\boxed{40\text{ km/h}}
$$

**Traditional verification:** Assume the total journey is 120 km, so each half is 60 km.

$$
t_1=\frac{60}{30}=2\text{ hours},\qquad
t_2=\frac{60}{60}=1\text{ hour}
$$

$$
\text{Average speed}=\frac{120}{2+1}=\boxed{40\text{ km/h}}
$$

**Answer: 40 km/h.**

**Trap:** Do not use (30 + 60)/2 = 45 km/h. The arithmetic mean applies to equal-time travel, not equal-distance travel.
<!-- /CAT-UPDATE-ID: beecf83aa0758656 -->

## Common traps

- The inverse relationship applies only when distance is fixed.
- Do not equate the percentage increase in speed with the percentage decrease in time.
- Keep units consistent in S = D/T.

<!-- CAT-UPDATE-ID: e6fe475946f50ee0 -->
### Average-speed traps

- **Always start with total distance ÷ total time.**
- Equal distances call for the harmonic mean, not the arithmetic mean.
- Equal times call for the arithmetic mean.
- If neither distance nor time is equal, calculate each leg's time and use total distance ÷ total time.
- Do not assume a 20% increase in speed creates a 20% decrease in time; for fixed distance, use reciprocal multipliers.
- Keep distance, time and speed units consistent.
<!-- /CAT-UPDATE-ID: e6fe475946f50ee0 -->

## Practice and mistakes

- [ ] I can identify when distance is constant.
- [ ] I can use S₁T₁ = S₂T₂.
- [ ] I calculate percentage change using the original time as the base.

## Related notes

- [[Time & Work]]
- [[Percentages]]
- [[Ratios & Proportions]]

<!-- CAT-UPDATE-ID: b2c4cf030dac8d0d -->
- [[Averages]]
- [[Time & Work]]
- [[Ratios & Proportions]]
- [[Percentages]]
<!-- /CAT-UPDATE-ID: b2c4cf030dac8d0d -->
