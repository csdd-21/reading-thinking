# Operation scenarios

```
git操作场景
git常见问题
如何看懂git graph
gitlens操作与git command的对应
githook配置
```

***

```
1.
local原本 C1 -> C2 -> C3 -> C4 -> C5 -> C6
local改为 C1 -> C2 -> C3
           \
            C4 -> C5 -> C6
提交到远程

local原本 C1 -> C2 -> C3 -> C4 -> C5 -> C6
local改为 C1 -> C2 -> C3
           \
            C4 -> C5 -> C6
提交到远程

2.
修改历史commit message

3.
我有2个分支，为v0.1 v0.2，当我执行完以下的命令后，结果是什么
git checkout v0.1
git reset HEAD^
git checkout v0.2
git revert HEAD
请说明，执行这些命令一般是什么场景下会执行？给出详细的场景例子介绍

4.

```

***

<details>

<summary>reference</summary>

[https://mp.weixin.qq.com/s/2p4m63JdsCjBpVku-WaZyA](https://mp.weixin.qq.com/s/2p4m63JdsCjBpVku-WaZyA)

[https://juejin.cn/post/6921519872035782670?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/6921519872035782670?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/6932026894015856654?searchId=2023081918500831BD4344DCFC9072754D#heading-15](https://juejin.cn/post/6932026894015856654?searchId=2023081918500831BD4344DCFC9072754D#heading-15)

[https://juejin.cn/post/6948338652845965348?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/6948338652845965348?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/7012191751507017741?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/7012191751507017741?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/7117174240012402701?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/7117174240012402701?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/7260690925528072250?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/7260690925528072250?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/7266308603938340919?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/7266308603938340919?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/6926761897450536973?searchId=2023081918500831BD4344DCFC9072754D#heading-21](https://juejin.cn/post/6926761897450536973?searchId=2023081918500831BD4344DCFC9072754D#heading-21)

[https://juejin.cn/post/6844903862495608839?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/6844903862495608839?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/6844903793897766926?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/6844903793897766926?searchId=2023081918500831BD4344DCFC9072754D)

[https://juejin.cn/post/6844903956531904525?searchId=2023081918500831BD4344DCFC9072754D](https://juejin.cn/post/6844903956531904525?searchId=2023081918500831BD4344DCFC9072754D)

[https://segmentfault.com/a/1190000038682597](https://segmentfault.com/a/1190000038682597)

[https://segmentfault.com/a/1190000011010819](https://segmentfault.com/a/1190000011010819)

[https://segmentfault.com/a/1190000008617626](https://segmentfault.com/a/1190000008617626)

[https://segmentfault.com/a/1190000013838580](https://segmentfault.com/a/1190000013838580)

</details>

