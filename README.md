# 入群问题解答

1. 巴塞尔问题

```py
def f(N):
    s = 0.0
    for n in range(1, N + 1):
        s += 1 / (n ** 2)
    return s
```
2. sqrt(1+2*sqrt(1+3*sqrt(1+4*sqrt(1+...))))

构造：
x_n = n * sqrt(1 + x_{n+1})
求 x_1 即可
易见 x_n = n*(n+2) 满足
x_1 = **3**
