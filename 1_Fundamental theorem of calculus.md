# Hard problem => Sum of many small Values

- Fundamental theorem of calculus
- 微积分基本定理: https://www.bilibili.com/video/av24325548?p=1
- integral 积分: 近似求和
- differential 微分: 微小的增量 `dx`
- derivative 导数:  衡量函数对取值的微小变化敏感度 (切线斜率) `f'(x)` 或 `dy/dx`

<hr />

# 1. 概念理解
从一个圆了解概念 某个圆的计算面积是从哪儿来的?

### 1.1 思考 I
为什么圆的面积是 $Area= r^2 \pi$ ?

<img src="https://user-images.githubusercontent.com/13708045/74117830-e3d8e500-4bf3-11ea-8a21-7a6a0d3b2b88.png" width=300 />

### 1.2 思考II - 厚度 dr
<img src="https://user-images.githubusercontent.com/13708045/74117850-f8b57880-4bf3-11ea-86ea-5abeecc95f10.png" width=300 />

```
面积是 = 长度 * dr(宽度/厚度)
概念: 将困难的问题 将其化成 多个小量的和
```

### 1.3 思考III - 证明
<img src="https://user-images.githubusercontent.com/13708045/74117878-11259300-4bf4-11ea-9d69-66a89838d989.png" width=300 />

例子中 R = 3, 换成R的话
$Area= r^2 \pi$

### 1.4 在 x^2 的积分
- 这个求解的是: 面积增量, 不是斜率的增量, 我们想知道的是[积分]
- 积分: 在每个dx划分区域里的面积的加和
- Integral of x^2，即x^2下的积分

<img src="https://user-images.githubusercontent.com/13708045/74117899-28648080-4bf4-11ea-8e81-78f11d84b792.png" width=300 />

# 2. 例子2
### 2.1 思考I
- 每个小面积 (微小变化的量) dA
-  dA / dx 小面积除以厚度 = derivative

<img src="https://user-images.githubusercontent.com/13708045/74117909-3ca87d80-4bf4-11ea-84f1-794c796a24d6.png" width=300 />

### 2.2 推导
<img src="https://user-images.githubusercontent.com/13708045/74117915-47fba900-4bf4-11ea-8754-cb45e6e496f2.png" width=300 />

# 3. 结论
### 3.1 积分 integral

**`在该函数下, dx足够小, 小到是个矩形, dA面积 = f(x) * dt`**

<img src="https://user-images.githubusercontent.com/13708045/74118006-ade83080-4bf4-11ea-9d2b-16708cb88be9.png" width=300 />

### 3.2 导数 derivative

<img src="https://user-images.githubusercontent.com/13708045/74117919-4b8f3000-4bf4-11ea-9b43-7c846a3e1cf6.png" width=200 />
