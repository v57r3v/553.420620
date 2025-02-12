java c
553.420/620 Intro. to Probability
Assignment #10
10.1. In class we showed that when X1 ∼ Gamma(α1, 1) and X2 ∼ Gamma(α2, 1) are independent, then


U1 = X1+X2/X1 ∼ Beta(α1, α2) by using method of Jacobians (taking U2 = X1 +X2). In this problem I want you to extend this result: Let X1 ∼ Gamma(α1, 1), X2 ∼ Gamma(α2, 1), X3 ∼ Gamma(α3, 1) be independent. Set





(a) Derive the joint PDF fU1,U2,U3(u1, u2, u3) of U1, U2, U3.
(b) Integrate out u3 to find the joint (marginal) PDf fU1,U2(u1, u2) of U1, U2.
Remark. Regarding part (b): This marginal is an example of the Dirichlet distribution and is to the multi-nomial distribution as the Beta distribution is to the binomial distribution. In general, if X1, X2, . . . , Xk+1 are independent and Xi ∼ Gamma(αi, 1) for i = 1, 2, . . . , k + 1 and, for 1 ≤ j ≤ k, Uj = X1···+Xk+1/+Xj, and Uk+1 = X1 + · · · + Xk+1, then it can be shown that, for 0 < uj < 1, j = 1, 2, . . . , k and 0 < u1 + · · · + uk < 1:





10.2. (independence and uncorrelated are not quite the same thing) In order to define the covariance between two random variables it is necessary for these random variables to possess a finite mean value: Cov(X, Y ) = E[(X − E(X))(Y − E(Y ))]. But random variables can be independent with possessing a finite mean value, for example, just consider two independent Cauchy rvs or Zeta(2) rvs. Therefore, independence does not imply uncorrelated. However, if independent rvs each have a finite mean, then their covariance is 0 (and are therefore uncorrelated). Show this, i.e., you have to show that if X and Y are independent and have finite means, then E(XY ) − E(X)E(Y ) = 0.
(b) Consider the discrete rv X with PMF P(X = −1) = 4/1 = P(X = 1), P(X = 0) = 2/1 . Let Y = X2. Show that X, Y are uncorrelated and not independent.
For part (b), in order to show they are not independent you have to show that the joint PMF is not the product of the marginal PMFs.
10.3 (a) Let X1, X2, . . . , Xn be rvs that have finite means and variances. Show that, for any constants a1, a2, . . . , an,





(b) Write down what part (a) says in the special case n = 2.
(c) What does part (a) tell us about the variance of a sum when the rvs are uncorrelated? Write it down.
(d) Now suppose X and Y are independent. Find a value of a with 0 ≤ a ≤ 1 such that V ar(aX + (1 − a)Y ) is minimized.
10.4. X1, X2, X3, . . . are a sequence of i.i.d. uniform(0, 1) random variables.
(a) For each fixed n, find the CDF of X(1), the smallest among X1, X代 写553.420/620 Intro. to Probability Assignment #10Python
代做程序编程语言2, . . . , Xn.
(b) For each fixed n, find the CDF of nX(1) = n min{X1, X2, . . . , Xn}.
(c) Compute limn→∞ FnX(1) (x). Does this CDF look familiar? If so, what is it?
10.5. Suppose N ∼ Poisson(λ) with λ > 0. Conditioned on N = n, X ∼ binomial(n, p), i.e., X|N ∼ binomial(N, p). Let Y = N − X.
(a) Show that X and Y each have Poisson distributions with respective parameters λp and λ(1 − p).
(b) Show that X and Y are, in fact, independent random variables! This shows that conditionally dependent random variables can be made independent through randomization.




10.6. Four people offer bids on an item; say the bid from person i is a continuous rv Xi. Assume the bids are independent and all share the same pdf f(x). The winning bid is the largest bid. The following are separate questions. If there is not enough information to answer, say so.
Compute the probability that. . .
(a) person 4 has the winning bid.
(b) X1 > X2 > X3.
(c) X1 > X2 > X3 and person 4 has the winning bid.
(d) X1 > X2 > X3 and person 4 does not have the winning bid.
(e) person 4 has the winning bid and person 1’s bid is not the lowest bid.
(f) the largest bid among the four people is at least $1 more than the next largest bid.
10.7. We have 5 iid uniform(0,1) rvs X1, X2, X3, X4, X5. Find easy ways to compute each of the following if possible.
(a) the probability the smallest of these is X5.
(b) the probability that X1 < X2.
(c) the probability that X1, X3 and X5 are monotone, i.e., either X1 < X3 < X5 or X1 > X3 > X5.
(d) the probability that X5 is the largest and X1 is not the smallest.
10.8. X, Y, Z have the joint PDF f(x, y, z) = 4xyz(x + y + z) for 0 < x < 1, 0 < y < 1, 0 < z < 1.
Compute P(X < Y |Z > max{X, Y }).
Remark. It would be great if you could do this without doing any calculus.
10.9. We have 4 A’s, 4 B’s, and 4 C’s. We randomly disburse these 12 into 4 groups of 3 each. Compute the expected number of groups containing one each of A, B and C.
10.10. A dish has 1 yellow, 1 red, 2 green and 6 blue mm’s. A person randomly selects 3.
(a) Let X count the number of blue candies in the selection. Compute E(X).
(b*) Let Y count the number of different colors in the selection. Compute E(Y ).
*Please find a way of computing this expected value without deriving the distribution of Y .
10.11. A spinner has 4 equally likely regions. Compute the expected number of spins it will take to see every region hit (at least once).





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
