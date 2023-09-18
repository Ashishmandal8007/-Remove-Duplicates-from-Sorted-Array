# -Remove-Duplicates-from-Sorted-Array
# Algorithm

We are 2 pointer approach to solve this question.

At first j and i is fixed on element 0 of array nums.

After that if nums[j]=nums[i] then i is incremented to next index.

whenn num[j] != nums[i] then j is incremented and the value of i is inserted on j new incremented position.

At return statement is passeed return j+1 because we have print unique value, where j index are 01234 if we are incrementing j by 1 we getting our answer
