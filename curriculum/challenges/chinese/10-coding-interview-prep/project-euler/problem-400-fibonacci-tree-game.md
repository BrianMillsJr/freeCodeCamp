---
id: 5900f4fe1000cf542c510010
title: 问题400：斐波纳契树游戏
challengeType: 5
videoUrl: ''
dashedName: problem-400-fibonacci-tree-game
---

# --description--

Fibonacci树是递归定义为的二叉树：T（0）是空树。 T（1）是只有一个节点的二叉树。 T（k）由具有T（k-1）和T（k-2）作为子节点的根节点组成。

在这样的树上，两个玩家玩外卖游戏。在每个回合中，玩家选择一个节点并删除该节点以及以该节点为根的子树。被迫占用整棵树根节点的玩家输了。

以下是T（k）从k = 1到k = 6的第一个回合的第一个玩家的获胜动作。

假设f（k）是在T（k）上播放该游戏时在第一轮游戏中第一玩家的获胜移动的数量（即，第二玩家没有获胜策略的移动）。

例如，f（5）= 1且f（10）= 17。

找到f（10000）。给出答案的最后18位数字。

# --hints--

`euler400()`应返回438505383468410600。

```js
assert.strictEqual(euler400(), 438505383468410600);
```

# --seed--

## --seed-contents--

```js
function euler400() {

  return true;
}

euler400();
```

# --solutions--

```js
// solution required
```
