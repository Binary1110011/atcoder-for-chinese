## 题意
高桥在黑板上写下了 $N$ 组，从 $a_i$ 到 $b_i$ 公差为 $1$ 的等差数列。

求黑板上数字的总和。
## 数据范围
$1\le N \le 10^5$

$1\le a_i\le b_i \le 10^6$
## 输入格式
第一行输入一个 $N$

之后 $N$ 行，每行两个数 $a_i,b_i$ 
## 输出格式
求黑板上数字的总和。
### 样例输入1
```
2
1 3
3 5
```
### 样例输出1
```
18
```
### 样例解释1
他在黑板第一次写下了 $1,2,3$。

第二次写下了 $3,4,5$。

$(1+2+3)+(3+4+5)=18$
### 样例输入2
```
3
11 13
17 47
359 44683
```
### 样例输出2
```
998244353
```
### 样例输入3
```
1
1 1000000
```
### 样例输出3
```
500000500000
```