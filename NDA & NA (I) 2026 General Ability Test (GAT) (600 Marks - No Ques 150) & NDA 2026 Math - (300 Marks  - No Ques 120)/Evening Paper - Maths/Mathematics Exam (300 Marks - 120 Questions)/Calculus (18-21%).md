# NDA 2026 Mathematics: Calculus (18-21%)

## Important Notes and Formulas

### Limits
- **Definition**: lim_{x→a} f(x) = L if for every ε > 0, there exists δ > 0 such that |f(x) - L| < ε whenever 0 < |x - a| < δ.
- **One-sided Limits**: lim_{x→a+} f(x), lim_{x→a-} f(x).
- **Indeterminate Forms**: 0/0, ∞/∞, 0*∞, ∞-∞, 0^0, 1^∞, ∞^0.
- **L'Hôpital's Rule**: For 0/0 or ∞/∞, lim (f/g) = lim (f'/g').
- **Standard Limits**:
  - lim_{x→0} (sin x)/x = 1
  - lim_{x→0} (1 - cos x)/x = 0
  - lim_{x→0} (e^x - 1)/x = 1
  - lim_{x→0} (a^x - 1)/x = ln a
  - lim_{x→0} (ln(1+x))/x = 1
  - lim_{x→∞} (1 + 1/x)^x = e
  - lim_{x→0} (1 + x)^(1/x) = e
- **Squeeze Theorem**: If f ≤ g ≤ h and lim f = lim h = L, then lim g = L.

### Continuity
- **Definition**: f is continuous at x=a if lim_{x→a} f(x) = f(a).
- **Types**: Continuous from left/right, removable discontinuity, jump discontinuity, infinite discontinuity.
- **Properties**: Sum, difference, product, quotient (if denominator ≠0) of continuous functions are continuous.
- **Composite Functions**: If f continuous at a, g continuous at f(a), then g∘f continuous at a.
- **Intermediate Value Theorem**: If f continuous on [a,b], f(a) < c < f(b), then ∃x in (a,b) with f(x)=c.
- **Extreme Value Theorem**: If f continuous on [a,b], then f has max and min on [a,b].

### Differentiability
- **Definition**: f'(a) = lim_{h→0} [f(a+h) - f(a)]/h
- **Rules**:
  - (c)' = 0
  - (x^n)' = n x^{n-1}
  - (cf)' = c f'
  - (f+g)' = f' + g'
  - (f g)' = f' g + f g'
  - (f/g)' = (f' g - f g') / g^2
  - (f∘g)' = f'(g) g'
