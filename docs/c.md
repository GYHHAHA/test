## 10.1

$$
P(e r r)=1-\sum_{c \in \mathcal{Y}} P(c | \boldsymbol{x}) P(c | \boldsymbol{z})
$$

[解析]：$P(c | \boldsymbol{x}) P(c | \boldsymbol{z})$表示$x$和$z$同属类$c$的概率，对所有可能的类别$c\in\mathcal{Y}$求和，则得到$x$和$z$同属相同类别的概率，因此$1-\sum_{c \in \mathcal{Y}} P(c | \boldsymbol{x}) P(c | \boldsymbol{z})$表示$x$和$z$分属不同类别的概率。



## 10.2

$$
\begin{aligned}
P(e r r) &=1-\sum_{c \in \mathcal{Y}} P(c | \boldsymbol{x}) P(c | \boldsymbol{z}) \\
& \simeq 1-\sum_{c \in \mathcal{Y}} P^{2}(c | \boldsymbol{x}) \\
& \leqslant 1-P^{2}\left(c^{*} | \boldsymbol{x}\right) \\
&=\left(1+P\left(c^{*} | \boldsymbol{x}\right)\right)\left(1-P\left(c^{*} | \boldsymbol{x}\right)\right) \\
& \leqslant 2 \times\left(1-P\left(c^{*} | \boldsymbol{x}\right)\right)
\end{aligned}
$$

[解析]：第二个式子是来源于前提假设"假设样本独立同分布，且对任意$x$和任意小正数$\delta$，在$x$附近$\delta$距离范围内总能找到一个训练样本"，假设所有$\delta$中最小的$\delta$组成和$\boldsymbol{x}$同一维度的向量$\boldsymbol{\delta}$则$P(c | \boldsymbol{z}) = P(c | \boldsymbol{x\pm\delta})\simeq P(c|\boldsymbol{x})$。第三个式子是应为$c^{*}\in\mathcal{Y}$，因此$P^{2}\left(c^{*} | \boldsymbol{x}\right)$是$\sum_{c \in \mathcal{Y}} P^{2}(c | \boldsymbol{x})$的一个分量，所以$\sum_{c \in \mathcal{Y}} P^{2}(c | \boldsymbol{x}) \geqslant P^{2}\left(c^{*} | \boldsymbol{x}\right)$。第四个式子是平方差公式展开，最后一个式子因为$1 + P\left(c^{*} | \boldsymbol{x}\right)\leqslant 2$。
