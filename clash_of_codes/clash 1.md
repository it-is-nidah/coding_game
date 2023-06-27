Find the total sum of the sum of the first N positive numbers, the first N positive perfect squares, and the first N positive perfect cubes.
Input
Line 1: An integer N
Output
Line 1:The sum of the sum of all numbers from 1 to N, the sum of 1 to N each squared and the sum of 1 to N each cubed.
Constraints
1 ≤ N ≤ 300 (The solution is always lower than 2^31-1)
Example
Input
3
Output
56

```python
import sys
import math

# Auto-generated code below aims at helping you parse
# the standard input according to the problem statement.

n = int(input())
t = 0
# Write an answer using print
# To debug: print("Debug messages...", file=sys.stderr, flush=True)


for i in range(1, n+1):
    t += i
    t += i*i
    t += i*i*i

print(t)
```
