---
id: 5900f4861000cf542c50ff98
title: 问题281：比萨馅料
challengeType: 5
videoUrl: ''
dashedName: problem-281-pizza-toppings
---

# --description--

您将得到一个比萨饼（完美的圆），该比萨饼已被切成等份的m·n，并且您想在每个切片上精确地放一个馅料。

令f（m，n）表示在披萨上放置m种不同配料（m≥2）的方法，将每个配料恰好放在n个切片上（n≥1）。 反射被认为是不同的，旋转没有。

因此，例如，f（2,1）= 1，f（2,2）= f（3,1）= 2和f（3,2）= 16.f（3,2）如下所示：

找出所有f（m，n）的总和，使f（m，n）≤1015。

# --hints--

`euler281()`应该返回1485776387445623。

```js
assert.strictEqual(euler281(), 1485776387445623);
```

# --seed--

## --seed-contents--

```js
function euler281() {

  return true;
}

euler281();
```

# --solutions--

```js
// solution required
```
