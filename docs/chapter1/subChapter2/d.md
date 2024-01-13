## 10.4

$$
\sum^m_{i=1}dist^2_{ij}=\operatorname{tr}(\boldsymbol B)+mb_{jj}
$$

[解析]：首先根据式10.3有
$$
\sum^m_{i=1}dist^2_{ij}= \sum^m_{i=1}b_{ii}+\sum^m_{i=1}b_{jj}-2\sum^m_{i=1}b_{ij}
$$
对于第一项，根据矩阵迹的定义，$\sum^m_{i=1}b_{ii} = tr(\boldsymbol B)$，对于第二项，由于求和号内元素和$i$无关，因此$\sum^m_{i=1}b_{jj}=mb_{jj}$，对于第三项有，
$$
\sum_{i=1}^{m} b_{i j}=\sum_{i=1}^{m} \boldsymbol{z}_{i}^{\top} \boldsymbol{z}_{j}=
\sum_{i=1}^{m} \boldsymbol{z}_{j}^{\top} \boldsymbol{z}_{i}=
\boldsymbol{z}_{j}^{\top} \sum_{i=1}^{m} \boldsymbol{z}_{i}=
\boldsymbol{z}_{j}^{\top} \cdot \mathbf{0}=0
$$
其中$\sum_{i=1}^{m} \boldsymbol{z}_{i}=\mathbf{0}$是利用了书上的前提条件，即将降维后的样本被中心化。

## 10.5

$$
\sum_{j=1}^{m} \operatorname{dist}_{i j}^{2}=\operatorname{tr}(\mathbf{B})+m b_{i i}
$$
