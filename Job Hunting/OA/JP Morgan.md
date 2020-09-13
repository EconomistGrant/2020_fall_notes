prerequisite:
```c++
//sort
sort(vec.begin(), vec.end())
//max
auto iter = max_element(v.begin(),v.end());
int nPos = (int)(std::max_element(v.begin(), v.end()) - (v.begin());
//妙用char的数值进行转换
int a = s[i] - '0'
char BIG = s[i] - 'a' + 'A'
char small = s[i] - 'A' + 'a' 
```
readline?
capitalize

# Maximum sum window
DP: the largest sum of continuous intergers that has ith integer as its end
a[i+1] = a[i] + v[i] if a[i] >0 
       = v[i] o/w

# Shopping cart
[value weight], weight limit
value per weight, take as much as possible?
dp, O(mn)
at each point: asses s[ i-weight[j]]+value[j]

# 1,3,5 -> minumum number of coins
dp works
math? need proof

# Maximum beauty

# Mth to last element
read lines from standard input
space delimited?

# Decoded String: lc394
https://leetcode-cn.com/problems/decode-string/

# Sliding Window Median: lc480
https://leetcode-cn.com/problems/sliding-window-median/

# essay
Choose a ML method that you have used, briefly explain how it works, and what made it suitable for the problem you were working on