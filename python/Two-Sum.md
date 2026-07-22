### Two-Sum
##### solution:
```class Solution(object):
    def twoSum(self, nums, target):
        for i in range(0, len(nums)):
            n1 = nums[i]
            for j in range(i+1, len(nums)):
                n2 = nums[j]
                if n1 + n2 == target:
                    ris = [i, j]
                    return ris```
> i learned how to write for-loops, if conditions and arrays.