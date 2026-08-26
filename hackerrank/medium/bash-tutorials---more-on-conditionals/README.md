# More on Conditionals

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Given three integers ($X$, $Y$, and $Z$) representing the three sides of a triangle, identify whether the triangle is scalene, isosceles, or equilateral.

- If all three sides are equal, output `EQUILATERAL`.  
- Otherwise, if any two sides are equal, output `ISOSCELES`.  
- Otherwise, output `SCALENE`.  

**Input Format**

Three integers, each on a new line.

**Constraints**

$1 \le X,Y,Z \le 1000$  
The sum of any two sides will be greater than the third.  


**Output Format**

One word: either "SCALENE" or "EQUILATERAL" or "ISOSCELES" (quotation marks excluded).

## Solution

**Language:** Bash  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-26T08:25:15.305Z  

```sh
read -p 'Enter 1st number' n1
read -p 'Enter 2nd number' n2
read -p 'Enter 4rd number' n3
if [ "$n1" -eq "$n2" ] && [ "$n2" -eq "$n3" ]
then 
    echo 'EQUILATERAL'
elif [ "$n1" -eq "$n2" ] || [ "$n1" -eq "$n3" ] || [ "$n2" -eq "$n3" ]
then
     echo 'ISOSCELES'
else
    echo 'SCALENE'
fi

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/bash-tutorials---more-on-conditionals/problem)