- **Chain Rule**: d/dx [f(g(x))] = f'(g(x)) g'(x)
- **Implicit Differentiation**: Differentiate both sides, solve for dy/dx.
- **Higher Derivatives**: f'', f''', etc.
- **Logarithmic Differentiation**: For y = u^v, ln y = v ln u, differentiate.
- **Parametric Differentiation**: dx/dt, dy/dt, dy/dx = (dy/dt)/(dx/dt)

### Maxima and Minima
- **Critical Points**: f'(x) = 0 or undefined.
- **Second Derivative Test**: If f''(c) > 0, local min; <0, local max; =0, inconclusive.
- **First Derivative Test**: Sign change from + to - : max; - to + : min.
- **Absolute Max/Min**: On closed interval, check endpoints and critical points.
- **Rolle's Theorem**: If f continuous on [a,b], differentiable on (a,b), f(a)=f(b), then ∃c in (a,b) with f'(c)=0.
- **Mean Value Theorem**: ∃c in (a,b) with f'(c) = [f(b)-f(a)]/(b-a).
- **Increasing/Decreasing**: f' >0 increasing, f'<0 decreasing.

### Integration
- **Indefinite Integral**: ∫ f(x) dx = F(x) + C, where F' = f.
- **Definite Integral**: ∫_a^b f(x) dx = F(b) - F(a)
- **Properties**:
  - ∫_a^b f = - ∫_b^a f
  - ∫_a^b (f+g) = ∫f + ∫g
  - ∫_a^b c f = c ∫f
  - ∫_a^c f + ∫_c^b f = ∫_a^b f
- **Fundamental Theorem**: d/dx ∫_a^x f(t) dt = f(x)
- **Integration by Parts**: ∫ u dv = u v - ∫ v du
- **Substitution**: ∫ f(g(x)) g'(x) dx = ∫ f(u) du, u=g(x)
- **Partial Fractions**: For rational functions.
- **Trigonometric Integrals**: ∫ sin^m x cos^n x dx, etc.
- **Reduction Formulas**: For higher powers.

### Differential Equations
- **Order**: Highest derivative.
- **Degree**: Power of highest derivative.
- **General Solution**: Contains arbitrary constants.
- **Particular Solution**: Specific values.
- **First Order Linear**: dy/dx + P y = Q, integrating factor e^{∫P dx}
- **Homogeneous**: dy/dx = f(y/x)
- **Variable Separable**: dy/dx = f(x) g(y), ∫ g(y) dy = ∫ f(x) dx
- **Exact**: M dx + N dy = 0, ∂M/∂y = ∂N/∂x
- **Bernoulli**: dy/dx + P y = Q y^n
- **Second Order Linear**: y'' + P y' + Q y = 0
- **Homogeneous**: Characteristic equation r^2 + P r + Q = 0
- **Particular Solution**: For RHS, assume form based on RHS.

## MCQs

### Limits (Questions 1-83)

1. lim_{x→0} (sin x)/x = ?  
   A) 0  
   B) 1  
   C) ∞  
   D) -1  
   **Answer:** B) 1  
   **Explanation:** Standard limit.

2. lim_{x→0} (1 - cos x)/x² = ?  
   A) 0  
   B) 1/2  
   C) 1  
   D) ∞  
   **Answer:** B) 1/2  
   **Explanation:** lim (1 - cos x)/x² = (1/2) lim (sin x / x)^2 * (1/sin x) wait, derivative.

3. lim_{x→∞} (x² + 1)/(x² - 1) = ?  
   A) 0  
   B) 1  
   C) ∞  
   D) -1  
   **Answer:** B) 1  
   **Explanation:** Divide numerator and denominator by x².

4. lim_{x→0} (e^x - 1)/x = ?  
   A) 0  
   B) 1  
   C) e  
   D) ∞  
   **Answer:** B) 1  
   **Explanation:** Standard limit.

5. lim_{x→0} (ln(1+x))/x = ?  
   A) 0  
   B) 1  
   C) ∞  
   D) -∞  
   **Answer:** B) 1  
   **Explanation:** Standard limit.

6. lim_{x→0} (a^x - 1)/x = ?  
   A) 0  
   B) ln a  
   C) 1  
   D) ∞  
   **Answer:** B) ln a  
   **Explanation:** Standard limit.

7. lim_{x→∞} (1 + 1/x)^x = ?  
   A) 0  
   B) 1  
   C) e  
   D) ∞  
   **Answer:** C) e  
   **Explanation:** Standard limit.

8. lim_{x→0} (1 + x)^(1/x) = ?  
   A) 0  
   B) 1  
   C) e  
   D) ∞  
   **Answer:** C) e  
   **Explanation:** Standard limit.

9. lim_{x→0} sin x / x = 1, this is?  
   A) L'Hôpital  
   B) Squeeze  
   C) Standard  
   D) None  
   **Answer:** C) Standard  
   **Explanation:** Fundamental.

10. For indeterminate 0/0, use?  
    A) L'Hôpital  
    B) Squeeze  
    C) Standard  
    D) None  
    **Answer:** A) L'Hôpital  
    **Explanation:** Rule.

11. lim_{x→2} (x² - 4)/(x - 2) = ?  
    A) 0  
    B) 4  
    C) 2  
    D) ∞  
    **Answer:** B) 4  
    **Explanation:** Factor.

12. lim_{x→0} (sin 3x)/x = ?  
    A) 0  
    B) 3  
    C) 1  
    D) ∞  
    **Answer:** B) 3  
    **Explanation:** sin 3x = 3 sin x cos 2x ≈ 3x.

13. lim_{x→0} (tan x)/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -1  
    **Answer:** B) 1  
    **Explanation:** tan x ≈ x.

14. lim_{x→∞} x / e^x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** Exponential grows faster.

15. lim_{x→0+} x ln x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** 0 * (-∞) = 0.

16. lim_{x→0} (1 - cos x)/x = ?  
    A) 0  
    B) 1  
    C) 1/2  
    D) ∞  
    **Answer:** A) 0  
    **Explanation:** Standard.

17. lim_{x→π/2} (x - π/2)/sin x = ?  
    A) 0  
    B) 1  
    C) -1  
    D) ∞  
    **Answer:** B) 1  
    **Explanation:** L'Hôpital or known.

18. lim_{x→0} (sin x)/ (x + sin x) = ?  
    A) 0  
    B) 1/2  
    C) 1  
    D) ∞  
    **Answer:** B) 1/2  
    **Explanation:** Divide numerator and denominator by x.

19. lim_{x→∞} (x + 1)/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** B) 1  
    **Explanation:** ∞/∞ =1.

20. lim_{x→0} (e^{2x} - 1)/x = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** Standard.

21. lim_{x→0} (ln(1 + 2x))/x = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** Standard.

22. lim_{x→0} (2^x - 1)/x = ?  
    A) 0  
    B) ln 2  
    C) 1  
    D) ∞  
    **Answer:** B) ln 2  
    **Explanation:** Standard.

23. lim_{x→∞} (2x + 1)/(x - 1) = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** Divide by x.

24. lim_{x→0} (sin 2x)/x = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** sin 2x = 2 sin x cos x ≈ 2x.

25. lim_{x→0} (cos x - 1)/x² = ?  
    A) 0  
    B) -1/2  
    C) 1/2  
    D) ∞  
    **Answer:** B) -1/2  
    **Explanation:** Derivative.

26. lim_{x→∞} e^x / x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** C) ∞  
    **Explanation:** Exponential dominates.

27. lim_{x→0+} x^x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** B) 1  
    **Explanation:** 0^0 =1.

28. lim_{x→∞} (ln x)/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** Log grows slower.

29. lim_{x→1} (x^2 - 1)/(x - 1) = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** Factor.

30. lim_{x→0} (tan 2x)/x = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** tan 2x ≈ 2x.

31. lim_{x→0} (e^x - e^{-x})/x = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** sinh x / x →1, but wait, (e^x - e^{-x})/x = 2 sinh x / x →2.

32. lim_{x→∞} x sin(1/x) = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** B) 1  
    **Explanation:** Squeeze.

33. lim_{x→0} (arcsin x)/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** B) 1  
    **Explanation:** Derivative.

34. lim_{x→0} (arctan x)/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** B) 1  
    **Explanation:** Derivative.

35. lim_{x→∞} (x^2 + x + 1)/(x^2 - x + 1) = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** B) 1  
    **Explanation:** Divide by x².

36. lim_{x→0} (sin x)^2 / x^2 = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** B) 1  
    **Explanation:** (sin x / x)^2.

37. lim_{x→∞} (x^3 + 1)/(x^2 + 1) = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** C) ∞  
    **Explanation:** x^3 / x^2 = x.

38. lim_{x→0} (1 - cos 2x)/x^2 = ?  
    A) 0  
    B) 1  
    C) 2  
    D) ∞  
    **Answer:** C) 2  
    **Explanation:** 1 - cos 2x = 2 sin^2 x, so 2 (sin x / x)^2 →2.

39. lim_{x→0} (e^{3x} - 1)/x = ?  
    A) 0  
    B) 1  
    C) 3  
    D) ∞  
    **Answer:** C) 3  
    **Explanation:** Standard.

40. lim_{x→0} (ln(1 + 3x))/x = ?  
    A) 0  
    B) 1  
    C) 3  
    D) ∞  
    **Answer:** C) 3  
    **Explanation:** Standard.

41. lim_{x→0} (3^x - 1)/x = ?  
    A) 0  
    B) ln 3  
    C) 1  
    D) ∞  
    **Answer:** B) ln 3  
    **Explanation:** Standard.

42. lim_{x→∞} (3x + 1)/(x - 1) = ?  
    A) 0  
    B) 1  
    C) 3  
    D) ∞  
    **Answer:** C) 3  
    **Explanation:** Divide by x.

43. lim_{x→0} (sin 4x)/x = ?  
    A) 0  
    B) 1  
    C) 4  
    D) ∞  
    **Answer:** C) 4  
    **Explanation:** sin 4x ≈ 4x.

44. lim_{x→0} (cos 2x - 1)/x^2 = ?  
    A) 0  
    B) -1  
    C) -2  
    D) ∞  
    **Answer:** C) -2  
    **Explanation:** Derivative of cos 2x at 0 is -2 sin 2x, wait, (cos 2x -1)/x^2 → (1/2) d²/dx² cos 2x at 0 = (1/2)(-4) cos 2x = -2.

45. lim_{x→∞} x^2 / e^x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** Exponential dominates.

46. lim_{x→0+} (-ln x) = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** C) ∞  
    **Explanation:** As x→0+, ln x → -∞, -ln x → ∞.

47. lim_{x→∞} x / ln x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** C) ∞  
    **Explanation:** Log grows slower.

48. lim_{x→3} (x^2 - 9)/(x - 3) = ?  
    A) 0  
    B) 3  
    C) 6  
    D) ∞  
    **Answer:** C) 6  
    **Explanation:** Factor.

49. lim_{x→0} (sin 5x)/x = ?  
    A) 0  
    B) 1  
    C) 5  
    D) ∞  
    **Answer:** C) 5  
    **Explanation:** sin 5x ≈ 5x.

50. lim_{x→0} (1 - cos 3x)/x^2 = ?  
    A) 0  
    B) 3/2  
    C) 9/2  
    D) ∞  
    **Answer:** C) 9/2  
    **Explanation:** 1 - cos 3x = 2 sin^2 (3x/2), so (2 * (3x/2)^2 ) / x^2 = (2 * 9x^2 /4 ) / x^2 = (9/2).

51. lim_{x→0} (e^{4x} - 1)/x = ?  
    A) 0  
    B) 1  
    C) 4  
    D) ∞  
    **Answer:** C) 4  
    **Explanation:** Standard.

52. lim_{x→0} (ln(1 + 4x))/x = ?  
    A) 0  
    B) 1  
    C) 4  
    D) ∞  
    **Answer:** C) 4  
    **Explanation:** Standard.

53. lim_{x→0} (4^x - 1)/x = ?  
    A) 0  
    B) ln 4  
    C) 1  
    D) ∞  
    **Answer:** B) ln 4  
    **Explanation:** Standard.

54. lim_{x→∞} (4x + 1)/(x - 1) = ?  
    A) 0  
    B) 1  
    C) 4  
    D) ∞  
    **Answer:** C) 4  
    **Explanation:** Divide by x.

55. lim_{x→0} (sin 6x)/x = ?  
    A) 0  
    B) 1  
    C) 6  
    D) ∞  
    **Answer:** C) 6  
    **Explanation:** sin 6x ≈ 6x.

56. lim_{x→0} (cos 3x - 1)/x^2 = ?  
    A) 0  
    B) -3/2  
    C) -9/2  
    D) ∞  
    **Answer:** C) -9/2  
    **Explanation:** Derivative.

57. lim_{x→∞} x^3 / e^x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** Exponential dominates.

58. lim_{x→0+} ln x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** D) -∞  
    **Explanation:** As x→0+, ln x → -∞.

59. lim_{x→∞} x / x^2 = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** 1/x →0.

60. lim_{x→4} (x^2 - 16)/(x - 4) = ?  
    A) 0  
    B) 4  
    C) 8  
    D) ∞  
    **Answer:** C) 8  
    **Explanation:** Factor.

61. lim_{x→0} (tan 3x)/x = ?  
    A) 0  
    B) 1  
    C) 3  
    D) ∞  
    **Answer:** C) 3  
    **Explanation:** tan 3x ≈ 3x.

62. lim_{x→0} (1 - cos 4x)/x^2 = ?  
    A) 0  
    B) 2  
    C) 4  
    D) ∞  
    **Answer:** C) 4  
    **Explanation:** 1 - cos 4x = 2 sin^2 2x, so 2 (sin 2x / 2x)^2 * 4x^2 / x^2 = 2*1*4 =8? Wait, (1 - cos 4x)/x^2 = 2 sin^2 2x / x^2 = 2 (2x)^2 / x^2 = 8, yes 8.

Wait, sin 2x ≈ 2x, sin^2 2x ≈ 4x^2, so 2*4x^2 / x^2 =8.

Yes.

63. lim_{x→0} (e^{5x} - 1)/x = ?  
    A) 0  
    B) 1  
    C) 5  
    D) ∞  
    **Answer:** C) 5  
    **Explanation:** Standard.

64. lim_{x→0} (ln(1 + 5x))/x = ?  
    A) 0  
    B) 1  
    C) 5  
    D) ∞  
    **Answer:** C) 5  
    **Explanation:** Standard.

65. lim_{x→0} (5^x - 1)/x = ?  
    A) 0  
    B) ln 5  
    C) 1  
    D) ∞  
    **Answer:** B) ln 5  
    **Explanation:** Standard.

66. lim_{x→∞} (5x + 1)/(x - 1) = ?  
    A) 0  
    B) 1  
    C) 5  
    D) ∞  
    **Answer:** C) 5  
    **Explanation:** Divide by x.

67. lim_{x→0} (sin 7x)/x = ?  
    A) 0  
    B) 1  
    C) 7  
    D) ∞  
    **Answer:** C) 7  
    **Explanation:** sin 7x ≈ 7x.

68. lim_{x→0} (cos 4x - 1)/x^2 = ?  
    A) 0  
    B) -2  
    C) -8  
    D) ∞  
    **Answer:** C) -8  
    **Explanation:** Derivative.

69. lim_{x→∞} x^4 / e^x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** Exponential dominates.

70. lim_{x→0+} 1/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** C) ∞  
    **Explanation:** As x→0+, 1/x → ∞.

71. lim_{x→∞} ln x / x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** Log grows slower.

72. lim_{x→5} (x^2 - 25)/(x - 5) = ?  
    A) 0  
    B) 5  
    C) 10  
    D) ∞  
    **Answer:** C) 10  
    **Explanation:** Factor.

73. lim_{x→0} (cot x)/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** C) ∞  
    **Explanation:** cot x = 1/tan x → ∞ as x→0.

74. lim_{x→0} (1 - cos 5x)/x^2 = ?  
    A) 0  
    B) 5/2  
    C) 25/2  
    D) ∞  
    **Answer:** C) 25/2  
    **Explanation:** 1 - cos 5x = 2 sin^2 (5x/2), so 2 (5x/2)^2 / x^2 = 2 * 25x^2 /4 / x^2 = (50/4) = 25/2.

75. lim_{x→0} (e^{6x} - 1)/x = ?  
    A) 0  
    B) 1  
    C) 6  
    D) ∞  
    **Answer:** C) 6  
    **Explanation:** Standard.

76. lim_{x→0} (ln(1 + 6x))/x = ?  
    A) 0  
    B) 1  
    C) 6  
    D) ∞  
    **Answer:** C) 6  
    **Explanation:** Standard.

77. lim_{x→0} (6^x - 1)/x = ?  
    A) 0  
    B) ln 6  
    C) 1  
    D) ∞  
    **Answer:** B) ln 6  
    **Explanation:** Standard.

78. lim_{x→∞} (6x + 1)/(x - 1) = ?  
    A) 0  
    B) 1  
    C) 6  
    D) ∞  
    **Answer:** C) 6  
    **Explanation:** Divide by x.

79. lim_{x→0} (sin 8x)/x = ?  
    A) 0  
    B) 1  
    C) 8  
    D) ∞  
    **Answer:** C) 8  
    **Explanation:** sin 8x ≈ 8x.

80. lim_{x→0} (cos 5x - 1)/x^2 = ?  
    A) 0  
    B) -5/2  
    C) -25/2  
    D) ∞  
    **Answer:** C) -25/2  
    **Explanation:** Derivative.

81. lim_{x→∞} x^5 / e^x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** A) 0  
    **Explanation:** Exponential dominates.

82. lim_{x→0-} 1/x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** D) -∞  
    **Explanation:** As x→0-, 1/x → -∞.

83. lim_{x→∞} x^2 / ln x = ?  
    A) 0  
    B) 1  
    C) ∞  
    D) -∞  
    **Answer:** C) ∞  
    **Explanation:** Polynomial grows faster.

### Continuity (Questions 84-167)

84. f is continuous at x=a if?  
    A) lim f(x) = f(a)  
    B) f(a) exists  
    C) lim f(x) exists  
    D) All  
    **Answer:** D) All  
    **Explanation:** Definition.

85. Removable discontinuity at x=a if?  
    A) lim f(x) exists but ≠ f(a)  
    B) lim doesn't exist  
    C) f(a) undefined  
    D) Jump  
    **Answer:** A) lim f(x) exists but ≠ f(a)  
    **Explanation:** Can be removed by redefining.

86. Jump discontinuity if?  
    A) Left and right limits differ  
    B) lim infinite  
    C) f(a) undefined  
    D) None  
    **Answer:** A) Left and right limits differ  
    **Explanation:** Definition.

87. Infinite discontinuity if?  
    A) lim = ∞  
    B) lim doesn't exist  
    C) f(a) = ∞  
    D) None  
    **Answer:** A) lim = ∞  
    **Explanation:** Vertical asymptote.

88. Polynomials are continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Everywhere.

89. Rational functions continuous except?  
    A) Denominator zero  
    B) Numerator zero  
    C) Both  
    D) None  
    **Answer:** A) Denominator zero  
    **Explanation:** Poles.

90. sin x continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Everywhere.

91. e^x continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Everywhere.

92. ln x continuous on?  
    A) (0,∞)  
    B) (-∞,0)  
    C) ℝ  
    D) [0,∞)  
    **Answer:** A) (0,∞)  
    **Explanation:** Domain.

93. |x| continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Everywhere.

94. f+g continuous if f,g continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Sum.

95. f g continuous if f,g continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Product.

96. f/g continuous if g≠0 and f,g continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Quotient.

97. g∘f continuous if f,g continuous?  
    A) Yes  
    B) No  
    C) Sometimes  
    D) Never  
    **Answer:** A) Yes  
    **Explanation:** Composite.

98. Intermediate Value Theorem applies to?  
    A) Continuous functions  
    B) Differentiable  
    C) Polynomials  
    D) None  
    **Answer:** A) Continuous functions  
    **Explanation:** On interval.

99. Extreme Value Theorem for?  
    A) Continuous on [a,b]  
    B) Differentiable  
    C) Polynomials  
    D) None  
    **Answer:** A) Continuous on [a,b]  
    **Explanation:** Has max/min.

100. f(x) = 1/x continuous at x=0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Discontinuous.

101. f(x) = [x] continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Jump at integers.

102. f(x) = x^2 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Polynomial.

103. f(x) = sin(1/x) for x≠0, 0 at 0, continuous at 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Oscillates.

104. f(x) = e^{-1/x^2} for x≠0, 0 at 0, continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Smooth.

105. Continuity implies differentiability?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Counterexamples.

106. Differentiability implies continuity?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

107. f(x) = |x| differentiable at 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Sharp corner.

108. f(x) = x^{1/3} differentiable at 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Vertical tangent.

109. f(x) = x^3 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

110. f(x) = 1/(x-1) continuous at x=1?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Pole.

111. f(x) = tan x continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Discontinuous at π/2 + kπ.

112. f(x) = cos x continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

113. f(x) = ln|x| continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** At 0.

114. f(x) = x sin(1/x) for x≠0, 0 at 0, continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Bounded.

115. f(x) = x^2 + 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

116. f(x) = √x continuous on?  
     A) [0,∞)  
     B) (-∞,0)  
     C) ℝ  
     D) (0,∞)  
     **Answer:** A) [0,∞)  
     **Explanation:** Domain.

117. f(x) = 1/x^2 continuous at x=0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** ∞.

118. f(x) = e^x continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

119. f(x) = x^4 - 3x^2 + 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Polynomial.

120. f(x) = sin x / x for x≠0, 1 at 0, continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Limit exists.

121. f(x) = (x^2 - 1)/(x - 1) for x≠1, 2 at 1, continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Removable.

122. f(x) = 1/x for x≠0, undefined at 0, continuous at 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** No.

123. f(x) = x^3 - 2x + 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

124. f(x) = e^{-x^2} continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

125. f(x) = ln(x+1) continuous on?  
     A) (-1,∞)  
     B) (-∞,1)  
     C) ℝ  
     D) [0,∞)  
     **Answer:** A) (-1,∞)  
     **Explanation:** Domain.

126. f(x) = 1/(x^2 + 1) continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

127. f(x) = [x] + {x} continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Fractional part.

128. f(x) = x^2 sin(1/x) for x≠0, 0 at 0, continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** x^2 damps oscillation.

129. f(x) = x^3 + x^2 - 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

130. f(x) = cos(1/x) for x≠0, 0 at 0, continuous at 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Oscillates between -1 and 1.

131. f(x) = √(x^2 + 1) continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

132. f(x) = 1/(x-2) continuous at x=2?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Pole.

133. f(x) = e^{x} continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

134. f(x) = x^5 - 4x^3 + 2 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

135. f(x) = sin x / (x^2 + 1) continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

136. f(x) = ln(x^2 + 1) continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

137. f(x) = 1/x for x≠0, continuous at 0 if defined as 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Limit doesn't exist.

138. f(x) = x^4 - 3x^2 + 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

139. f(x) = e^{-1/x^2} for x≠0, 0 at 0, continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

140. f(x) = √x continuous at x=0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Limit 0.

141. f(x) = 1/x continuous at x=1?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

142. f(x) = x^2 + 2x + 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

143. f(x) = cos x continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

144. f(x) = tan x continuous at x=π/4?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

145. f(x) = sec x continuous at x=0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

146. f(x) = csc x continuous at x=π/2?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Pole.

147. f(x) = x^3 - 6x^2 + 11x - 6 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

148. f(x) = e^x sin x continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

149. f(x) = ln(x + 2) continuous on?  
     A) (-2,∞)  
     B) (-∞,2)  
     C) ℝ  
     D) [0,∞)  
     **Answer:** A) (-2,∞)  
     **Explanation:** Domain.

150. f(x) = 1/(x^2 - 1) continuous at x=1?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Pole.

151. f(x) = x^2 e^{-x} continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

152. f(x) = sin(π/x) for x≠0, 0 at 0, continuous at 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Oscillates.

153. f(x) = x^3 + 3x^2 - 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

154. f(x) = e^{x^2} continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

155. f(x) = √(x - 1) continuous on?  
     A) [1,∞)  
     B) (-∞,1)  
     C) ℝ  
     D) (1,∞)  
     **Answer:** A) [1,∞)  
     **Explanation:** Domain.

156. f(x) = 1/(x^2 + 4) continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

157. f(x) = [x] continuous at x=2?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Integer.

158. f(x) = x sin x continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

159. f(x) = x^4 - 5x^2 + 4 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

160. f(x) = cos(1/x) for x≠0, 1 at 0, continuous at 0?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Oscillates.

161. f(x) = √(x^2 + 2x + 1) continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

162. f(x) = 1/(x-3) continuous at x=3?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Pole.

163. f(x) = e^{2x} continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

164. f(x) = x^6 - 3x^4 + 2x^2 - 1 continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

165. f(x) = sin x / x for x≠0, 1 at 0, continuous?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** A) Yes  
     **Explanation:** Yes.

166. f(x) = ln(x^2 - 4) continuous on?  
     A) (-∞,-2)∪(2,∞)  
     B) (-2,2)  
     C) ℝ  
     D) [0,∞)  
     **Answer:** A) (-∞,-2)∪(2,∞)  
     **Explanation:** Domain.

167. f(x) = 1/(x^2 - 9) continuous at x=3?  
     A) Yes  
     B) No  
     C) Sometimes  
     D) Never  
     **Answer:** B) No  
     **Explanation:** Pole.

### Differentiability (Questions 168-251)

168. f'(x) = lim_{h→0} [f(x+h) - f(x)]/h  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Definition.

169. (c)' = 0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Constant.

170. (x^n)' = n x^{n-1}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Power rule.

171. (cf)' = c f'  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Constant multiple.

172. (f+g)' = f' + g'  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Sum.

173. (f g)' = f' g + f g'  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Product.

174. (f/g)' = (f' g - f g') / g^2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Quotient.

175. (f∘g)' = f'(g) g'  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

176. d/dx sin x = cos x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

177. d/dx cos x = -sin x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

178. d/dx tan x = sec² x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

179. d/dx e^x = e^x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

180. d/dx ln x = 1/x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

181. d/dx a^x = a^x ln a  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

182. d/dx arcsin x = 1/√(1 - x²)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

183. d/dx arctan x = 1/(1 + x²)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

184. Implicit differentiation for x^2 + y^2 = 1, dy/dx = ?  
     A) -x/y  
     B) -y/x  
     C) x/y  
     D) y/x  
     **Answer:** A) -x/y  
     **Explanation:** 2x + 2y y' =0, y' = -x/y.

185. Logarithmic differentiation for y = x^x, ln y = ?  
     A) x ln x  
     B) ln x  
     C) x  
     D) 1  
     **Answer:** A) x ln x  
     **Explanation:** Yes.

186. Parametric: x = t^2, y = t^3, dy/dx = ?  
     A) (3t^2)/(2t) = 3t/2  
     B) (3t)/(2)  
     C) 3t^2 / 2t  
     D) 2t / 3t^2  
     **Answer:** A) (3t^2)/(2t) = 3t/2  
     **Explanation:** dy/dt = 3t^2, dx/dt = 2t, dy/dx = 3t^2 / 2t = 3t/2.

187. Higher derivative f''(x) = d/dx f'(x)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

188. (x^2)' = 2x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

189. (x^3)' = 3x^2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

190. (√x)' = 1/(2√x)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Power rule.

191. (1/x)' = -1/x^2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

192. (e^{2x})' = 2 e^{2x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

193. (ln 2x)' = 1/x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** d/dx ln u = (1/u) u', u=2x, u'=2, 2/(2x)=1/x.

194. (sin 2x)' = 2 cos 2x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

195. (cos 3x)' = -3 sin 3x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

196. (tan x)' = sec² x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

197. (cot x)' = -csc² x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

198. (sec x)' = sec x tan x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

199. (csc x)' = -csc x cot x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

200. (arc cos x)' = -1/√(1 - x²)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

201. (arc sec x)' = 1/(|x| √(x² - 1))  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

202. Implicit: x y = 1, dy/dx = ?  
     A) -1/x^2  
     B) -y/x  
     C) -1/y^2  
     D) -x/y  
     **Answer:** B) -y/x  
     **Explanation:** x dy + y dx =0, dy/dx = -y/x.

203. Log diff: y = (x^2 + 1)^3, ln y = 3 ln(x^2 +1), y' / y = 3 * 2x / (x^2 +1), y' = 3(x^2 +1)^2 * 2x / (x^2 +1) = 6x (x^2 +1)^2 / (x^2 +1) = 6x (x^2 +1)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

204. Parametric: x = cos t, y = sin t, dy/dx = ?  
     A) -cos t / sin t = -cot t  
     B) -sin t / cos t = -tan t  
     C) cos t / sin t = cot t  
     D) sin t / cos t = tan t  
     **Answer:** A) -cos t / sin t = -cot t  
     **Explanation:** dy/dt = cos t, dx/dt = -sin t, dy/dx = cos t / (-sin t) = -cot t.

205. (x^4)' = 4x^3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

206. (x^5)' = 5x^4  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

207. (x^{-1})' = -x^{-2}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

208. (e^{3x})' = 3 e^{3x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

209. (ln 3x)' = 1/x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar to 193.

210. (sin 4x)' = 4 cos 4x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

211. (cos 5x)' = -5 sin 5x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

212. (tan 2x)' = 2 sec² 2x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

213. (cot 3x)' = -3 csc² 3x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

214. (sec 4x)' = 4 sec 4x tan 4x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

215. (csc 5x)' = -5 csc 5x cot 5x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

216. (arc sin x)' = 1/√(1 - x²)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

217. (arc tan x)' = 1/(1 + x²)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

218. (arc cot x)' = -1/(1 + x²)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

219. Implicit: x^2 + y^2 = r^2, dy/dx = -x/y  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Circle.

220. Log diff: y = x^{sin x}, ln y = sin x ln x, y'/y = cos x ln x + sin x / x, y' = x^{sin x} (cos x ln x + sin x / x)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

221. Parametric: x = e^t, y = t^2, dy/dx = ?  
     A) 2t / e^t  
     B) e^t / 2t  
     C) 2t e^{-t}  
     D) t^2 / e^t  
     **Answer:** A) 2t / e^t  
     **Explanation:** dy/dt = 2t, dx/dt = e^t, dy/dx = 2t / e^t.

222. (x^6)' = 6x^5  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

223. (x^7)' = 7x^6  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

224. (x^{-2})' = -2x^{-3}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

225. (e^{4x})' = 4 e^{4x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

226. (ln 4x)' = 1/x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

227. (sin 6x)' = 6 cos 6x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

228. (cos 7x)' = -7 sin 7x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

229. (tan 8x)' = 8 sec² 8x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

230. (cot 9x)' = -9 csc² 9x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

231. (sec 10x)' = 10 sec 10x tan 10x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

232. (csc 11x)' = -11 csc 11x cot 11x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

233. (arc cos x)' = -1/√(1 - x²)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

234. (arc sec x)' = 1/(x √(x² - 1)) for x >1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

235. Implicit: y = sin x, dy/dx = cos x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Explicit.

236. Log diff: y = (x +1)^x, ln y = x ln(x+1), y'/y = ln(x+1) + x /(x+1), y' = (x+1)^x [ln(x+1) + x/(x+1)]  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

237. Parametric: x = t, y = t^2, dy/dx = 2t  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** dy/dt = 2t, dx/dt =1, dy/dx =2t.

238. (x^8)' = 8x^7  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

239. (x^9)' = 9x^8  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

240. (x^{-3})' = -3x^{-4}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

241. (e^{5x})' = 5 e^{5x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

242. (ln 5x)' = 1/x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

243. (sin 12x)' = 12 cos 12x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

244. (cos 13x)' = -13 sin 13x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

245. (tan 14x)' = 14 sec² 14x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

246. (cot 15x)' = -15 csc² 15x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

247. (sec 16x)' = 16 sec 16x tan 16x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

248. (csc 17x)' = -17 csc 17x cot 17x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Chain.

249. (arc sin x)' = 1/√(1 - x²) for |x| <1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

250. (arc tan x)' = 1/(1 + x²) for all x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

251. Implicit: x^3 + y^3 = 3xy, dy/dx = (y - x^2)/(y^2 - x)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Differentiate: 3x^2 + 3y^2 y' = 3y + 3x y', 3y^2 y' - 3x y' = 3y - 3x^2, y' (3y^2 - 3x) = 3(y - x^2), y' = (y - x^2)/(y^2 - x).

### Maxima and Minima (Questions 252-335)

252. Critical points where f'(x) = 0 or undefined  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

253. Second derivative test: f'' >0 local min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

254. First derivative test: sign change + to - max  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

255. Absolute max/min on closed interval check endpoints  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

256. Rolle's theorem: f(a)=f(b), differentiable, then f'(c)=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

257. Mean value theorem: f'(c) = [f(b)-f(a)]/(b-a)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

258. Increasing if f' >0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

259. Decreasing if f' <0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

260. f(x) = x^2, min at x=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=2x=0, f''=2>0 min.

261. f(x) = -x^2, max at x=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-2x=0, f''=-2<0 max.

262. f(x) = x^3, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2=0 at 0, f''=6>0 min? Wait, inflection.

263. f(x) = x^4, min at x=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3=0, f''=12x^2>0 min.

264. f(x) = sin x, max at π/2, min at 3π/2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=cos x=0 at π/2, 3π/2, f''=-sin x at π/2 = -1<0 max, at 3π/2=1>0 min.

265. f(x) = cos x, max at 0, min at π  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-sin x=0 at 0,π, f''=-cos x at 0=-1<0 max, at π=1>0 min.

266. f(x) = e^x, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=e^x >0 always.

267. f(x) = ln x, no max/min on (0,∞)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=1/x >0.

268. f(x) = x^3 - 3x, max at x=-1, min at x=1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2-3=0, x=±1, f''=6x at -1=-6<0 max, at 1=6>0 min.

269. f(x) = x^4 - 2x^2, min at x=0, max at x=±1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3-4x=0, x=0,±1, f''=12x^2-4, at 0=-4<0 max? Wait, f(0)=0, f(1)=1-2=-1, f(-1)=-1, f(2)=16-8=8, so min at ±1, max at 0? Wait, f'' at 0= -4<0 max, at 1=12-4=8>0 min.

Wait, yes, local max at 0, local min at ±1.

270. f(x) = x^5 - 5x, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-5=0, x=1, f''=20x^3 at 1=20>0 min.

271. f(x) = x^6, min at x=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=6x^5=0, f''=30x^4>0 min.

272. f(x) = -x^4, max at x=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-4x^3=0, f''=-12x^2<0 max.

273. f(x) = sin 2x, max at π/4, min at 5π/4  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=2cos2x=0, 2x=π/2, 2x=3π/2, x=π/4, 3π/4, f''=-4sin2x at π/4=-4(-1)=4>0 min? Wait, sin2x at π/4=1, max at π/4, min at 3π/4.

Wait, f''(x)=-4sin2x, at π/4 sin(π/2)=1, -4*1=-4<0 max, at 3π/4 sin(3π/2)=-1, -4*(-1)=4>0 min.

Yes.

274. f(x) = cos 3x, max at 0, min at π/3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-3sin3x=0, 3x=0,π, x=0,π/3, f''=-9cos3x at 0=-9<0 max, at π/3=-9cosπ=-9(-1)=9>0 min.

275. f(x) = e^{-x}, max at x=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-e^{-x}=0 never, but as x→∞, min at ∞, max at 0? No max/min, decreasing.

Wait, no critical points, no local max/min.

276. f(x) = ln(x+1), no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=1/(x+1)>0.

277. f(x) = x^2 - 4x + 3, min at x=2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=2x-4=0, x=2, f''=2>0 min.

278. f(x) = -x^2 + 6x - 5, max at x=3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-2x+6=0, x=3, f''=-2<0 max.

279. f(x) = x^3 - 6x^2 + 9x, max at x=1, min at x=3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2-12x+9=0, (x-1)(x-3)=0, f''=6x-12 at 1=-6<0 max, at 3=6>0 min.

280. f(x) = x^4 - 4x^2, min at x=0, max at x=±1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** As above.

281. f(x) = x^5 - 5x^4, min at x=4  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-20x^3=5x^3(x-4)=0, x=0,4, f''=20x^3-60x^2=20x^2(x-3), at 4=20*16*1>0 min.

282. f(x) = x^6 - 6x^4, min at x=0, max at x=±1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=6x^5-24x^3=6x^3(x^2-4)=0, x=0,±2, f''=30x^4-72x^2=6x^2(5x^2-12), at 0=0 inconclusive, at 2=6*4*(20-12)=24*8>0 min, at -2 same, at ±1 f''=6*1*(5-12)=6*(-7)<0 max.

283. f(x) = sin x + cos x, max at π/4  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=cos x - sin x=0, x=π/4, f''=-sin x - cos x at π/4=-1-1=-2<0 max.

284. f(x) = e^x - x, min at x=0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=e^x -1=0, x=0, f''=e^x>0 min.

285. f(x) = x ln x, min at x=1/e  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=ln x +1=0, x=1/e, f''=1/x>0 min.

286. f(x) = x^2 e^{-x}, max at x=2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=2x e^{-x} - x^2 e^{-x}=x e^{-x}(2 - x)=0, x=0,2, f'' complex, at 2 max.

287. f(x) = x^3 - 3x^2 - 9x + 1, max at x=-1, min at x=3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2-6x-9=0, x=3, -1, f''=6x-6 at -1=-12<0 max, at 3=12>0 min.

288. f(x) = x^4 - 8x^2 + 1, min at x=0, max at x=±2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3-16x=0, x=0,±2, f''=12x^2-16 at 0=-16<0 max, at 2=48-16=32>0 min.

289. f(x) = x^5 - 10x^3, max at x=0, min at x=±2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-30x^2=5x^2(x^2-6)=0, x=0,±√6, f''=20x^3-60x=20x(x^2-3), at 0=0, at √6>0 min, at -√6<0 max? Wait, local max at -√6, local min at √6, at 0 f''=0, inflection.

290. f(x) = x^6 - 9x^4, min at x=0, max at x=±√(9/2)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=6x^5-36x^3=6x^3(x^2-6)=0, x=0,±√6, f''=30x^4-108x^2=6x^2(5x^2-18), at 0=0, at √6=6*6*(30-18)=36*12>0 min, at -√6 same.

291. f(x) = sin 3x, max at π/6, min at 5π/6  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3cos3x=0, 3x=π/2, 3x=3π/2, x=π/6, π/2, f''=-9sin3x at π/6=-9*1=-9<0 max, at π/2=-9*0=0, at 5π/6=5π/6 *3=5π/2, sin(5π/2)=-1, -9*(-1)=9>0 min.

292. f(x) = cos 4x, max at 0, min at π/4  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-4sin4x=0, 4x=0,π, x=0,π/4, f''=-16cos4x at 0=-16<0 max, at π/4=-16cosπ=-16(-1)=16>0 min.

293. f(x) = e^{-2x}, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Decreasing.

294. f(x) = ln(x^2 +1), no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=2x/(x^2+1)>0 for x>0, <0 for x<0, but no critical points.

295. f(x) = x^3 - 9x, max at x=-√3, min at x=√3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2-9=0, x=±√3, f''=6x at √3>0 min, at -√3<0 max.

296. f(x) = -x^3 + 3x, max at x=1, min at x=-1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-3x^2+3=0, x=±1, f''=-6x at 1=-6<0 max, at -1=6>0 min.

297. f(x) = x^4 - 2x^2 + 1, min at x=0, max at x=±1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3-4x=0, x=0,±1, f''=12x^2-4 at 0=-4<0 max, at 1=8>0 min.

298. f(x) = x^5 - 5x^3 + 4x, max at x=1, min at x=-1, inflection at 0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-15x^2+4=0, complex, but known.

299. f(x) = x^6 - 3x^4 + 2x^2, min at x=0, max at x=±1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=6x^5-12x^3+4x=0, x=0,±1,±2, f'' at 0=4>0 min, at 1=30-36+4=-2<0 max, at 2=240-288+4=-44<0 max? Wait, local max at ±1, local min at 0, and at ±2.

300. f(x) = sin x - x, max at 0? No, decreasing, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** B) False  
     **Explanation:** f'(x)=cos x -1 ≤0, equal at 0, but f''=-sin x=0 at 0, higher derivatives.

301. f(x) = x e^{-x}, max at x=1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=e^{-x} - x e^{-x}=e^{-x}(1-x)=0, x=1, f''= -e^{-x} + (1-x)e^{-x} = e^{-x} (-1 +1 -x) = -x e^{-x} at 1=-1<0 max.

302. f(x) = x^2 ln x, min at x=1/e  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=2x ln x + x^2 *1/x = x(2 ln x +1)=0, x=1/e, f'' complex >0 min.

303. f(x) = x^3 e^{-x}, max at x=3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2 e^{-x} - x^3 e^{-x}=x^2 e^{-x}(3 - x)=0, x=0,3, f'' at 3 >0 min? Wait, local max at 3? f''(x)=6x e^{-x} - 3x^2 e^{-x} - 2x^3 e^{-x} + x^3 e^{-x} = e^{-x} (6x - 3x^2 - 2x^3 + x^3) = e^{-x} (6x - 3x^2 - x^3) at 3=18-27-27=-36<0 max.

304. f(x) = x^4 - 4x^3 + 6x^2 - 4x + 1, min at x=1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3-12x^2+12x-4=0, (x-1)^3=0, x=1, f''=12x^2-24x+12 at 1=12-24+12=0, higher.

305. f(x) = x^5 - 5x^4 + 5x^3, min at x=3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-20x^3+15x^2=5x^2(x^2-4x+3)=0, x=0,1,3, f'' at 3>0 min.

306. f(x) = x^6 - 6x^5 + 15x^4 - 20x^3 + 15x^2 - 6x + 1, min at x=1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** (x-1)^6=0, x=1, f''>0 min.

307. f(x) = sin 5x, max at π/10, min at 3π/10  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5cos5x=0, 5x=π/2, x=π/10, f''=-25sin5x at π/10=-25*1=-25<0 max.

308. f(x) = cos 6x, max at 0, min at π/6  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-6sin6x=0, 6x=0, x=0, f''=-36cos6x at 0=-36<0 max.

309. f(x) = e^{-3x}, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Decreasing.

310. f(x) = ln(x^3 +1), no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Increasing.

311. f(x) = x^3 - 12x, max at x=-2, min at x=2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2-12=0, x=±2, f''=6x at 2>0 min, at -2<0 max.

312. f(x) = -x^3 + 12x, max at x=2, min at x=-2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-3x^2+12=0, x=±2, f''=-6x at 2=-12<0 max, at -2=12>0 min.

313. f(x) = x^4 - 4x^2 + 3, min at x=0, max at x=±1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3-8x=0, x=0,±√2, f''=12x^2-8 at 0=-8<0 max, at √2=12*2-8=16>0 min.

314. f(x) = x^5 - 10x^2, max at x=0, min at x=±2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-20x=0, x=0,±2, f''=20x^3-20=20(x^3-1), at 0=-20<0 max, at 2=20(8-1)=140>0 min.

315. f(x) = x^6 - 9x^2, min at x=0, max at x=±√(3/2)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=6x^5-18x=0, x=0,±√3, f'' at 0=-18<0 max, at √3>0 min.

316. f(x) = sin 7x, max at π/14, min at 3π/14  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

317. f(x) = cos 8x, max at 0, min at π/8  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

318. f(x) = e^{-4x}, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Decreasing.

319. f(x) = ln(x^4 +1), no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Increasing.

320. f(x) = x^3 - 15x, max at x=-√5, min at x=√5  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2-15=0, x=±√5, f''=6x at √5>0 min, at -√5<0 max.

321. f(x) = -x^3 + 15x, max at x=√5, min at x=-√5  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-3x^2+15=0, x=±√5, f''=-6x at √5=-6√5<0 max, at -√5=6√5>0 min.

322. f(x) = x^4 - 6x^2 + 1, min at x=0, max at x=±√3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3-12x=0, x=0,±√3, f''=12x^2-12 at 0=-12<0 max, at √3=36-12=24>0 min.

323. f(x) = x^5 - 15x, max at x=0, min at x=±√3  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-15=0, x=0,± (15/5)^{1/4} wait, 5x^4=15, x^4=3, x=±3^{1/4}, f'' at 0=-15<0 max, at 3^{1/4}>0 min.

324. f(x) = x^6 - 12x^2, min at x=0, max at x=±2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=6x^5-24x=0, x=0,±2, f'' at 0=-24<0 max, at 2>0 min.

325. f(x) = sin 9x, max at π/18, min at 5π/18  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

326. f(x) = cos 10x, max at 0, min at π/10  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

327. f(x) = e^{-5x}, no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Decreasing.

328. f(x) = ln(x^5 +1), no max/min  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Increasing.

329. f(x) = x^3 - 18x, max at x=-√6, min at x=√6  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=3x^2-18=0, x=±√6, f''=6x at √6>0 min, at -√6<0 max.

330. f(x) = -x^3 + 18x, max at x=√6, min at x=-√6  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=-3x^2+18=0, x=±√6, f''=-6x at √6=-6√6<0 max, at -√6=6√6>0 min.

331. f(x) = x^4 - 8x^2 + 2, min at x=0, max at x=±2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=4x^3-16x=0, x=0,±2, f''=12x^2-16 at 0=-16<0 max, at 2=48-16=32>0 min.

332. f(x) = x^5 - 20x, max at x=0, min at x=±2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=5x^4-20=0, x=0,± (4)^{1/4}, f'' at 0=-20<0 max, at 2>0 min.

333. f(x) = x^6 - 15x^2, min at x=0, max at x=±√(5/2)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f'(x)=6x^5-30x=0, x=0,±√5, f'' at 0=-30<0 max, at √5>0 min.

334. f(x) = sin 11x, max at π/22, min at 3π/22  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

335. f(x) = cos 12x, max at 0, min at π/12  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Similar.

### Integration (Questions 336-419)

336. ∫ c dx = c x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Constant.

337. ∫ x^n dx = x^{n+1}/(n+1) + C for n ≠ -1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Power rule.

338. ∫ e^x dx = e^x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

339. ∫ 1/x dx = ln|x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

340. ∫ sin x dx = -cos x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

341. ∫ cos x dx = sin x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

342. ∫ sec² x dx = tan x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

343. ∫ csc² x dx = -cot x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

344. ∫ sec x tan x dx = sec x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

345. ∫ csc x cot x dx = -csc x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

346. ∫ tan x dx = ln|sec x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

347. ∫ cot x dx = ln|sin x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

348. ∫ sec x dx = ln|sec x + tan x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

349. ∫ csc x dx = ln|csc x - cot x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

350. ∫ a^x dx = a^x / ln a + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

351. ∫ 1/√(1 - x²) dx = arcsin x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

352. ∫ 1/(1 + x²) dx = arctan x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

353. ∫ -1/√(1 - x²) dx = arccos x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

354. ∫ 1/√(x² - 1) dx = ln|x + √(x² - 1)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

355. ∫ 1/√(x² + 1) dx = ln|x + √(x² + 1)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

356. Integration by parts: ∫ u dv = u v - ∫ v du  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

357. Substitution: ∫ f(g(x)) g'(x) dx = ∫ f(u) du  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

358. ∫_a^b f(x) dx = F(b) - F(a)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Fundamental theorem.

359. ∫_a^b f(x) dx = - ∫_b^a f(x) dx  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

360. ∫_a^a f(x) dx = 0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

361. ∫_a^b (f + g) = ∫f + ∫g  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

362. ∫_a^b c f = c ∫_a^b f  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

363. ∫_a^c f + ∫_c^b f = ∫_a^b f  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

364. ∫ sin² x dx = (x/2 - sin2x/4) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

365. ∫ cos² x dx = (x/2 + sin2x/4) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

366. ∫ sin^3 x dx = -cos x + cos^3 x /3 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

367. ∫ cos^3 x dx = sin x - sin^3 x /3 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

368. ∫ tan^2 x dx = tan x - x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

369. ∫ cot^2 x dx = -cot x - x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

370. ∫ sec^3 x dx = (sec x tan x + ln|sec x + tan x|) /2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Reduction.

371. ∫ csc^3 x dx = (-csc x cot x + ln|csc x - cot x|) /2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Reduction.

372. ∫ e^{a x} dx = e^{a x} / a + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

373. ∫ x e^{a x} dx = (a x - 1) e^{a x} / a^2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

374. ∫ x^2 e^{a x} dx = (a^2 x^2 - 2 a x + 2) e^{a x} / a^3 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

375. ∫ ln x dx = x ln x - x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

376. ∫ x ln x dx = (x^2 /2) ln x - x^2 /4 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

377. ∫ sin a x dx = -cos a x / a + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

378. ∫ cos a x dx = sin a x / a + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

379. ∫ e^{a x} sin b x dx = e^{a x} (a sin b x - b cos b x) / (a^2 + b^2) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

380. ∫ e^{a x} cos b x dx = e^{a x} (a cos b x + b sin b x) / (a^2 + b^2) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

381. ∫ 1/(a^2 + x^2) dx = (1/a) arctan(x/a) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

382. ∫ 1/(x^2 - a^2) dx = (1/(2a)) ln|(x-a)/(x+a)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Partial fractions.

383. ∫ 1/√(a^2 - x^2) dx = arcsin(x/a) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

384. ∫ 1/√(x^2 + a^2) dx = ln|x + √(x^2 + a^2)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

385. ∫ 1/√(x^2 - a^2) dx = ln|x + √(x^2 - a^2)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

386. ∫ √(a^2 - x^2) dx = (x/2) √(a^2 - x^2) + (a^2/2) arcsin(x/a) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

387. ∫ √(x^2 + a^2) dx = (x/2) √(x^2 + a^2) + (a^2/2) ln|x + √(x^2 + a^2)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

388. ∫ √(x^2 - a^2) dx = (x/2) √(x^2 - a^2) - (a^2/2) ln|x + √(x^2 - a^2)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

389. ∫ x sin x dx = -x cos x + sin x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

390. ∫ x cos x dx = x sin x + cos x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

391. ∫ x^2 sin x dx = -x^2 cos x + 2 x sin x + 2 cos x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

392. ∫ x^2 cos x dx = x^2 sin x + 2 x cos x - 2 sin x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

393. ∫ x e^x dx = x e^x - e^x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

394. ∫ x^2 e^x dx = x^2 e^x - 2 x e^x + 2 e^x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

395. ∫ ln x dx = x ln x - x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

396. ∫ x ln x dx = (x^2 /2) ln x - x^2 /4 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

397. ∫ (ln x)^2 dx = x (ln x)^2 - 2 x ln x + 2 x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

398. ∫ sin^2 a x dx = x/2 - sin(2 a x)/(4 a) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

399. ∫ cos^2 a x dx = x/2 + sin(2 a x)/(4 a) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

400. ∫ sin a x cos b x dx = [a cos b x sin a x - b sin b x cos a x] / (a^2 - b^2) + C if a ≠ b  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Product.

401. ∫ sin a x sin b x dx = [sin (a-b) x]/(2(a-b)) - [sin (a+b) x]/(2(a+b)) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Product.

402. ∫ cos a x cos b x dx = [sin (a-b) x]/(2(a-b)) + [sin (a+b) x]/(2(a+b)) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Product.

403. ∫ tan x dx = - ln|cos x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

404. ∫ cot x dx = ln|sin x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

405. ∫ sec x dx = ln|tan x + sec x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

406. ∫ csc x dx = ln|tan (x/2)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

407. ∫ 1/(x ln x) dx = ln|ln x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Substitution.

408. ∫ x^n ln x dx = x^{n+1} [(n+1) ln x - 1] / (n+1)^2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

409. ∫ e^{a x} sin b x dx = e^{a x} (a sin b x - b cos b x) / (a^2 + b^2) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

410. ∫ e^{a x} cos b x dx = e^{a x} (a cos b x + b sin b x) / (a^2 + b^2) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

411. ∫ 1/(a + b cos x) dx = (2/√(a^2 - b^2)) arctan [...] + C if a > |b|  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

412. ∫ 1/(a + b sin x) dx = (1/√(b^2 - a^2)) ln|...| + C if b > |a|  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

413. ∫ √(a^2 - x^2) dx = (x/2) √(a^2 - x^2) + (a^2/2) arcsin(x/a) + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

414. ∫ √(x^2 + a^2) dx = (x/2) √(x^2 + a^2) + (a^2/2) ln|x + √(x^2 + a^2)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

415. ∫ √(x^2 - a^2) dx = (x/2) √(x^2 - a^2) - (a^2/2) ln|x + √(x^2 - a^2)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Trig sub.

416. ∫ x sin a x dx = (sin a x - a x cos a x)/a^2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

417. ∫ x cos a x dx = (cos a x + a x sin a x)/a^2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

418. ∫ x^2 sin a x dx = (2 - a^2 x^2) cos a x / a^3 + 2 a x sin a x / a^2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

419. ∫ x^2 cos a x dx = (a^2 x^2 - 2) sin a x / a^3 + 2 a x cos a x / a^2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

### Differential Equations (Questions 420-500)

420. Order of dy/dx = x is 1  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

421. Degree of (dy/dx)^2 + y = 0 is 2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

422. General solution has arbitrary constants equal to order  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

423. Particular solution specific values  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

424. Variable separable: dy/dx = f(x) g(y), ∫ g(y) dy = ∫ f(x) dx  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

425. Homogeneous: dy/dx = f(y/x), let y = v x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

426. Linear first order: dy/dx + P y = Q, I.F. e^{∫P dx}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

427. Bernoulli: dy/dx + P y = Q y^n, let z = y^{1-n}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

428. Exact: M dx + N dy = 0, ∂M/∂y = ∂N/∂x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

429. Second order linear: y'' + P y' + Q y = 0, char eq r^2 + P r + Q = 0  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

430. Distinct real roots: y = A e^{r1 x} + B e^{r2 x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

431. Repeated root: y = (A + B x) e^{r x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

432. Complex roots: y = e^{a x} (A cos b x + B sin b x)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

433. Cauchy-Euler: x^2 y'' + a x y' + b y = 0, assume y = x^r  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

434. Wronskian for linear independence  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

435. Variation of parameters for particular solution  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

436. dy/dx = k y, y = A e^{k x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Exponential growth/decay.

437. dy/dx = k (y - a), y = a + B e^{k x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Logistic or asymptote.

438. y'' = k, y = (k/2) x^2 + A x + B  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Constant acceleration.

439. y'' + ω^2 y = 0, y = A cos ω x + B sin ω x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** SHM.

440. y'' - k y = 0, y = A e^{√k x} + B e^{-√k x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Hyperbolic.

441. dy/dx + y tan x = sec x, linear  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

442. (x^2 + 1) dy/dx + 2 x y = 0, homogeneous  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** f(y/x).

443. dy/dx = (x + y + 1)/(x + y - 1), homogeneous  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

444. (2x + y) dx + (x + 2y) dy = 0, exact  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** ∂M/∂y =2, ∂N/∂x=1, no.

Wait, ∂M/∂y =1, ∂N/∂x=1, yes.

445. dy/dx = y^2 / x^2, separable  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

446. dy/dx + y = e^x, linear  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

447. dy/dx = y (1 - y), separable  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Logistic.

448. y'' + 2 y' + y = 0, char r^2 + 2r +1 =0, r=-1 repeated, y = (A + B x) e^{-x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

449. y'' + y = 0, y = A cos x + B sin x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

450. y'' - 2 y' + y = 0, same as above  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

451. x^2 y'' - 2 x y' + 2 y = 0, Cauchy-Euler, r(r-1) -2 r +2=0, r^2 -3r +2=0, r=1,2, y = A x + B x^2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

452. dy/dx = sin x, y = -cos x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

453. dy/dx = e^x, y = e^x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

454. dy/dx = 1/x, y = ln x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

455. dy/dx = x, y = x^2 /2 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

456. dy/dx = x^2, y = x^3 /3 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

457. dy/dx = √x, y = (2/3) x^{3/2} + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

458. dy/dx = 1/√x, y = 2 √x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

459. dy/dx = e^{-x}, y = -e^{-x} + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

460. dy/dx = sin 2x, y = - (1/2) cos 2x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

461. dy/dx = cos 3x, y = (1/3) sin 3x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

462. dy/dx = tan x, y = - ln|cos x| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

463. dy/dx = sec^2 x, y = tan x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

464. dy/dx = csc^2 x, y = - cot x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

465. dy/dx = sec x tan x, y = sec x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

466. dy/dx = csc x cot x, y = - csc x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

467. dy/dx = 1/(1 + x^2), y = arctan x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

468. dy/dx = 1/√(1 - x^2), y = arcsin x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

469. dy/dx = -1/√(1 - x^2), y = arccos x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

470. dy/dx = 1/√(x^2 - 1), y = ln|x + √(x^2 - 1)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

471. dy/dx = 1/√(x^2 + 1), y = ln|x + √(x^2 + 1)| + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

472. dy/dx = x e^x, y = x e^x - e^x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

473. dy/dx = x sin x, y = sin x - x cos x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

474. dy/dx = x cos x, y = cos x + x sin x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

475. dy/dx = ln x, y = x ln x - x + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

476. dy/dx = x ln x, y = (x^2 /2) ln x - x^2 /4 + C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Parts.

477. dy/dx = (x + y + 1)^2, homogeneous? No, but solvable.  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** B) False  
     **Explanation:** Not homogeneous.

478. dy/dx = y/x, homogeneous, y = C x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

479. dy/dx = (x^2 + y^2)/x y, homogeneous, let y = v x, v + x dv/dx = (1 + v^2)/v, etc.  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

480. dy/dx + 2y = 4, linear, I.F. e^{2x}, y = 2 + C e^{-2x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

481. dy/dx = y^2, separable, 1/y^2 dy = dx, -1/y = x + C, y = -1/(x + C)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

482. dy/dx = e^{x+y}, separable, e^{-y} dy = e^x dx, -e^{-y} = e^x + C, e^{-y} = -e^x - C  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

483. (x + y) dx + (x - y) dy = 0, homogeneous, let y = v x, (1 + v) + x dv/dx (1 - v) = 0, etc.  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

484. y dx - x dy = 0, exact, M=y, N=-x, ∂M/∂y=1, ∂N/∂x=-1, no. Wait, homogeneous.  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** B) False  
     **Explanation:** Not exact.

485. y'' + 4y = 0, y = A cos 2x + B sin 2x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

486. y'' - 9y = 0, y = A e^{3x} + B e^{-3x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

487. y'' + 6y' + 9y = 0, r^2 +6r +9=0, r=-3 repeated, y = (A + B x) e^{-3x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

488. y'' + 2y' + 5y = 0, r^2 +2r +5=0, r=-1 ± 2i, y = e^{-x} (A cos 2x + B sin 2x)  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

489. x^2 y'' + x y' - y = 0, Cauchy, r(r-1) + r -1 =0, r^2 -1=0, r=±1, y = A x + B /x  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

490. x^2 y'' - 3 x y' + 4 y = 0, r(r-1) -3 r +4=0, r^2 -4r +4=0, r=2 repeated, y = (A + B ln x) x^2  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

491. dy/dx = k y, population growth  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

492. dy/dx = k (M - y), limited growth  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

493. y'' = -ω^2 y, SHM  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

494. y'' = g, free fall  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

495. y'' + b y' + k y = 0, damped oscillation  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

496. dy/dx = v, dv/dx = a, kinematics  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

497. Heat equation partial, but for ODE, dy/dx = -k (y - T), Newton's law  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

498. Logistic: dy/dx = r y (1 - y/K), separable  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

499. Predator-prey: dx/dt = a x - b x y, dy/dt = -c y + d x y, system  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.

500. Radioactive decay: dy/dx = -λ y, y = y0 e^{-λ x}  
     A) True  
     B) False  
     C) Sometimes  
     D) Never  
     **Answer:** A) True  
     **Explanation:** Yes.
