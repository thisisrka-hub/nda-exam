# NDA 2026 Mathematics: Statistics & Probability (5-10%)

## Important Notes and Formulas

### Measures of Central Tendency
- Mean (arithmetic mean): sum of observations divided by number of observations.
  - For data x_1, x_2, ..., x_n, mean = (x_1+x_2+...+x_n)/n.
- Median: middle value in ordered data.
  - If n is odd, median = middle term.
  - If n is even, median = average of two middle terms.
- Mode: most frequently occurring value. There can be one mode, more than one mode, or no mode.
- Weighted mean: sum(w_i x_i)/sum(w_i).
- Combined mean: (n_1 mean_1 + n_2 mean_2)/ (n_1 + n_2).
- Relationship: mean - mode = 3(mean - median) for moderately skewed distributions.

### Measures of Dispersion
- Range = maximum - minimum.
- Mean deviation (mean absolute deviation): average of absolute deviations from mean.
- Variance: average squared deviation from mean.
  - Population variance = sigma^2 = (1/N) sum (x_i - mu)^2.
  - Sample variance = s^2 = (1/(n-1)) sum (x_i - xbar)^2.
- Standard deviation: square root of variance.
  - Population SD = sigma.
  - Sample SD = s.
- Coefficient of variation = (standard deviation / mean) * 100%.
- Quartile deviation (semi-interquartile range) = (Q3 - Q1)/2.
- Percentiles: k-th percentile is value below which k% of observations lie.
- Chebyshev's inequality: at least (1 - 1/k^2) of values lie within k standard deviations of mean for any distribution.

### Probability Basics
- Probability of event A: P(A) = number of favorable outcomes / total outcomes (for equally likely outcomes).
- Complement rule: P(A') = 1 - P(A).
- Addition rule: P(A or B) = P(A) + P(B) - P(A and B).
- For mutually exclusive events: P(A or B) = P(A) + P(B).
- Multiplication rule for independent events: P(A and B) = P(A) P(B).
- Conditional probability: P(A|B) = P(A and B)/P(B).
- Bayes theorem: P(A|B) = P(B|A)P(A)/P(B).

### Probability Distribution
- Probability mass function (pmf) for discrete random variable X: P(X=x).
- Probability density function (pdf) for continuous X: f(x) with P(a<X<b) = integral_a^b f(x) dx.
- Cumulative distribution function (cdf): F(x) = P(X \le x).
- Expected value (mean) of discrete distribution: E(X) = sum x P(X=x).
- Variance of distribution: Var(X) = E(X^2) - [E(X)]^2.
- Binomial distribution: P(X=k) = nCk p^k (1-p)^{n-k}.
  - Mean = np, variance = np(1-p).
- Poisson distribution: P(X=k) = e^{-lambda} lambda^k / k!.
  - Mean = lambda, variance = lambda.
- Uniform discrete distribution on k values: each value has probability 1/k.
- Normal distribution: bell-shaped density with mean mu and variance sigma^2.
  - Standard normal variable Z = (X - mu)/sigma.

### Key Formulas
- Arithmetic mean = sum x_i / n.
- Median for grouped data = l + [(n/2 - cf)/f]*h.
- Mode for grouped data = l + [(f1 - f0)/(2f1 - f0 - f2)]*h.
- Variance = (sum x_i^2)/n - mean^2 for population.
- SD = sqrt(variance).
- Coefficient of variation = (SD / mean) * 100.
- Binomial mean = np.
- Binomial variance = np(1-p).
- Poisson mean and variance = lambda.
- For discrete distributions, E(X) = sum x p_x, E(X^2) = sum x^2 p_x.

## MCQs

1. Mean of 2, 5, 7 is?
   A) 14/3
   B) 4
   C) 5
   D) 7
   **Answer:** A
   **Explanation:** Arithmetic mean = 14/3.

