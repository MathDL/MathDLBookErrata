In this file we will keep errata associated to the book ["Mathematical Foundations of Deep Leanring Models and Algorithms"](https://bookstore.ams.org/view?ProductCode=GSM/252&_zs=hX3BH1&_zl=C09q7) published by the American Mathematical Society (AMS) in 2025.

1. Page 11: There is an $m$ missing at the formula right after (1.9). That formula should read\
   $`\Lambda(\theta)\overset{\text{def}}{=} \frac{1}{M}\sum_{m=1}^M \ell_{y_{m}}(\mathfrak{m}(x_{m};\theta)), `$
2. Page 15: The first bullet point after (1.11) should read
   "If the data set is too small and the model $\mathfrak{m}(x;\theta)$ is not trained on sufficient enough data points, then the model will have large variance."
3. Page 219: Around the middle of the page, it should be $\mathfrak{m}(\textbf{X};\theta)$ instead of $\mathfrak{m}(\textbf{X},\theta).$
4. Page 462: Equation (24.1) should read $z_{1}=\mathfrak{m}_{1}(x;\theta)$. There is an extra "=".
5. Page 462: Three lines before the end of the page there is a subscript $\ell-1$ missing on $z$ in the formula. The formula should read\
   $\frac{\partial\mathfrak{m}_{\ell}}{\partial\theta}\left(z_{\ell-1},x;\theta\right)=\sigma'\left(W^{\ell}_{z}z_{\ell-1}+W^{\ell}_{x}x\right)\odot W^{\ell}_{z}$.


Last updated: December 15, 2025
