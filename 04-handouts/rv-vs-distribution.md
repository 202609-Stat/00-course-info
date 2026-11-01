# Random Variables vs. Distributions

Student handout · Q&A

## Q1. What is the difference between a random variable and a distribution?

**Answer:** A random variable is the quantity that takes a value; its distribution is the list of possible values and how likely each one is.

- **Random variable** = *what* we measure (e.g., X = the number of heads in 3 coin flips).
- **Distribution** = *how* its values are spread (P(X=0)=1/8, P(X=1)=3/8, P(X=2)=3/8, P(X=3)=1/8).

The distribution summarizes a random variable, but it is not the variable itself.

## Q2. In daily speech we say "normal distribution" and "normal variable" interchangeably. Is there really a difference?

**Answer:** In casual talk, it is fine to mix them. Strictly speaking, they differ:

- **The normal distribution N(μ, σ²)** is *one* bell-shaped probability law.
- **A normal random variable** is *any* variable whose distribution is that law. There can be many of them.

The difference shows up when we combine variables.

**Example.** Let Z be a standard normal variable, Z ~ N(0, 1).

1. −Z is also a standard normal variable. Z and −Z have exactly the same distribution.
2. But Z + (−Z) = 0 every time. That sum is not normal at all.
3. Now take a second, independent variable Z′ ~ N(0, 1). It also has the same distribution as Z. Yet Z + Z′ ~ N(0, 2).

| Pair | Distribution of each | Distribution of the sum |
| --- | --- | --- |
| Z and −Z | N(0, 1) | Always 0 |
| Z and Z′ (independent) | N(0, 1) | N(0, 2) |

**Takeaway:** Same distributions do not mean same variables. To know how variables behave together, we need to know how they relate to each other, not just each one's distribution.
