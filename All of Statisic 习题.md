## All of statisic: 第一章

### 1.

如果$A_n  \rightarrow A $​，则当$n->\infty$​时，
$$
P(A_n)->P(A)
$$
证明：假定$A_n$​​时单调递增序列，则$A_1 \subset A_2 \subset \cdots$​​. 令$A=\lim_{n \rightarrow \infty}A_n=\cup^{\infty}_{i=1}A_i$​​。定义$B_1=A_1$​​,$B_2=\{\omega \in \Omega,\omega \in A_2,\omega\notin{A_1}\}$​​，$B_3=\{\omega\in\Omega,\omega\in A_3,\omega\notin{A_2},\omega\notin{A_1}\}，$$\cdots$​​。容易证明$B_1$​​，$B_2$​​，$\cdots$​​两两不相交，对一切$n$​​有$A_n=\cup^{n}_{i=1}A_i=\cup^{n}_{i=1}B_i$​​且$\cup^{\infty}_{i=1}A_i=\cup^{n}_{i=1}B_i$​​。由公理3可得
$$
P(A_n)=P(\cup_{i=1}^{n}B_i)=\Sigma_{i=1}^{n}P(B_i)
$$
因此，再利用公理3就可以得到
$$
\lim_{n\rightarrow\infty}P(A_n)=\lim_{n\rightarrow\infty}P(\cup_{i=1}^{n}B_i)=\Sigma_{i=1}^{\infty}P(B_i)=P(\cup_{i=1}^{\infty}B_i)=P(A)
$$
$B_1$，$B_2$，$\cdots$两两不相交证明：

思路：设$i,j\in{N}$,任选$B_i,B_j$，证明$B_i\cup{B_j}=\emptyset$​即可。

设$i<j$，有$B_i\subset{A_i}$且$B_j\cup{A_i}=\emptyset$，则可以说$B_i\cup{B_j}=\emptyset$​。$i>j$同理可证。

ex.1:$A_n$为单调递减序列时，即$\lim_{n\rightarrow\infty}A_n=\cap_{i=1}^{\infty}A_i$时的证明。

此时$A_n$的反集$A_{n}^{c}$为单调递增序列，证明方式同上。注：$A_n=1-A_{n}^{c}$。

### 3.![Dingtalk_20210824101757](C:\Users\Wang\Desktop\Dingtalk_20210824101757.jpg)

a)证明：$\cup_{i=1}^{n}A_i\subset\cup_{i=1+1}^{n}A_i$​也就是$B_i\subset{B_{i+1}}$​。C同理可证

b)证明:

### 10.三门问题

在假定第一次开门后没有奖品的前提下，应该换不换门。

选门1概率为$\frac{1}{3}$,奖品在门2，门3一开始被打开概率为$1$，门2被打开概率为$0$​，但主观认为门2门3被打开概率为$\frac{1}{2}$​那么中奖的概率为
$$
P(2|1)=\frac{p(1|2)P(2)}{p(1)}=\frac{1×\frac{1}{3}}{\frac{1}{2}}=\frac{2}{3}
$$
不中奖概率为,
$$
P(3|1)=\frac{p(1|3)P(3)}{p(1)}=\frac{\frac{1}{2}×\frac{1}{3}}{\frac{1}{2}}=\frac{1}{3}
$$

### 12.

设事件A为第一次看到绿色，那么$P(A)=\frac{1}{3}+\frac{1}{3}\frac{1}{2}=\frac{1}{2}$​​​​，左边是选到两面都是绿色卡的概率，右边是选到一面是绿色卡的概率。设事件B为第二次看到绿色，那么A,B的联合分布为$P(A,B)=\frac{1}{3}$，即选中两面绿色的卡。按照贝叶斯公式，
$$
P(B|A)=\frac{P(A,B)}{p(A)}=\frac{\frac{1}{3}}{\frac{1}{2}}=\frac{2}{3}
$$
