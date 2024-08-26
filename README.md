# cardai

\[ \sigma^2 = M \cdot p(a) \cdot p(b) \cdot (1 - p(a) \cdot p(b)) \]
\[ \sigma = \sqrt{M \cdot p(a) \cdot p(b) \cdot (1 - p(a) \cdot p(b))} \]

#### 4. Convert to Normal Distribution (if appropriate)

For large \(M\), we can use the normal distribution to approximate the binomial distribution:
\[ Z = \frac{N_{\text{observed}} - \mu}{\sigma} = \frac{N_{\text{observed}} - M \cdot p(a) \cdot p(b)}{\sqrt{M \cdot p(a) \cdot p(b) \cdot (1 - p(a) \cdot p(b))}} \]
