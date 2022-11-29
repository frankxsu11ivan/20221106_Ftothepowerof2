# 20221106_Ftothepowerof2+G
#magnanimous adj having or showing a generous and kind nature
#Hank Mosley Jazz.

This problem was asked by Facebook.

Given a list of integers L, find the maximum length of a sequence of consecutive numbers that can be formed using elements from L.

For example, given L = [5, 2, 99, 3, 4, 1, 100], return 5 as we can build a sequence [1, 2, 3, 4, 5] which has length 5.
One approach is to simply sort the list and then iterate over it, keeping a counter and checking if the current number minus 1 is equal to the last number we've seen. If it is, then increase our counter since we're continuing the current sequence. Otherwise, we reset the counter to 1 (since it's the start of a new sequence).
