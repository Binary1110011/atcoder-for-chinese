### 题意 

给出一个 $9\times 9$ 的，只包含 `.` 和 `#` 的字符矩阵。

你需要求出矩阵内 **四个顶点都是 `#` 的正方形** 的个数。

注意正方形可以斜着放。

### 数据范围

无。

---

### 输入格式

一个 $9\times 9$ 的，只包含 `.` 和 `#` 的字符矩阵。

### 输出格式

输出一个整数表示答案。

---

### 样例输入1

```
##.......
##.......
.........
.......#.
.....#...
........#
......#..
.........
.........
```

### 样例输出1

```
2
```

### 样例解释1

第一个可行的正方形： $(1,1),(1,2),(2,2),(2,1)$ 。

第二个可行的正方形： $(4,8),(5,6),(7,7),(6,9)$ 。

所以答案为 $2$ 。

### 样例输入2

```
.#.......
#.#......
.#.......
.........
....#.#.#
.........
....#.#.#
........#
.........
```

### 样例输出2

```
3
```

