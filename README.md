# leetcode-practice

## 1. String Manipulation 

### String Manipulation
```python
class Solution:
    def reverseString(self, s: List[str]) -> None:
        """
        Do not return anything, modify s in-place instead.
        """
        # Time : o(n) , Space: o(1) 
        left, right = 0 , len(s)-1
        while left < right:
            s[left] , s[right] = s[right] , s[left]
            left , right = left+1 , right-1
```