2. Median of 3, 1, 4, 5 is?
   A) 3.5
   B) 3
   C) 4
   D) 2.5
   **Answer:** A
   **Explanation:** Even number of terms; average middle two.

3. Mode of 2, 3, 3, 4 is?
   A) 3
   B) 2
   C) 4
   D) None
   **Answer:** A
   **Explanation:** 3 appears most frequently.

4. Range of 4, 10, 6 is?
   A) 6
   B) 10
   C) 4
   D) 16
   **Answer:** A
   **Explanation:** Range = 10-4 = 6.

5. Population variance formula uses divisor?
   A) N
   B) n-1
   C) n+1
   D) 2n
   **Answer:** A
   **Explanation:** Population variance divides by N.

6. Sample variance formula uses divisor?
   A) n-1
   B) n
   C) N
   D) n+1
   **Answer:** A
   **Explanation:** Sample variance divides by n-1.

7. Standard deviation is?
   A) sqrt(variance)
   B) variance^2
   C) mean*variance
   D) mean/variance
   **Answer:** A
   **Explanation:** SD is square root of variance.

8. Coefficient of variation expresses?
   A) SD as % of mean
   B) mean as % of SD
   C) range as % of mean
   D) variance / mean
   **Answer:** A
   **Explanation:** CV = SD/mean * 100%.

9. P(A or B) for mutually exclusive events is?
   A) P(A)+P(B)
   B) P(A)P(B)
   C) P(A)-P(B)
   D) P(A)/P(B)
   **Answer:** A
   **Explanation:** Mutually exclusive addition rule.

10. P(A | B) is?
   A) P(A and B)/P(B)
   B) P(A)+P(B)
   C) P(A)P(B)
   D) P(B)/P(A)
   **Answer:** A
   **Explanation:** Definition of conditional probability.

11. Binomial mean is?
   A) np
   B) n/p
   C) p/n
   D) n+p
   **Answer:** A
   **Explanation:** Mean of Binomial = np.

12. Poisson mean equals?
   A) lambda
   B) np
   C) p
   D) n
   **Answer:** A
   **Explanation:** Poisson mean is lambda.

13. If P(A)=0.3, P(A")==
   A) 0.7
   B) 0.3
   C) 1.3
   D) 0
   **Answer:** A
   **Explanation:** Complement rule.

14. For discrete X, PMF sums to?
   A) 1
   B) 0
   C) n
   D) 2
   **Answer:** A
   **Explanation:** Total probability = 1.

15. A random variable with probability density is?
   A) Continuous
   B) Discrete
   C) Qualitative
   D) None
   **Answer:** A
   **Explanation:** Density applies to continuous variables.

16. If data = 5,5,5, mode =?
   A) 5
   B) none
   C) 15
   D) 0
   **Answer:** A
   **Explanation:** All values same mode is 5.

17. Median of 1, 2, 3, 4, 5 is?
   A) 3
   B) 2
   C) 4
   D) 3.5
   **Answer:** A
   **Explanation:** Middle value with odd data count.

18. Range of 2, 8, 12 is?
   A) 10
   B) 12
   C) 8
   D) 14
   **Answer:** A
   **Explanation:** 12-2 = 10.

19. Mean deviation is average of?
   A) Absolute deviations
   B) Squared deviations
   C) Raw deviations
   D) Log deviations
   **Answer:** A
   **Explanation:** Mean deviation uses absolute deviations.

20. Variance of constant data is?
   A) 0
   B) 1
   C) Mean
   D) Undefined
   **Answer:** A
   **Explanation:** No spread means variance 0.

21. PDF integrates to?
   A) 1
   B) 0
   C) n
   D) Mean
   **Answer:** A
   **Explanation:** Total probability = 1.

22. CDF is nondecreasing and ranges from?
   A) 0 to 1
   B) 1 to 2
   C) -1 to 1
   D) 0 to infinity
   **Answer:** A
   **Explanation:** CDF values go from 0 to 1.

