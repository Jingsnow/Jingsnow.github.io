---
title: markdown数学公式
date: 2019-8-8 22:1:02
categories:
- Markdown语法笔记
mathjax: true
---
# H1

## H2

### H3

# 插入方式

## 1.1行间插入

用两个\$号，$a+b$
## 1.2另取一行

`$$a+b$$`
$$a+b$$
# 2.基本类型的插入
## 2.1上下标
$$x_1$$
$$x_1^2$$
$$x^2_1$$
$$x_{22}^{(n)}$$
$${}^*x^*$$
$$x_{balabala}^{bala}$$
## 2.2分式
$$\frac{x+y}{2}$$
$$\frac{1}{1+\frac{1}{2}}$$
## 2.3根式
$$\sqrt{2}<\sqrt[3]{3}$$
$$\sqrt{1+\sqrt[p]{1+a^2}}$$
$$\sqrt{1+\sqrt[^p\!]{1+a^2}}$$
## 2.4求和，积分
$$\sum_{k=1}^{n}\frac{1}{k}$$
$$\int_a^b f(x)dx$$
比较美观的积分
$$\int_a^b f(x)\mathrm{d}x$$
$$\int_a^b f(x)\,\mathrm{d}x$$
## 2.5空格
紧贴 $$a\!b$$
小空格 $$a\,b$$
中等空格 $$a\;b$$
大空格 $$a\ b$$
quad空格 $$a \quad b$$
两个quad空格 $$a \qquad b$$
## 2.6公式界定符
主要符号(),[],|,||,通过\left和\right后面跟界定符来对同时界定。
$$\left(\sum_{k=\frac{1}{2}}^{N^2}\frac{1}{k}\right)$$
## 2.7矩阵
类似于 left right，这里是 begin 和 end。而且里面有具体的矩阵语法，& 区分行间元素，\\\\\\\\ 代表换行。可以理解为 HTML 的标签之类的。
$$\begin{matrix}1 & 2\\\\3 & 4\end{matrix}$$
$$\begin{pmatrix}1 & 2\\\\3 & 4\end{pmatrix}$$
$$\begin{bmatrix}1 & 2\\\\3 & 4\end{bmatrix}$$
$$\begin{Bmatrix}1 & 2\\\\3 & 4\end{Bmatrix}$$
$$\begin{vmatrix}1 & 2\\\\3 & 4\end{vmatrix}$$
$$\left|\begin{matrix}1 & 2\\\\3 &4\end{matrix}\right|$$
$$\begin{Vmatrix}1 & 2\\\\3 &4\end{Vmatrix}$$
## 2.8排版数组
$$\mathbf{X}=
\left( \begin{array}{ccc}
x_{11} & x_{12} & \ldots \\\\
x_{21} & x_{22} & \ldots \\\\
\vdots & \vdots & \ddots 
\end{array}    \right)$$

# 3.常用公式举例
## 3.1多行公式
### 3.1.1长公式
$$
\begin{aligned}
x = a+b+c+{} \\\\
d+e+f+g
\end{aligned}
$$
### 3.1.2公式组
$$
\begin{gather}
a &= b+c+d \\\\
x &= y+z
\end{gather}
$$
$$
\begin{align}
y &= \cos t + 1 \\\\
y &= 2sin t \\\\
\end{align}
$$
### 3.1.3分段函数
$$
y=\begin{cases}
-x,\quad x\leq 0 \\\\
x,\quad x>0
\end{cases}
$$
## 3.2数组的其他使用
### 3.2.1划线
$$
\left(\begin{array}{|c|c|}
1 & 2 \\\\
\hline
3 & 4
\end{array}\right)
$$
### 3.2.2制表
$$
\begin{array}{|c|c|}
\hline
{1111111111} & 2 \\\\
\hline
3 & 4 \\\\
\hline
\end{array}
$$
# 4.常用的数学符号
## 4.1希腊字母
$$
\begin{array}{|c|c|c|c|c|c|c|c|}
\hline
{\alpha} & {\backslash alpha} & {\theta} & {\backslash theta} & {o} & {o} & {\upsilon} & {\backslash upsilon} \\\\
\hline
{\beta} & {\backslash beta} & {\vartheta} & {\backslash vartheta} & {\pi} & {\backslash pi} & {\phi} & {\backslash phi} \\\\
\hline
{\gamma} & {\backslash gamma} & {\iota} & {\backslash iota} & {\varpi} & {\backslash varpi} & {\varphi} & {\backslash varphi} \\\\
\hline
{\delta} & {\backslash delta} & {\kappa} & {\backslash kappa} & {\rho} & {\backslash rho} & {\chi} & {\backslash chi} \\\\
\hline
{\epsilon} & {\backslash epsilon} & {\lambda} & {\backslash lambda} & {\varrho} & {\backslash varrho} & {\psi} & {\backslash psi} \\\\
\hline
{\varepsilon} & {\backslash varepsilon} & {\mu} & {\backslash mu} & {\sigma} & {\backslash sigma} & {\omega} & {\backslash omega} \\\\
\hline
{\zeta} & {\backslash zeta} & {\nu} & {\backslash nu} & {\varsigma} & {\backslash varsigma} & {} & {} \\\\
\hline
{\eta} & {\backslash eta} & {\xi} & {\backslash xi} & {\tau} & {\backslash tau} & {} & {} \\\\
\hline
{\Gamma} & {\backslash Gamma} & {\Lambda} & {\backslash Lambda} & {\Sigma} & {\backslash Sigma} & {\Psi} & {\backslash Psi} \\\\
\hline
{\Delta} & {\backslash Delta} & {\Xi} & {\backslash Xi} & {\Upsilon} & {\backslash Upsilon} & {\Omega} & {\backslash Omega} \\\\
\hline
{\Omega} & {\backslash Omega} & {\Pi} & {\backslash Pi} & {\Phi} & {\backslash Phi} & {} & {} \\\\
\hline
\end{array}
$$
