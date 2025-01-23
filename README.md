java c
553.420/620 Probability 
Assignment #07 
1. In class we learned that a chi-square distribution with n > 0 degrees of freedom is the distribution of a continuous random variable having a Gamma( n2, 2)-distribution. We usually write this as X ∼ χ2n.
(a) Using this fact or just using the distribution sheet, construct the PDF of a χ22, i.e., a chi-square with 2 degrees of freedom. Is this another familiar distribution? If so, what specifically is it? Include parameters.
(b) Let X ∼ χ22. Using the MGF of a χ22, compute E(X).
(c)* (continued) Using the MGF of a χ22, compute E(eX/4), E(XeX/4) and E(X2eX/4).
(d)* (continued) E(eX/2) is not finite. Using the MGF of a χ22, explain what goes wrong here that didn’t go wrong in part (c).
2. Suppose X ∼ exp(1), and let a > 0 be a fixed constant. Use the CDF method to find the PDf of Y =√aX.
Remark: With the value a = 1 you notice this is just the PDF of the rv R from problem 5 on HW#6. Now this problem gives us an alternate way to do problem 5(c) from HW#6:

3. Suppose X ∼ uniform(0, 1). Use the CDF method to find the PDF of Y = ln(1−X/X). Just as a reminder here: part of this problem is for you to find the support of the rv Y . To help in this look at what happens to Y as X gets close to 0 from the right, and then look at what happens to Y when X gets close to 1 from the left.
4. Consider this function: 
(a) Show that it is a joint PDF.
(b) Compute P(0 < X < 2/1, 0 < Y < 2/1).
(c) Compute P(X + Y ≤ 2/1).
5. Suppose X and Y are jointly continuous rvs having the joint PDF from problem 4.
(a) Compute the marginal PDF of X.
(b) Use the marginal PDF to compute P(X ≤ 2/1).
6. The graph of the quadratic polynomial y = Ax2 − 1, when A > 0, has a unique positive root. For example when A = 2/1 this unique root is √2. For this problem we suppose A is random, A ∼ exp(1). Find the PDF of the (random) unique positive root.
Hint: the two solutions to Ax2 + Bx + C = 0 are  and  In our problem only one of these is positive.
7. Chips numbered 1 through 5 are in a hat and someone selects two of these chips uniformly at random without replacement. Let X be the number of even chips selected. Y be the number of chips still in the hat that are strictly between the two selected.
(a) Compute the joint PMF of X and Y in tabular form. Be sure to identify the support of each rv, for consistency, please make X the rows and Y the columns.
(b) Compute P(Y > X) and P(XY = 0). Clearly label each calculation.
(c) Derive the marginal PMFs of each rv X and Y .

8. Let X be a continuous random variable. You may suppose for this problem that its CDF F(x) is not only continuous but is also strictly increasing so that there is an inverse function F−1(y). No代 写553.420/620 Probability Assignment #07R
代做程序编程语言w, consider the new random variable Y = F(X), that is, Y is the random variable you get when we plug X into its own CDF. Show that Y has a uniform(0, 1) distribution.
Remark: This is an important fact to know since it is the basis of many ideas in statistics and often used in simulating observations of such a random variable X from simulations of uniform(0, 1): namely, to produce a value of a random variable X having CDF F, generate a uniform(0, 1) observation U. Then F−1(U) will have the distribution F.
Here’s an application of this result: Suppose we want to generate an X ∼ exp(λ) distribution. Compute the CDF of X, it turns out to be F(x) = 1 − e−λx for x > 0 (and = 0 otherwise). Compute the inverse of this CDF: y = F(x) = 1 − e−λx ⇐⇒ x = −λ/1 ln(1 − y) = F−1(y). Next generate a uniform(0, 1) ob-servation U (most computer programs can do this, eg., in Microsoft Excel the formula is =RAND()). Then x = F−1(U) = − λ/1 ln(1 − U) will be exp(λ) distributed.
9. In this problem Z ∼ N(0, 1) and X ∼ N(µ, σ2).
Write the answers to the following using the CDF Φ(z) of a standard normal distribution. Also, find the values of each of the following using either tables or a calculating device.
(a) P(Z < 2).
(b) P(|Z| ≤ 2).
(c) P(Z > −3.1).
(d) P(−2.3 < Z < 1.5).
(e) Let µ = 100 and σ = 10 (σ2 = 100). P(77 < X < 115).
(f) Let µ = 100 and σ = 10 (σ2 = 100). P(|X − 95| ≤ 10).
10. Suppose X, Y are independent uniform(0, 60), so that fX,Y (x, y) = 6012 for 0 < x < 60, 0 < y < 60. You can think of X and Y as the times (measured in minutes) at which two people arrive to a facility; they arrive independently of each other and at any time (uniformly ar random) in the one-hour interval from time 0 to time 60 minutes.
(a) Compute P(|X − Y | < 10). That is, compute the probability they arrive within 10 minutes of each other. Also, this is the probability that neither has o wait more than 10 minutes for the other to arrive.
(b) Compute the probability that one of them has to wait at least 30 minutes for the other.
11. In this problem the discrete X and the continuous Y are jointly distributed with joint distribution

Please understand that, in this function, x-values are discrete whereas the y-values are continuous, so we sum on x and integrate on y with this joint distribution.
(a) Derive the marginal PDF of Y . Identify it if you can along with parameters.
(b) Derive the marginal PMF of X. Identify the resulting familiar PMFs in the cases where m = 1 and m = 2.
12. Let X ∼ geom(p) and Y ∼ geom(q) be independent. Compute P(X = Y ).
13. Suppose X ∼ exp(1) and Y ∼ Gamma(2, 1) are independent. Find the PDF of U = X/Y.











         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