23. Expected value E(X) is also called?
   A) Mean
   B) Median
   C) Mode
   D) Range
   **Answer:** A
   **Explanation:** Expected value is mean of distribution.

24. If p = 0.5 in binomial, distribution is?
   A) Symmetric
   B) Skewed left
   C) Skewed right
   D) Undefined
   **Answer:** A
   **Explanation:** Binomial symmetric at p=0.5.

25. For a normal distribution, mean equals?
   A) Median
   B) Mode
   C) Both median and mode
   D) None
   **Answer:** C
   **Explanation:** Normal distribution is symmetric.

26. Probability of impossible event is?
   A) 0
   B) 1
   C) 0.5
   D) Undefined
   **Answer:** A
   **Explanation:** Impossible event has probability 0.

27. Probability of certain event is?
   A) 1
   B) 0
   C) 0.5
   D) Undefined
   **Answer:** A
   **Explanation:** Certain event has probability 1.

28. Random variable taking values 1,2,3 equally likely has mean?
   A) 2
   B) 1
   C) 3
   D) 6
   **Answer:** A
   **Explanation:** Mean = (1+2+3)/3.

29. A distribution with two modes is called?
   A) Bimodal
   B) Uniform
   C) Skewed
   D) Normal
   **Answer:** A
   **Explanation:** Two modes define bimodal.

30. Q1 and Q3 are?
   A) First and third quartiles
   B) Mean and median
   C) Variance and SD
   D) Range endpoints
   **Answer:** A
   **Explanation:** Quartiles definition.

31. Semi-interquartile range = ?
   A) (Q3 - Q1)/2
   B) Q3 - Q1
   C) (Q1 + Q3)/2
   D) Q1/Q3
   **Answer:** A
   **Explanation:** Definition of quartile deviation.

32. In grouped data, median formula uses?
   A) cumulative frequency
   B) range
   C) mode
   D) mean
   **Answer:** A
   **Explanation:** Grouped median uses CF.

33. Poisson distribution approximates binomial when?
   A) n large, p small
   B) n small, p large
   C) p=0.5
   D) n=1
   **Answer:** A
   **Explanation:** Poisson approximation conditions.

34. Variance of binomial = np(1-p). For p=0 or p=1, variance =?
   A) 0
   B) n
   C) np
   D) 1
   **Answer:** A
   **Explanation:** Distribution degenerates to constant.

35. A symmetric distribution has mean = ?
   A) median = mode
   B) range
   C) variance
   D) skewness
   **Answer:** A
   **Explanation:** Symmetric distribution equality.

36. The sample standard deviation uses degrees of freedom?
   A) n-1
   B) n
   C) 1
   D) 2
   **Answer:** A
   **Explanation:** Sample SD divisor is n-1.

37. Standard deviation is always?
   A) Non-negative
   B) Negative
   C) Zero only
   D) Undefined
   **Answer:** A
   **Explanation:** SD cannot be negative.

38. Probability of A or A complement is?
   A) 1
   B) 0
   C) P(A)
   D) P(A complement)
   **Answer:** A
   **Explanation:** Either event must occur.

39. Combined mean of groups uses total sum divided by?
   A) Total frequency
   B) Group count
   C) Range
   D) Mode
   **Answer:** A
   **Explanation:** Weighted sum over total size.

40. If data values are all equal, mean equals?
   A) Value
   B) 0
   C) Range
   D) Variance
   **Answer:** A
   **Explanation:** All observations same.

41. Empirical rule 68-95-99.7 applies to?
   A) Normal distribution
   B) Any distribution
   C) Uniform distribution
   D) Binomial only
   **Answer:** A
   **Explanation:** Empirical rule is for normal.

42. Probability of A and B for independent events is?
   A) P(A)P(B)
   B) P(A)+P(B)
   C) P(A)-P(B)
   D) P(A)/P(B)
   **Answer:** A
   **Explanation:** Independence multiplication rule.

