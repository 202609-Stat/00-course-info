# Statistics artifacts

[← Back to course information](README.md)

Interactive demos, listed by textbook chapter (Mendenhall, Beaver & Beaver, *Introduction to Probability and Statistics*). ✅ = ready (click the link); ⏳ = planned.

**[Open the table of contents page / 開啟互動示範目錄 →](https://claude.ai/artifact/TCTuT7f77Nkrv3Zc9mmTdi)**

## Across the course

- ✅ A brief history of statistics / 統計學簡史 — [open the page](https://claude.ai/artifact/8qkrtEysZE1beHqBRySiSK)
  - The person behind each chapter of the textbook, from the first charts in 1786 to the rank tests of 1945, with a drawing of each one’s key idea.

## Ch. 5 Discrete Probability Distributions

- ✅ Bernoulli trials — [open the demo](https://claude.ai/artifact/GTeVF9r8guehMg9Asrn7QB)
  - One trial, two outcomes: the share of successes settles at p; the variance p(1−p) is largest at p = 0.5.
- ✅ Binomial distribution — [open the demo](https://claude.ai/artifact/NbtNEGBmAr2gyP8HVA5k7m)
  - Count the successes in n trials, replication by replication; compare with the PMF, mean np and standard deviation.

## Ch. 6 The Normal Probability Distribution

- ✅ Normal distribution — [open the demo](https://claude.ai/artifact/8wuNWY1LjDau6rhsWafBF1)
  - Probability is area: shade P(a < X < b), see the same area on the z scale, check the 68–95–99.7 rule by simulation.

## Ch. 7 Sampling Distributions

- ✅ Central Limit Theorem — [open the demo](https://claude.ai/artifact/7rDtrP2FbSVgDTGGhJNkCP)
  - Five populations (Bernoulli, Uniform(0, 1), Normal, Poisson(5), Exp with mean 10), sample size n, replications R: one sample at a time, then histograms of X₁, the sample mean and the standardized sample mean.

## Ch. 8 Large-Sample Estimation

- ✅ Confidence intervals — [open the demo](https://claude.ai/artifact/5JboLhjXwFQfYBudnYaTtN)
  - Repeated samples build interval after interval; about 95% cover μ. The 95% describes the method, not one interval.

## Ch. 9 Large-Sample Tests of Hypotheses

- ✅ Hypothesis testing — [open the demo](https://claude.ai/artifact/YVfANGDShhckuDGiH6TSb9)
  - Run a z test again and again: rejection region, p-value, Type I and Type II errors, and power.

## Ch. 10 Inference from Small Samples

- ✅ How to build a chi-square distribution with 1 degree of freedom from Z² — [open the live demo](https://claude.ai/artifact/LdfPHdD6d4UbpLYokvTxCU)
  - Monte Carlo simulation: draw Z ~ N(0, 1), square it, and watch the draws of Z and Z² stack up into the N(0, 1) and χ²(1) densities. Histograms are overlaid with the theoretical PDFs. English / 中文.
- ✅ How to build a t distribution with 3 degrees of freedom — [open the demo](https://claude.ai/artifact/XV7vHsGhQgDmjnB9j8h6Em)
  - 2 × 3 panels for Z, χ²₃ and t₃ = Z / √(χ²₃ / 3); t is more spread out than z.

## Other commonly seen questions and answers

- ✅ Random variable vs. distribution — [open the page](https://claude.ai/artifact/KiaXtCgTGThVHPzpYE9EyY)
  - Two short Q&As: how a random variable differs from its distribution, and why "normal variable" and "normal distribution" are not the same thing. English / 中文.
- ✅ Why the claim goes in Hₐ, not H₀ — [open the page](https://claude.ai/artifact/76Kn8PkYeYRq98DufGGVRz)
  - A student's question: 為什麼要把想驗證的 claim 放在 Hₐ 而非 H₀？這和型一、型二錯誤有什麼關係？ Answer: α is the only error we control, so "support the claim" must mean "reject H₀"; with the 880-ton example, a decision-vs-truth table and the court analogy. English / 中文.
- ✅ Rejection region and p-value / 拒絕域與 p 值 — [open the page](https://claude.ai/artifact/5nyp8uXNbGBKhfmL2trzMA)
  - Two routes to one decision: z₀ falls in the rejection region exactly when p ≤ α, because the tail probability shrinks as the statistic moves out. Right, left and two-tailed forms side by side, a worked z₀ = 2.00 example, and why a small p is not a large effect. English / 中文.
- ✅ Writing H₀ and Hₐ, and the ANOVA H₀ / 如何寫 H₀ 與 Hₐ — [open the page](https://claude.ai/artifact/7TEwcHQ7PH9x9wdcY8ugtf)
  - H₀ carries the equality because a test needs one specific value to get a distribution from; Hₐ carries the claim. Then ANOVA: why H₀ is always "the grouping explains nothing" — only under equality does F have an F(k−1, n−k) distribution, differences only push MSB up, and the model should earn its keep. Same logic for the regression overall F test. English / 中文.
- ✅ Is regression a reduced case of a neural network? / 迴歸作為最小的神經網路 — [open the page](https://claude.ai/artifact/WPGWqgzCUCj9W1DgJkMi4k)
  - Yes: no hidden layer, one output, no activation, squared-error loss — that is least squares. Two diagrams show the small network and the same network reduced, with the algebra of why identity activations collapse any depth to one linear map, and what a network gives up (standard errors, t and F tests, intervals). English / 中文.


---

## 💬 Your comments

Questions or suggestions about these pages? Tell us in a one-minute form; your name is optional.
對這些頁面有疑問或建議嗎？歡迎花一分鐘填寫表單，可不具名。

**[Leave a comment / 填寫意見表 →](https://docs.google.com/forms/d/e/1FAIpQLSf-7mmgqvjLB7plzSDZUdUBGUnOJtH5gn4yUUJzsNfPEE-5GQ/viewform)**

© 2026 Huei-Wen Teng · FIMA Lumen · [CC BY-NC-SA 4.0](LICENSE)
