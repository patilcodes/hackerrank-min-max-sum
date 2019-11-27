#!/bin/python3

import math
import os
import random
import re
import sys

# Complete the miniMaxSum function below.
def miniMaxSum(arr):
    arr.sort()
    arr1=arr[:4]
    arr2=arr[1:]
    min=0
    max=0
    for a in arr1:
        min+=a
    for b in arr2:
        max+=b
    print(min,max)




if __name__ == '__main__':
    arr = list(map(int, input().rstrip().split()))

    miniMaxSum(arr)
