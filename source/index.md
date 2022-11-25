---
title: ShwStone 的 Blog
comments: false
---
[![Netlify Status](https://api.netlify.com/api/v1/badges/809b23ff-4f84-4ffe-bb96-2e256dd00797/deploy-status)](https://app.netlify.com/sites/shwblog/deploys)
![](https://api.xecades.xyz/api?date=2023-06-25&str=%E6%88%91%E7%9A%84%E4%B8%8B%E4%B8%80%E4%B8%AA%E7%94%9F%E6%97%A5&quote=%E7%A5%9D%E6%82%A8AKIOI&email=HaowenShi%40outlook.com&github=ShwStone&wechat=uhygygyg&codeforces=Shihaowen&luogu=ShwStone&bilibili=%E4%B8%80%E9%A2%97%E7%9F%B3%E5%A4%B4&img=3)

## 站点目录

### [ForOIer](/categories/信奥/)

{% spoiler %}

#### [模板](/2022/07/14/模板)

#### 文件操作
```cpp
freopen("*.in", "r", stdin);
freopen("*.out", "w", stdout);
```

#### [模拟](https://oi-wiki.org/basic/simulate/) & [贪心](https://oi-wiki.org/basic/greedy/) & [递归、分治](https://oi-wiki.org/basic/divide-and-conquer/)

#### [排序](/2022/11/04/排序)

#### [模拟退火](https://oi-wiki.org/misc/simulated-annealing/)

#### 离线算法

##### [莫队](https://oi-wiki.org/misc/mo-algo/)

##### [整体二分](/2022/10/26/整体二分)

##### [CDQ分治](/2022/10/26/CDQ分治)

#### 搜索

##### 暴力枚举

##### DFS

##### BFS

##### 记忆化搜索

##### [A*](https://oi-wiki.org//search/astar/) & [IDA*](https://oi-wiki.org//search/idastar/)

#### [前缀和及二维前缀和](/2022/07/13/Prozor-题解) & 差分

#### [数据结构](/2022/07/13/模板)

#### [分块](/2022/07/13/分块——暴力美学)

#### 动态规划

##### [线性动规](/2022/07/13/NOIP2013-提高组-花匠-题解)

##### [背包](/2022/07/13/弹珠-题解)

##### [区间动规](https://oi-wiki.org/dp/interval/)

##### [树型动规](https://oi-wiki.org/dp/tree/)

##### [单调队列优化](/2022/10/27/单调队列优化DP)

##### [状压DP](/2022/10/27/状压DP)

#### 数学

##### [数论基础](/2022/07/13/数论)

##### [狄利克雷卷积](/2022/10/21/杜教筛) & [反演](/2022/10/24/反演)

##### [狄利克雷前缀和](/2022/08/08/Dirichlet-前缀和)

##### [逆元](https://oi-wiki.org/math/number-theory/inverse/)

##### [质数](https://oi-wiki.org/math/number-theory/prime/) & [质因数分解](https://zhuanlan.zhihu.com/p/267884783)

#### 树论

##### [dfs 序](/2022/10/26/dfs序)

##### [lca](https://oi-wiki.org/graph/lca/)

##### [树链剖分](https://oi-wiki.org/graph/hld/)

##### [树的重心 & 点分树](/2022/10/27/点分治)

#### 图论

##### 图的存储

```
std::vector<int> graph[maxn];
graph[u].emplace_back(v);
```

##### 拓扑排序

对于有向无环图，每次选择入度为 0 的点，放入队列，然后删除他的所有出边。入队的顺序称为拓扑序，具有无后效性的特点。可以跑 dp 。

另： tarjan 缩点的顺序是逆拓扑序。

代码：

```cpp
// 咕一会儿
```

##### [最短路算法](https://oi-wiki.org/graph/shortest-path/)

##### [最小生成树](https://oi-wiki.org/graph/mst/)

##### [匈牙利](/2022/10/26/匈牙利算法)

##### [tarjan](/2022/10/27/tarjan)

##### [2-SAT](/2022/10/26/2-SAT)

##### [网络流](https://oi-wiki.org/graph/flow/max-flow/)

#### 字符串

##### [字符串 hash](https://oi-wiki.org/string/hash/)

##### [KMP](/2022/10/27/KMP)

##### [trie](https://oi-wiki.org/string/trie/)

#### [STL](https://oi-wiki.org/lang/csl/)

{% endspoiler %}

### [题解](/categories/信奥/题解)

### 文化课

{% spoiler %}

#### 语文

##### [诗歌语言的陌生化](/2022/10/30/诗歌语言的陌生化)

##### [2022高考全国卷甲卷作文](/2022/07/24/2022高考全国卷甲卷作文)

##### [水浒传](/2022/07/24/水浒传)

#### 化学

##### [化学反应基础](/2022/07/28/化学反应基础)

##### [化学物质反应规律](/2022/10/16/化学物质反应规律)

{% endspoiler %}

### 其他

{% spoiler %}

#### [hexo+next搭建博客](/2022/07/26/hexo+next搭建博客)

#### [vsftpd指北](/2022/10/04/vsftpd指北)

#### [爬虫](/categories/爬虫)

{% endspoiler %}