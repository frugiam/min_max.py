# Author: Michelle Frugia
# GitHub username: frugiam
# Date: 01/23/2024
# Description: Project 3a

print("How many integers would you like to enter?")
num_integers = int(input())
min_num = float('inf')
max_num = float('-inf')
print("Please enter", num_integers, "integers.")
for i in range(num_integers):
    num = int(input())
    if num < min_num:
        min_num = num
    if num > max_num:
        max_num = num

print("min:", min_num)
print("max:", max_num)
