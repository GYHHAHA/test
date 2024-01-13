## 10.3

$$
\begin{aligned}
\operatorname{dist}_{i j}^{2} &=\left\|\boldsymbol{z}_{i}\right\|^{2}+\left\|\boldsymbol{z}_{j}\right\|^{2}-2 \boldsymbol{z}_{i}^{\mathrm{T}} \boldsymbol{z}_{j} \\
&=b_{i i}+b_{j j}-2 b_{i j}
\end{aligned}
$$

[推导]：
$$
\begin{aligned}
\operatorname{dist}_{i j}^{2} &=\left\|\boldsymbol{z}_{i}-\boldsymbol{z}_{j}\right\|^{2}=\left(\boldsymbol{z}_{i}-\boldsymbol{z}_{j}\right)^{\top}\left(\boldsymbol{z}_{i}-\boldsymbol{z}_{j}\right) \\
&=\boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{i}-\boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{j}-\boldsymbol{z}_{j}^{\top} \boldsymbol{z}_{i}+\boldsymbol{z}_{j}^{\top} \boldsymbol{z}_{j} \\
&=\boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{i}+\boldsymbol{z}_{j}^{\top} \boldsymbol{z}_{j}-2 \boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{j} \\
&=\left\|\boldsymbol{z}_{i}\right\|^{2}+\left\|\boldsymbol{z}_{j}\right\|^{2}-2 \boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{j} \\
&=b_{i i}+b_{j j}-2 b_{i j}
\end{aligned}
$$