43. When events are mutually exclusive, P(A and B)=?
   A) 0
   B) P(A)P(B)
   C) P(A)+P(B)
   D) 1
   **Answer:** A
   **Explanation:** Mutually exclusive events cannot occur together.

44. The mean of discrete distribution is sum of x times?
   A) P(X=x)
   B) x
   C) 1/x
   D) cdf
   **Answer:** A
   **Explanation:** Expected value formula.

45. Variance is E(X^2) minus square of?
   A) E(X)
   B) Mode
   C) Median
   D) Range
   **Answer:** A
   **Explanation:** Variance identity.

46. A probability distribution must satisfy nonnegative probabilities and sums to?
   A) 1
   B) 0
   C) n
   D) Mean
   **Answer:** A
   **Explanation:** Basic requirement.

47. For binomial n=5, p=0.4, mean =?
   A) 2
   B) 1
   C) 3
   D) 0.4
   **Answer:** A
   **Explanation:** Mean = np = 2.

48. For Poisson lambda=3, variance =?
   A) 3
   B) 9
   C) 1
   D) 0
   **Answer:** A
   **Explanation:** Poisson variance equals lambda.

49. If data 1,2,3,4 have mean 2.5, median is?
   A) 2.5
   B) 2
   C) 3
   D) 1
   **Answer:** A
   **Explanation:** Even count median average.

50. Mode is not well-defined for which distribution?
   A) Uniform
   B) Bimodal
   C) Normal
   D) Skewed
   **Answer:** A
   **Explanation:** Uniform distribution has no mode or every value equally probable.

51. Probability of drawing red or blue from equal red blue green is?
   A) 2/3
   B) 1/3
   C) 1/2
   D) 3/4
   **Answer:** A
   **Explanation:** Two favorable out of three.

52. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

53. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

54. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

55. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

56. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

57. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

58. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

59. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

60. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

61. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

62. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

63. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

64. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

65. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

66. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

67. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

68. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

69. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

70. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

71. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

72. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

73. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

74. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

75. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

76. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

77. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

78. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

79. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

80. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

81. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

82. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

83. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

84. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

85. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

86. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

87. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

88. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

89. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

90. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

91. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

92. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

93. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

94. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

95. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

96. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

97. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

98. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

99. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

100. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

101. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

102. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

103. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

104. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

105. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

106. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

107. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

108. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

109. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

110. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

111. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

112. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

113. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

114. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

115. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

116. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

117. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

118. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

119. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

120. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

121. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

122. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

123. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

124. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

125. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

126. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

127. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

128. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

129. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

130. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

131. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

132. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

133. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

134. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

135. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

136. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

137. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

138. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

139. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

140. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

141. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

142. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

143. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

144. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

145. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

146. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

147. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

148. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

149. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

150. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

151. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

152. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

153. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

154. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

155. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

156. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

157. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

158. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

159. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

160. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

161. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

162. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

163. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

164. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

165. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

166. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

167. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

168. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

169. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

170. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

171. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

172. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

173. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

174. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

175. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

176. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

177. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

178. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

179. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

180. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

181. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

182. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

183. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

184. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

185. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

186. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

187. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

188. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

189. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

190. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

191. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

192. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

193. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

194. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

195. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

196. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

197. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

198. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

199. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

200. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

201. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

202. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

203. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

204. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

205. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

206. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

207. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

208. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

209. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

210. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

211. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

212. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

213. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

214. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

215. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

216. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

217. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

218. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

219. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

220. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

221. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

222. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

223. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

224. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

225. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

226. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

227. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

228. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

229. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

230. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

231. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

232. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

233. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

234. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

235. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

236. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

237. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

238. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

239. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

240. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

241. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

242. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

243. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

244. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

245. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

246. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

247. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

248. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

249. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

250. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

251. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

252. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

253. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

254. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

255. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

256. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

257. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

258. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

259. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

260. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

261. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

262. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

263. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

264. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

265. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

266. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

267. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

268. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

269. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

270. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

271. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

272. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

273. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

274. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

275. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

276. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

277. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

278. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

279. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

280. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

281. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

282. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

283. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

284. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

285. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

286. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

287. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

288. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

289. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

290. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

291. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

292. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

293. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

294. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

295. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

296. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

297. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

298. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

299. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

300. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

301. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

302. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

303. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

304. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

305. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

306. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

307. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

308. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

309. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

310. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

311. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

312. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

313. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

314. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

315. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

316. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

317. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

318. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

319. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

320. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

321. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

322. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

323. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

324. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

325. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

326. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

327. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

328. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

329. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

330. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

331. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

332. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

333. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

334. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

335. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

336. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

337. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

338. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

339. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

340. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

341. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

342. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

343. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

344. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

345. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

346. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

347. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

348. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

349. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

350. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

351. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

352. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

353. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

354. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

355. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

356. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

357. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

358. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

359. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

360. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

361. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

362. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

363. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

364. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

365. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

366. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

367. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

368. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

369. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

370. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

371. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

372. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

373. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

374. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

375. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

376. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

377. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

378. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

379. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

380. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

381. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

382. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

383. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

384. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

385. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

386. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

387. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

388. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

389. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

390. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

391. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

392. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

393. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

394. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

395. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

396. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

397. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

398. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

399. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

400. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

401. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

402. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

403. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

404. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

405. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

406. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

407. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

408. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

409. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

410. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

411. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

412. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

413. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

414. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

415. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

416. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

417. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

418. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

419. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

420. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

421. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

422. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

423. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

424. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

425. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

426. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

427. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

428. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

429. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

430. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

431. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

432. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

433. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

434. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

435. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

436. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

437. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

438. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

439. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

440. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

441. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

442. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

443. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

444. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

445. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

446. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

447. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

448. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

449. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

450. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

451. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

452. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

453. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

454. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

455. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

456. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

457. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

458. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

459. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

460. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

461. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

462. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

463. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

464. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

465. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

466. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

467. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

468. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

469. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

470. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

471. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

472. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

473. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

474. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

475. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

476. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

477. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

478. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

479. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

480. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

481. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

482. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

483. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

484. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

485. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

486. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

487. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

488. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

489. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

490. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

491. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

492. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.

493. Variance is the average of?
   A) Squared deviations
   B) Absolute deviations
   C) Values
   D) Reciprocals
   **Answer:** A
   **Explanation:** Variance uses squared deviations from the mean.

494. Standard deviation of data with variance 9 is?
   A) 3
   B) 9
   C) 81
   D) 1/3
   **Answer:** A
   **Explanation:** SD is sqrt(variance) = 3.

495. If P(A)=0.2 and P(B)=0.3 independent, P(A and B) =?
   A) 0.06
   B) 0.5
   C) 0.1
   D) 0.02
   **Answer:** A
   **Explanation:** Multiply probabilities for independent events.

496. For binomial with n=4, p=0.5, probability of 2 successes is?
   A) 6/16
   B) 4/16
   C) 1/16
   D) 8/16
   **Answer:** A
   **Explanation:** nCk p^k (1-p)^{n-k} = 6/16.

497. Mean of 1, 3, 5, 7, 9 is?
   A) 5
   B) 4
   C) 6
   D) 3
   **Answer:** A
   **Explanation:** Odd numbers average to middle value 5.

498. Median of 10, 20, 30, 40 is?
   A) 25
   B) 20
   C) 30
   D) 35
   **Answer:** A
   **Explanation:** Even terms median is average of middle two values.

499. Mode of 1, 2, 2, 3, 4 is?
   A) 2
   B) 1
   C) 3
   D) 4
   **Answer:** A
   **Explanation:** 2 appears most frequently.

500. Range of 8, 15, 22 is?
   A) 14
   B) 22
   C) 8
   D) 7
   **Answer:** A
   **Explanation:** Range = max - min = 22-8 = 14.



