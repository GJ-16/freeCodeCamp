---
id: 5900f43e1000cf542c50ff50
title: 问题210：钝角三角形
challengeType: 5
videoUrl: ''
---

# --description--

考虑点（x，y）的集合S（r），其中整数坐标满足| x | + | y | ≤r。设O为点（0,0），C为点（r / 4，r / 4）。令N（r）为S（r）中的点B的数量，使得三角形OBC具有钝角，即最大角度α满足90°&lt;α&lt;180°。因此，例如，N（4）= 24并且N（8）= 100。

什么是N（1,000,000,000）？

# --hints--

`euler210()`应该返回1598174770174689500。

```js
assert.strictEqual(euler210(), 1598174770174689500);
```

# --solutions--

