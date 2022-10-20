### 题意 

已知一个整数 $N$ 以及 $M$ 个整数二元组，第 $i$ 个二元组是 $(L_i,R_i)$。

求有多少个整数序列 $x=(x_1,x_2,\cdots, x_M)$ 可以由以下方式生成，答案对 $998244353$ 取模。

- 选一个 $(1,2,\cdots,N)$ 的置换 $p=(p_1,p_2,\cdots , p_N)$。
- 对于所有 $i(1\le i\le M)$，令 $x_i$ 表示 $p_{L_i},p_{L_i+1},\cdots,p_{R_i}$ 的最大值的下标，也就是 $\max(p_{L_i},p_{L_i+1},\cdots,p_{R_i})=p_{x_i}$

### 数据范围

- $2\le N\le 300$
- $1\le M\le N(N-1)/2$
- $1\le L_i < R_i \le N$
- 二元组互不相同。

---

### 输入格式

第一行两个数 $N,M$。

接下来 $M$ 行，每行两个数 $L_i,R_i$ 表示一个二元组。

### 输出格式

一行一个数，表示答案。

---

### 样例输入1

```
3 2
1 2
1 3
```

### 样例输出1

```
4
```

### 样例解释1

举个例子，对于 $p=(2,1,3)$，可以得到 $x=(1,3)$。

有 $4$ 个序列满足条件，分别是 $x=(1,1),(1,3),(2,2),(2,3)$。

---

### 样例输入2

```
6 3
1 2
3 4
5 6
```

### 样例输出2

```
8
```

---

### 样例输入3

```
10 10
8 10
5 8
5 7
2 5
1 7
4 5
5 9
2 8
7 8
3 9
```

### 样例输出3

```
1060
```

---
