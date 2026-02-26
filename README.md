In this file we will keep errata associated to the book ["Mathematical Foundations of Deep Leanring Models and Algorithms"](https://bookstore.ams.org/view?ProductCode=GSM/252&_zs=hX3BH1&_zl=C09q7) published by the American Mathematical Society (AMS) in 2025.

1. Page xvii: In the "Norms" block of the Notation section, there is an absolute value missing from the definition of the $||x||_{q}$ norm\
   $`\|x\|_{q}=\left(\sum_{i=1}^{D}|x_{i}|^{q}\right)^{1/q}`$
2. Page 6: There is an absolute value missing from the definition of the $||x||_{q}$ norm\
   $`\|x\|_{q}=\left(\sum_{i=1}^{D}|x_{i}|^{q}\right)^{1/q}`$    
1. Page 11: There is an $m$ missing at the formula right after (1.9). That formula should read\
   $`\Lambda(\theta)\overset{\text{def}}{=} \frac{1}{M}\sum_{m=1}^M \ell_{y_{m}}(\mathfrak{m}(x_{m};\theta)), `$
2. Page 15: The first bullet point after (1.11) should read
   "If the data set is too small and the model $\mathfrak{m}(x;\theta)$ is not trained on sufficient enough data points, then the model will have large variance."
3. Page 52-53 in Section 3.6: The variable $m$ can be thought of as $w$ to match previous notation, but technically speaking $m$ is also correct.
4. Page 54: In the third display $w$ should be capital $W$, i.e.\
   $`\mathfrak{m}(x;\theta)=S_{softmax}(Wx+b),`$   
5. Page 95: The second formula from the end should read\
   $`\frac{\partial\Lambda}{\partial Z}=\frac{\partial\Lambda}{\partial H}\frac{\partial H}{\partial Z}=...`$
6. Page 96: The expression of the last equality of the last display of the page should read $=w_{11}^{2}x_{1}^{1}+w_{21}^{2}x_{2}^{1}+ B^{2}.$ Namely, $x_{1}^{2}$ there should be $x_{1}^{1}$ and $x_{2}^{2}$ there should be $x_{2}^{1}$.
7. Page 97: In the second display of the page, $Z_{1}^{1}$ should be $Z_{1}^{2}$, i.e.,\
   $`\delta_{2}^{1}=\frac{\partial \Lambda}{\partial Z_{2}^{1}}=\frac{\partial \Lambda}{\partial Z_{1}^{2}}\frac{\partial Z_{1}^{2}}{\partial Z_{2}^{1}}=\delta_{1}^{2}w_{21}^{2}\sigma'(Z_{2}^{1}).`$
8. Page 97: Towards the middle of the page, there should be a minus sign in the derivative of the formula for the loss function with respect to the model, i.e., it should be\
   $`\frac{\partial\Lambda}{\partial m}=-(y-m(x;\theta)).`$
9. Page 98: The second formula in the second display should read: $`\frac{\partial \Lambda}{\partial w^{\ell}_{ij}}=\delta^{\ell}_{j}\cdot x^{\ell-1}_{i},`$   
10. Page 219: Around the middle of the page, it should be $\mathfrak{m}(\textbf{X};\theta)$ instead of $\mathfrak{m}(\textbf{X},\theta).$
11. Page 267: In the statement of Lemma 16.13, second line, $\mathbb{R}_{1}$ should be $\mathbb{R}^{1}$.
12. Page 462: Equation (24.1) should read $z_{1}=\mathfrak{m}_{1}(x;\theta)$. There is an extra "=".
13. Page 462: Three lines before the end of the page there is a subscript $\ell-1$ missing on $z$ in the formula. The formula should read\
   $`\frac{\partial\mathfrak{m}_{\ell}}{\partial\theta}\left(z_{\ell-1},x;\theta\right)=\sigma'\left(W^{\ell}_{z}z_{\ell-1}+W^{\ell}_{x}x\right)\odot W^{\ell}_{z}`$.


Last updated: February 26, 2026
