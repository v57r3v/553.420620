java c
553.420/620 Probability
Assignment #05
1. Flip a fair coin 3 times. Let X be the discrete random variable that returns the length of the longest run of heads. Identify the support of this random variable and construct its probability mass function. I’ll get you started. . .

2. Identify the name of distribution of the following random variables from the descriptions. Be sure to identify the associated parameters from the description if possible and write out its pmf – don’t forget the support of the pmf.
(a) We toss a fair coin once. Let X count the number of heads.
(b) A box has 3 red and 2 blue marbles. Draw a marble uniformly at random, note its color and put it back; repeat until you’ve selected 3 times. Let X count the number of red marbles drawn.
(c) A box has 3 red and 2 blue marbles. Draw a marble uniformly at random, note its color and do not replace; repeat until you’ve selected 3 times. Let X count the number of red marbles drawn.
(d) A box has 3 red and 2 blue marbles. Draw a marble uniformly at random, note its color and put it back; repeat until you’ve selected 3 red marbles. Let Y count the number of marbles drawn.
(e) Surface imperfections on a silicon chip occur at a rate of 0.5 imperfection per square centimeter. Let S count the number of imperfections on a 3 cm2chip.
3. Show      is a pdf. Then compute the CDF of an rv having this pdf.
4. If you invest $1 with an APR of I × 100%, then in one year you will have 1 + I. After n years you’ll have (1 + I)n. A computer scientist give you two options.
Option 1 is they will give you an APR of I = .5, i.e, 50%, for 10 years.
Option 2 is they will equally likely at random pick one of the three interest rates 25%, 50% or 75% and then lock you in at this rate for 10 years, i.e., they are telling you P(I = .25) = P(I = .50) = P(I = .75) = 3/1.
Notice that E(I) = .50 in option 2 which agrees with option 1.
Compute E[(1 + I)n] under each option when n = 1, 2, and 10. What do you notice?
5. Suppose X ∼ Poisson(λ), i.e., is a discrete rv with pmf      for x = 0, 1, 2, . . . .
(a) Compute E(X) by definition. FYI: I am asking you to simplify      The MacL代 写553.420/620 Probability Assignment #05Matlab
代做程序编程语言aurin expansion for    may come in handy.
(b) Compute the MGF of X, namely, the function M(θ) = E(eθX) using the Law of the Unconscious Statisti-cian. It will turn out the this function exists and is finite for every real number θ. Answer: you should show M(θ) = eλ(eθ−1) for −∞ < θ < ∞.
(c) By taking derivatives of the MGF from part (b), derive the first two moments of the Poisson(λ). Use this information to compute V ar(X).
6. In class we showed that for a discrete rv X possessing an expected value that for any real numbers a and b, E(aX + b) = aE(X) + b. You show V ar(aX + b) = a2V ar(X). Stating the obvious here but when a = 1 this says V ar(X +b) = V ar(X), i.e., shifting the distribution by a fixed constant does not change the variance.
7. Let X ∼ geometric(p), where X is the trial of the first success in independent Bernoulli(p) trials; recall the pmf is P(X = x) = p(1 − p)x−1for x = 1, 2, 3, . . . .
(a) Derive the MGF M(θ) of X and wshow how you find the values of θ for which it exists and is finite. I’ll get you started      Answer: M(θ) = 1−(1 −θp)θ/peθ   for θ < − ln(1 − p).
(b) By taking the first two derivatives of the MGF from part (a) [okay, I admit this is a little tedious, but is good at getting you to perform. the chain rule carefully] find the mean and variance of X. Answer: E(X) = p/1, V ar(X) = p2/1 − p .
8. Follow-up to question 7. Sometimes the Y ∼ geometric(p) rv is thought of as the number of failures before the first success, so that Y = X − 1, where X is the trial of the first success.
(a) Using the fact that Y = X − 1 and, maybe the result of a previous problem on this assignment, easily compute E(Y ) and V ar(Y ).
(b) Using the result of problem 7 and the fact that Y = X − 1, easily derive the MGF of Y . Hint: E(eθY ) = E(eθ(X−1)) and you know the MGF of X...
The point of this problem is so that you understand that a geometric rv has both of these interpretations and, consequently, the mean is different (but the variance is not). A similar statement can be made about the different interpretations of the negative binomial rvs.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
