## 10.6

$$
\sum_{i=1}^{m} \sum_{j=1}^{m} \operatorname{dist}_{i j}^{2}=2 m \operatorname{tr}(\mathbf{B})
$$

[推导]：
$$
\begin{aligned}
\sum_{i=1}^{m} \sum_{j=1}^{m} \operatorname{dist}_{i j}^{2} &=\sum_{i=1}^{m} \sum_{j=1}^{m}\left(\left\|z_{i}\right\|^{2}+\left\|\boldsymbol{z}_{j}\right\|^{2}-2 \boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{j}\right) \\
&=\sum_{i=1}^{m} \sum_{j=1}^{m}\left\|\boldsymbol{z}_{i}\right\|^{2}+\sum_{i=1}^{m} \sum_{j=1}^{m}\left\|\boldsymbol{z}_{j}\right\|^{2}-2 \sum_{i=1}^{m} \sum_{j=1}^{m} \boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{j} \\
\end{aligned}
$$
其中
$$
\sum_{i=1}^{m} \sum_{j=1}^{m}\left\|\boldsymbol{z}_{i}\right\|^{2}=m \sum_{i=1}^{m}\left\|\boldsymbol{z}_{i}\right\|^{2}=m \operatorname{tr}(\mathbf{B})
$$

$$
\sum_{i=1}^{m} \sum_{j=1}^{m}\left\|\boldsymbol{z}_{j}\right\|^{2}=m \sum_{j=1}^{m}\left\|\boldsymbol{z}_{j}\right\|^{2}=m \operatorname{tr}(\mathbf{B})
$$

$$
\sum_{i=1}^{m} \sum_{j=1}^{m} \boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{j}=0
$$
