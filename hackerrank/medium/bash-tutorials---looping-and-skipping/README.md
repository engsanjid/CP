# Looping and Skipping

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Your task is to use _for_ loops to display only _odd_ natural numbers from $1$ to $99$.
    

**Input Format**

_There is no input._  


**Constraints**

-

**Output Format**

	1
    3
    5
    .
    .
    .
    .
    .
    99

## Solution

**Language:** Bash  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-26T08:19:44.270Z  

```sh
for((i=1;i<=100;i+=2))
do
 echo $i
 done

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/bash-tutorials---looping-and-skipping/problem)