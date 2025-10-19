---
title: "My First Post"
author: Me
category: misc
tags: [test, mathjax]
use_math: true
lang: zh-cn
---

# My First Post

This is the first post on my personal blog, which is powered by Jekyll & Minimal Mistakes.

## 基本元素测试

### 文本样式测试

**这是粗体文本**  
*这是斜体文本*  
***这是粗体斜体文本***  
~~这是删除线文本~~  
<u>这是下划线文本</u>  
==这是高亮文本==

### 链接测试

普通链接：https://example.com  
带尖括号的链接：<https://example.com>  
电子邮件链接：<email@example.com>

### 转义字符测试

\*这个星号不会被解释为斜体\*  
\_这个下划线也不会被解释为斜体\_

## 完整功能测试

### 标题层级

## H2 标题

### H3 标题

#### H4 标题

##### H5 标题

###### H6 标题

### 列表测试

#### 无序列表

- 列表项一
- 列表项二
  - 嵌套列表项
  - 另一个嵌套项
- 列表项三

#### 有序列表

1. 第一项
2. 第二项
   1. 嵌套有序项
   2. 另一个嵌套项
3. 第三项

#### 任务列表

- [x] 已完成任务
- [ ] 未完成任务
- [ ] 另一个任务

### 代码测试

#### 行内代码

使用 `printf()` 函数输出文本。

#### 代码块

```python
def hello_world():
    print("Hello, World!")
    return True
```

## `MathJax`测试

### 行内公式测试

这是一个行内公式示例：$E = mc^2$，这是爱因斯坦的质能方程。

另一个行内公式：$\frac{d}{dx}f(x) = \lim_{h \to 0}\frac{f(x+h)-f(x)}{h}$

### 块级公式测试

#### 二次方程求根公式

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

#### 积分公式

$$
\int_a^b f(x)\,dx = F(b) - F(a)
$$

#### 求和公式

$$
\sum_{i=1}^n i = \frac{n(n+1)}{2}
$$

#### 矩阵公式

$$
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
\times
\begin{bmatrix}
x \\
y
\end{bmatrix}
=
\begin{bmatrix}
ax + by \\
cx + dy
\end{bmatrix}
$$

#### 极限公式

$$
\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e
$$

### 复杂公式示例

#### 傅里叶变换

$$
\mathcal{F}(\omega) = \int_{-\infty}^{\infty} f(t) e^{-i\omega t} \, dt
$$

#### 麦克斯韦方程组

$$
\begin{aligned}
\nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \mathbf{B} &= 0 \\
\nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} &= \mu_0\mathbf{J} + \mu_0\varepsilon_0\frac{\partial \mathbf{E}}{\partial t}
\end{aligned}
$$

#### 薛定谔方程

$$
i\hbar\frac{\partial}{\partial t}\Psi(\mathbf{r},t) = \left[ -\frac{\hbar^2}{2m}\nabla^2 + V(\mathbf{r},t) \right] \Psi(\mathbf{r},t)
$$

### 数学符号测试

#### 希腊字母

$\alpha, \beta, \gamma, \Gamma, \delta, \Delta, \pi, \Pi, \omega, \Omega$

#### 运算符

$\pm, \mp, \times, \div, \cdot, \ast, \star, \circ, \bullet$

#### 关系符号

$\leq, \geq, \neq, \approx, \equiv, \propto, \sim$

#### 集合符号

$\in, \notin, \subset, \subseteq, \supset, \supseteq, \cup, \cap, \emptyset$

#### 箭头符号

$\rightarrow, \leftarrow, \Rightarrow, \Leftarrow, \leftrightarrow, \Leftrightarrow$

### 分式和根号测试

#### 分式

$$
\frac{a}{b} + \frac{1}{1+\frac{1}{x}}
$$

#### 根号

$$
\sqrt{x} + \sqrt[3]{y} + \sqrt[n]{a+b}
$$

### 括号和定界符测试

#### 各种括号

