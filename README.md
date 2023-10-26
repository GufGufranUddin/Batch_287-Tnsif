# Batch_287-Tnsif
#Explanation of OperatorsDemo program:
Initially, a is 10, and b is 20. We print these values: "a and b values before the operation: 10 20."

++a increases the value of a by 1, so now a is 11. We use this updated a value in the next operation.

In the expression c = ++a + b + a--, we first increment a by 1 (making it 12), and then we use this new value of a in the expression.
After that, a-- takes the original value of a (12) and then decreases a by 1. So, c is calculated as 12 + 20 + 12, which equals 44. We print this as "C value after the operation: 44."

In the expression d = c++ + a + b--, we use the current value of c (which is 44) in the expression, and then we increment c by 1 (making it 45). 
We also use a (11) and b (20) before decreasing b by 1. So, d is calculated as 44 + 11 + 20, which equals 75. We print this as "D value after the operation: 75."

Finally, we print the values of a, b, c, and d after all these operations. 
a is 11 (increased by 1 and then decreased by 1), b is 19 (decreased by 1), c is 45 (increased by 1 in the first step), and d is 75.
#output:
![Screenshot 2023-10-27 002928](https://github.com/GufranUddin/Batch_287-Tnsif/assets/132918620/8521b8a4-4158-480f-8c19-64b3807fb6aa)
