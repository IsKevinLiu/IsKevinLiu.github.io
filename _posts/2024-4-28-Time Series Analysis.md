---
title: Time Series Analysis
author: Liu
date: 2024-04-28 16:10:00 +0800
categories: [Statistics, Time Series Analysis]
render_with_liquid: false
img_path: https://raw.githubusercontent.com/IsKevinLiu/IsKevinLiu.github.io/main/_image/20240428/
---

### 参考书
- Practical Time Series Analysis(Aileen Nielsen)
- Time Series Analysis and Its Applications(Robert H. Shumway and David S. Stoffer)
---

# 0. 时间序列统计模型
## 0.1 一些定义
- **时间序列**被定义为以时间顺序为索引的随机变量集合。如时间序列 $x_1、x_2、x_3、\dots$，其中 $x_1$ 表示第一个时间点，$x_2$ 表示第二个时间点，以此类推。通常，以时间 $\{x_t\}$ 为索引的随机变量集合被称为随机过程。随机过程的观测值被称为随机过程的实现。
- **白噪声**，