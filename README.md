In this file we will keep errata associated to the book ["Mathematical Foundations of Deep Leanring Models and Algorithms"](https://bookstore.ams.org/view?ProductCode=GSM/252&_zs=hX3BH1&_zl=C09q7) published by the American Mathematical Society (AMS) in 2025.

1. Page xvii: In the "Norms" block of the Notation section, there is an absolute value missing from the definition of the $||x||_{q}$ norm\
   $`\|x\|_{q}=\left(\sum_{i=1}^{D}|x_{i}|^{q}\right)^{1/q}`$
2. Page 4: In the second paragraph, instead of  "Rumelhart, Hornik, and Williams in 1986 [RHW86]", it should be "Rumelhart, Hinton, and Williams in 1986 [RHW86]".      
3. Page 6: There is an absolute value missing from the definition of the $||x||_{q}$ norm\
   $`\|x\|_{q}=\left(\sum_{i=1}^{D}|x_{i}|^{q}\right)^{1/q}`$
4. Page 11: There is an $m$ missing at the formula right after (1.9). That formula should read\
   $`\Lambda(\theta)\overset{\text{def}}{=} \frac{1}{M}\sum_{m=1}^M \ell_{y_{m}}(\mathfrak{m}(x_{m};\theta)), `$
5. Page 15: The first bullet point after (1.11) should read
   "If the data set is too small and the model $\mathfrak{m}(x;\theta)$ is not trained on sufficient enough data points, then the model will have large variance."
6. Page 52-53 in Section 3.6: The variable $m$ can be thought of as $w$ to match previous notation, but technically speaking $m$ is also correct.
7. Page 54: In the third display $w$ should be capital $W$, i.e.\
   $`\mathfrak{m}(x;\theta)=S_{softmax}(Wx+b),`$   
8. Page 95: The second formula from the end should read\
   $`\frac{\partial\Lambda}{\partial Z}=\frac{\partial\Lambda}{\partial H}\frac{\partial H}{\partial Z}=...`$
9. Page 96: The expression of the last equality of the last display of the page should read $=w_{11}^{2}x_{1}^{1}+w_{21}^{2}x_{2}^{1}+ B^{2}.$ Namely, $x_{1}^{2}$ there should be $x_{1}^{1}$ and $x_{2}^{2}$ there should be $x_{2}^{1}$.
10. Page 97: In the second display of the page, $Z_{1}^{1}$ should be $Z_{1}^{2}$, i.e.,\
   $`\delta_{2}^{1}=\frac{\partial \Lambda}{\partial Z_{2}^{1}}=\frac{\partial \Lambda}{\partial Z_{1}^{2}}\frac{\partial Z_{1}^{2}}{\partial Z_{2}^{1}}=\delta_{1}^{2}w_{21}^{2}\sigma'(Z_{2}^{1}).`$
11. Page 97: Towards the middle of the page, there should be a minus sign in the derivative of the formula for the loss function with respect to the model, i.e., it should be\
   $`\frac{\partial\Lambda}{\partial m}=-(y-m(x;\theta)).`$
12. Page 98: The second formula in the second display should read: $`\frac{\partial \Lambda}{\partial w^{\ell}_{ij}}=\delta^{\ell}_{j}\cdot x^{\ell-1}_{i},`$
13. Page 103: In the second paragraph of Section 6.7, instead of  "Rumelhart, Hornik, and Williams in 1986 [RHW86]", it should be "Rumelhart, Hinton, and Williams in 1986 [RHW86]".
14. Page 205: In Figure 13.7, K(V) should be K(X).
15. Page 207: Definition 13.3 should read "An operator $`\mathcal{Z}: \mathbb{R}^{d\times n}\mapsto \mathbb{R}^{d\times n}`$ ..." instead of "An operator $`\mathcal{Z}: \mathbb{R}^{n\times d}\mapsto \mathbb{R}^{n\times d}`$ ..."
16. Page 219: Around the middle of the page, it should be $\mathfrak{m}(\textbf{X};\theta)$ instead of $\mathfrak{m}(\textbf{X},\theta).$
17. Page 267: In the statement of Lemma 16.13, second line, $\mathbb{R}_{1}$ should be $\mathbb{R}^{1}$.
18. Page 396:  Second display to the end. The initial condition for the dynamics of the vehicle should read $\mathcal{R}_{0}(x;\lambda)=x$ instead of $\mathcal{R}_{n}(x;\lambda)=x$.
19. Page 398: Towards the middle, the sentence "We certainly have that $J(x;lambda) \geq 1$." should be replaced by the sentence "We certainly have that $T_{\lambda}(x) \geq 1\cdot \delta$."
20. Page 398: In the first line of the last display, there is an extra $(z)$ in $\Phi_{\lambda(z)}$. Namely it should be $\Phi_{\lambda}$ instead of $\Phi_{\lambda(z)}$.
21. Page 400: In the expression right after (21.13) where the optimal policy $\lambda_{N}(x)$ is defined, the  $Q$ function is missing. Namely it should read\
    $`\lambda_N(x)= \argmin_{\alpha \in A}Q(x,\alpha',\theta_N).`$
22. Page 403: In the first formula of the page for the best policy, $\lambda*$ should be a function of $x$, not of $z$.
23. Page 404: In the sentence before formula (21.19), the sentence "Therefore, let us now suppose that $x\neq 0$..." should read "Therefore, let us now suppose that $x\notin B$..."
24. Page 407: In the mathematical display right after (21.22), $V(j+1 | z, a′)$ should be $V(j+1, z, a′)$.
25. Page 411: In Remark 21.3, $G(x_k, a_k, \theta_k)$ should be $Q(x_k, a_k, \theta_k)$.
26. Page 412: In formula (21.28) of Theorem 21.6, the maximum in the summation should be  $\max_{a''\in A} h_s(z, a'')$.
27. Page 413: In the Taylor expansion step of Step 1 of the proof of Theorem 21.6, the first summation term should be\
    $`\frac{1}{\sqrt{N}}\sum_{n=1}^{N}(C_{k+1}^{n}-C_{k}^{n})\sigma(W_{k+1}^{n}\cdot \xi)`...$
28. Page 417: The discount factor is incorrectly denoted by $\gamma$. It shoul be $\beta$. This is in the second line of (21.33) and in the second line of (21.34).
29. Page 418: In the end of the second line of the first display of the page $C^i_k$ should have been $C^n_k$.
30. Page 420: In the last display of the page $\hat{w}$ should be $w$, i.e., the formula should read\
    $`\left(\sum_{m=1}^{M}z_{m}\sigma(w\cdot \xi_{m})+c\sigma'(w\cdot \xi_{m})\xi_{m}\right)^{2}>\frac{\epsilon}{2}>0.`$     
32. Page 462: Equation (24.1) should read $z_{1}=\mathfrak{m}_{1}(x;\theta)$. There is an extra "=".
33. Page 462: Three lines before the end of the page there is a subscript $\ell-1$ missing on $z$ in the formula. The formula should read\
   $`\frac{\partial\mathfrak{m}_{\ell}}{\partial\theta}\left(z_{\ell-1},x;\theta\right)=\sigma'\left(W^{\ell}_{z}z_{\ell-1}+W^{\ell}_{x}x\right)\odot W^{\ell}_{z}`$.


Last updated: April 9, 2026