$$
( ), [ ], \{ \}, \langle \rangle, | |, \lfloor \rfloor, \lceil \rceil
$$

#### 自适应大小括号

$$
\left( \frac{a}{b} \right), \left[ \frac{x}{y} \right], \left\{ \frac{m}{n} \right\}
$$

### 对齐环境测试

#### 多行公式对齐

$$
\begin{align}
f(x) &= (x+1)^2 \\
&= x^2 + 2x + 1
\end{align}
$$

#### 方程组

$$
\begin{cases}
x + 2y - z = 5 \\
2x - y + 3z = 1 \\
3x + y + 2z = 4
\end{cases}
$$

## `MathJax`测试二

### 行内公式测试二

这是一个行内公式示例：\(E = mc^2\)，这是爱因斯坦的质能方程。

另一个行内公式：\(\frac{d}{dx}f(x) = \lim_{h \to 0}\frac{f(x+h)-f(x)}{h}\)

### 块级公式测试二

#### 二次方程求根公式二

\[
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\]

#### 积分公式二

\[
\int_a^b f(x)\,dx = F(b) - F(a)
\]

#### 求和公式二

\[
\sum_{i=1}^n i = \frac{n(n+1)}{2}
\]

#### 矩阵公式二

\[
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
\times
\begin{bmatrix}
x \\
y
\end{bmatrix}=
\begin{bmatrix}
ax + by \\
cx + dy
\end{bmatrix}
\][^1]

#### 极限公式二

\[
\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e
\]

### 复杂公式示例二

#### 傅里叶变换二

\[
\mathcal{F}(\omega) = \int_{-\infty}^{\infty} f(t) e^{-i\omega t} \, dt
\]

#### 麦克斯韦方程组二

\[
\begin{aligned}
\nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \mathbf{B} &= 0 \\
\nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} &= \mu_0\mathbf{J} + \mu_0\varepsilon_0\frac{\partial \mathbf{E}}{\partial t}
\end{aligned}
\]

#### 薛定谔方程二

\[
i\hbar\frac{\partial}{\partial t}\Psi(\mathbf{r},t) = \left[ -\frac{\hbar^2}{2m}\nabla^2 + V(\mathbf{r},t) \right] \Psi(\mathbf{r},t)
\]

### 数学符号测试二

#### 希腊字母二

\(\alpha, \beta, \gamma, \Gamma, \delta, \Delta, \pi, \Pi, \omega, \Omega\)

#### 运算符二

\(\pm, \mp, \times, \div, \cdot, \ast, \star, \circ, \bullet\)

#### 关系符号二

\(\leq, \geq, \neq, \approx, \equiv, \propto, \sim\)

#### 集合符号二

\(\in, \notin, \subset, \subseteq, \supset, \supseteq, \cup, \cap, \emptyset\)

#### 箭头符号二

\(\rightarrow, \leftarrow, \Rightarrow, \Leftarrow, \leftrightarrow, \Leftrightarrow\)

### 分式和根号测试二

#### 分式二

\[
\frac{a}{b} + \frac{1}{1+\frac{1}{x}}
\]

#### 根号二

\[
\sqrt{x} + \sqrt[3]{y} + \sqrt[n]{a+b}
\]

### 括号和定界符测试二

#### 各种括号二

\[
( ), [ ], \{ \}, \langle \rangle, | |, \lfloor \rfloor, \lceil \rceil
\]

#### 自适应大小括号二

\[
\left( \frac{a}{b} \right), \left[ \frac{x}{y} \right], \left\{ \frac{m}{n} \right\}
\]

### 对齐环境测试二

#### 多行公式对齐二

\[
\begin{align}
f(x) &= (x+1)^2 \\
&= x^2 + 2x + 1
\end{align}
\]

#### 方程组二

\[
\begin{cases}
x + 2y - z = 5 \\
2x - y + 3z = 1 \\
3x + y + 2z = 4
\end{cases}
\][^10]

[^1]:不接受`=`单独成段
[^10]:非连续脚注
