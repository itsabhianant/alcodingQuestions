# Office Performance Analysis

## Problem Statement

In a corporate office, the management tracks the daily performance scores of employees over a period of `n` days. Each performance score is recorded in an array, where each number represents the productivity score for a specific day.

The HR department frequently needs to calculate the total productivity of an employee over a specific range of days to assess performance during certain periods. Your task is to help HR efficiently process these queries and provide the requested information.

---

## Input Format

1. The first line contains two integers, `n` and `q`:
   - `n`: The number of days for which performance data is recorded (`1 ≤ n ≤ 2 × 10^5`).
   - `q`: The number of queries HR wants to process (`1 ≤ q ≤ 2 × 10^5`).

2. The second line contains `n` integers, `x_1, x_2, ..., x_n`, representing the performance scores for each day (`1 ≤ x_i ≤ 10^9`).

3. Each of the next `q` lines contains two integers `a` and `b` (`1 ≤ a ≤ b ≤ n`), representing a query. For each query, HR needs to calculate the total productivity from day `a` to day `b` (inclusive).

---

## Constraints

- `1 ≤ n, q ≤ 2 × 10^5`
- `1 ≤ x_i ≤ 10^9`
- `1 ≤ a ≤ b ≤ n`

---

## Output Format

For each query, output a single integer, the total productivity score over the specified range of days.

---

## Test Cases

1. Input:
   
```
8 4
3 2 4 5 1 1 5 3
2 4
5 6
1 8
3 3
```

1. Output:

```
11
2
24
4
```
---

2. Input:
```
8 36
7 6 4 6 2 9 4 8
1 1
1 2
1 3
1 4
1 5
1 6
1 7
1 8
2 2
2 3
2 4
2 5
2 6
2 7
2 8
3 3
3 4
3 5
3 6
3 7
3 8
4 4
4 5
4 6
4 7
4 8
5 5
5 6
5 7
5 8
6 6
6 7
6 8
7 7
7 8
8 8
```

2. Output
```
7
13
17
23
25
34
38
46
6
10
16
18
27
31
39
4
10
12
21
25
33
6
8
17
21
29
2
11
15
23
9
13
21
4
12
8
```
---

3. Input
```
5 3
15 20 25 30 35
1 3
2 5
3 4
```

3. Output
```
5 3
15 20 25 30 35
1 3
2 5
3 4
```
---

























