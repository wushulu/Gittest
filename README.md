# git test

## 数学公式（源码 + 渲染）

下面每个示例先给出“源码”（代码块），然后给出渲染结果（即实际可见的公式）。这样你既能看到写法，也能看到渲染效果。

- 行内公式示例

源码：
```markdown
Euler: $e^{i\pi}+1=0$
```

渲染：Euler: $e^{i\pi}+1=0$

- 一元二次方程（块级显示）

源码：
```markdown
$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$
```

渲染：
$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$

- 定积分（块级）

源码：
```markdown
$
\int_a^b f(x)\,dx
$
```

渲染：
$$
\int_a^b f(x)\,dx
$$

- 导数（行内与显示）

源码（行内）：
```markdown
This is inline: $f'(x)=\dfrac{df}{dx}$
```

渲染（行内）：This is inline: $f'(x)=\dfrac{df}{dx}$

源码（显示）：
```markdown
$$
f(x)=\sum_{n=0}^{\infty}\frac{f^{(n)}(a)}{n!}(x-a)^n
$$
```

渲染（显示）：
$$
f(x)=\sum_{n=0}^{\infty}\frac{f^{(n)}(a)}{n!}(x-a)^n
$$

- 极限与求和

源码：
```markdown
$$
\lim_{x\to 0}\frac{\sin x}{x}=1
$$

$$
\sum_{k=1}^{n}k=\frac{n(n+1)}{2},\qquad \prod_{k=1}^{n}k=n!
$$
```

渲染：
$$
\lim_{x\to 0}\frac{\sin x}{x}=1
$$

$$
\sum_{k=1}^{n}k=\frac{n(n+1)}{2},\qquad \prod_{k=1}^{n}k=n!
$$

- 矩阵示例

源码：
```markdown
$$
A=\begin{bmatrix} a_{11} & a_{12} \\\\ a_{21} & a_{22} \end{bmatrix}
$$
```

渲染：
$$
A=\begin{bmatrix} a_{11} & a_{12} \\\\ a_{21} & a_{22} \end{bmatrix}
$$

- 高斯分布密度函数

源码：
```markdown
$$
\frac{1}{\sqrt{2\pi\sigma^2}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}
$$
```

渲染：
$$
\frac{1}{\sqrt{2\pi\sigma^2}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}
$$

---

## 使用提示

- 在源码块中使用 `markdown` 或不指定语言都可以，关键是代码块内要展示原始 Markdown 源（包括 `$` 和 `\`）。
- 预览公式：按 `Ctrl+Shift+V` 或 `Ctrl+K` 然后 `V`。推荐安装 `Markdown Preview Enhanced` 或 `Markdown+Math` 得到更完整的渲染支持。



