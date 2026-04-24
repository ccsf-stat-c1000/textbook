# Rules for Means and Variances of Random Variables (3 of 3)

```{admonition} Learning Objectives
    - Apply the rules of means and variances to find the mean and variance of a linear transformation of a random variable and the sum of two independent random variables.
```

Besides taking a linear transformation of a random variable, another way to form a new random variable is to combine two or more existing random variables in some way, such as finding the sum of two random variables. Again, we'll start with a motivating example.

```{admonition} Example: Xavier's and Yves' Production Lines
    Recall previous examples for the number X of defective parts coming out of Xavier's production line, and Y from Yves' line. Consider the total number of defective parts coming out of both production lines together. This is the *new random variable X + Y*. Since we know the means and standard deviations of X and of Y, is there a simple, quick way to figure out the mean and standard deviation of X + Y?
```

In general, the mean of the sum of random variables is the sum of the means. As long as the random variables are independent, the variance of the sum equals the sum of the variances. The formal rules are as follows:

## Rules for X + Y
                (Sum
                of
                Two
                Random
                Variables)

Let X and Y be random variables with means $μ_{X}$ and $μ_{Y}$ and with variances $σ_{X}^{2}$and $σ_{Y}^{2}$. Then the new random variable X + Y has a mean of:

$μ_{X+Y}=μ_{X}+μ_{Y}$

and as long as the random variables are independent, the variance of X + Y is:

$σ_{X+Y}^{2}=σ_{X}^{2}+σ_{Y}^{2}$

What these two rules tell us is that if we take two random variables and add them, then the new mean is the sum of the original two means, and the new variance—not standard deviation—is the sum of the original two variances, as long as those variables are independent.

## Comment

We've talked a lot about independent and dependent *events*, but not about what it means for two *random variables* to be independent or dependent. Basically, the same reasoning extends from events to random variables. Two random variables will be independent if knowing that one random variable takes any of its possible values has no effect on the probability that the other random variable takes a certain value.

While in the case of *events* we formalized the definition of independence using conditional probability, doing the same for random variables is beyond the scope of this course. Therefore, whenever we want to use the rule:

$σ_{X+Y}^{2}=σ_{X}^{2}+σ_{Y}^{2}$, we will assume that X and Y are independent, or it will be clear from the context of the problem.

```{admonition} Example: Combined Mean and Standard Deviation
    We want to find the mean and standard deviation of X + Y, the total number of defective products coming out of both production lines in an hour. In the previous section, we found that:

    $μ_{X}=1.8$

    $σ_{X}=1.21$

    $μ_{Y}=2.7$

    $σ_{Y}=0.85$

    Using the rules for X + Y, we find that:

    $μ_{X+Y}=μ_{X}+μ_{Y}=1.8+2.7=4.5$

    $σ_{X+Y}^{2}=σ_{X}^{2}+σ_{Y}^{2}=1.21^{2}+0.85^{2}=2.19$

    $σ_{X+Y}=\sqrt{2.19}=1.48$

    We can conclude, then, that the total number of defective parts coming out of both production lines in an hour is on average 4.5, and typically the combined number of defective products is about 1.48 away from that average.
```

## Comment

It is important to remember that while variances are additive, standard deviations are not:

$σ_{X}+σ_{Y}=1.21+0.85=2.06\neqσ_{X+Y}=1.48$

```{note}
    **Did I Get This?**

    *(Interactive activity — available in the OLI platform)*
```
