# Federated-Matrix-factorization
  
# *Matrix Factorization* 
 | Label | Title  | Code | Model |Description |
| ------------- | ------------- |------------- | ------------- | ------------- |
|2022_PR [paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320322002989)  |Efficient federated multi-view learning  |[code](https://github.com/huangsd/federated-multi-view-learning/tree/main)  | $\min_{\{U^{(m)},V^{(m)}\},V} \quad\sum_{m=1}^{M}\alpha^{(m)} \| X^{(m)}-U^{(m)}(V^{(m)})^{\top}\|_{F}^{2}$<br>$\mathrm{s.t.}\quad V^{(m)} \ge \mathbf{0}, V^{(m)} = V,V^{\top}V = I, \quad m=1,\ldots,M$  | $\alpha^{(m)} = 1 - \frac{2}{\| X^{(m)}-U^{(m)}(V^{(m)})^{\top} \|_F^2}.$<br>$\theta^{(m)}\in[0,1]$is a per-node parameter that controls the quality of the approximation.  |
|2022_TSP [paper](https://ieeexplore.ieee.org/document/9713943)  |Federated matrix factorization:<br>algorithm design and application to data clustering.  |[code](https://github.com/metastableB/kfed/)  | Content Cell  | Content Cell  |
|2024_KBS [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705124009365)  |Partially shared federated multiview learning.  |[code](https://github.com/robotpear/The-code-of-PSFedML)  | Content Cell  | Content Cell  |
|2024_IJCAI [paper](https://www.ijcai.org/proceedings/2024/0439.pdf)  |Effcient federated multi-view clustering with <br>integrated matrix factorization and K-Means.  |[code]  | Content Cell  | Content Cell  |
| 2025_TPAMI [paper](https://liujiyuan13.github.io/pdfs/CeFMC_early_access.pdf) | Communication-efficient federated multi-view clustering.  |[code](https://github.com/liujiyuan13/CeFMC-code_release)  | Content Cell  |  Content Cell  |



