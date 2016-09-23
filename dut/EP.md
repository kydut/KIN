# EP



## 2016/9/23    Fir

只要是做采样就不可能避开最远点采样，感觉广义里奇曲率在三维上的采样是自然推广，应该是比较靠谱的。

- [ ] ”The Farthest Point Strategy for Progressive Image Sampling“


- [ ] Git 教程

暂时就是这样。



问题：

-   bandlimited function?




>   Bernstein inequality
>   $$
>   f^{'}(x)|<2\pi BM
>   $$
>   $B$是函数的带宽，$M$是函数振幅的带宽。
>   $$
>   B_{min}(p,q)=\cfrac{arcsin(\cfrac{2I(q)-M}{M})-arcsin(\cfrac{2I(p)-M}{M})}   
>   {2\pi d(p,q) }
>   $$
>   我们得到建议的权值方程
>   $$
>
>
>   W(v)=R^2(v) \max_{s_i,s_j\in N(v)}(B_{min}(s_i,s_j))
>
>
>   $$
>

经典的采样定理有香农采样定理

>   在[数字信号处理](https://zh.wikipedia.org/wiki/%E6%95%B0%E5%AD%97%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86)领域，**采样定理**是[连续信号](https://zh.wikipedia.org/wiki/%E8%BF%9E%E7%BB%AD%E4%BF%A1%E5%8F%B7)（通常称作“模拟信号”）与[离散信号](https://zh.wikipedia.org/wiki/%E7%A6%BB%E6%95%A3%E4%BF%A1%E5%8F%B7)（通常称作“数字信号”）之间的一个基本桥梁。它确定了信号带宽的上限，或能捕获连续信号的所有信息的离散采样信号所允许的[采样频率](https://zh.wikipedia.org/wiki/%E9%87%87%E6%A0%B7%E9%A2%91%E7%8E%87)的下限。
>
>   严格地说，定理仅适用于具有[傅里叶变换](https://zh.wikipedia.org/wiki/%E5%82%85%E9%87%8C%E5%8F%B6%E5%8F%98%E6%8D%A2)的一类[数学函数](https://zh.wikipedia.org/wiki/%E5%87%BD%E6%95%B0)，即频率在有限区域以外为零（参照图1）。[离散时间傅里叶变换](https://zh.wikipedia.org/wiki/%E7%A6%BB%E6%95%A3%E6%97%B6%E9%97%B4%E5%82%85%E9%87%8C%E5%8F%B6%E5%8F%98%E6%8D%A2)（[泊松求和公式](https://zh.wikipedia.org/w/index.php?title=%E6%B3%8A%E6%9D%BE%E6%B1%82%E5%92%8C%E5%85%AC%E5%BC%8F&action=edit&redlink=1)的一种形式）提供了实际[信号](https://zh.wikipedia.org/wiki/%E4%BF%A1%E5%8F%B7_(%E4%BF%A1%E6%81%AF%E8%AE%BA))的解析延拓，但只能近似该条件。直观上我们希望，当把连续函数化为采样值（叫做“样本”）的离散序列并[插值](https://zh.wikipedia.org/wiki/%E6%8F%92%E5%80%BC)到连续函数中，结果的保真度取决于原始采样的密度（或[采样率](https://zh.wikipedia.org/wiki/%E5%8F%96%E6%A8%A3)）。采样定理介绍了对带宽限制的函数类型来说保真度足够完整的采样率的概念；在采样过程中"信息"实际没有损失。定理用函数的带宽来表示采样率。定理也导出了一个数学上*理想的*原连续信号的重构公式。
>
>   该定理没有排除一些并不满足采样率准则的特殊情况下完整重构的可能性。（参见下文[非基带信号采样](https://zh.wikipedia.org/wiki/%E9%87%87%E6%A0%B7%E5%AE%9A%E7%90%86#.E9.9D.9E.E5.9F.BA.E5.B8.A6.E4.BF.A1.E5.8F.B7.E9.87.87.E6.A0.B7)，以及[压缩感知](https://zh.wikipedia.org/wiki/%E5%A3%93%E7%B8%AE%E6%84%9F%E7%9F%A5)。）

























































































