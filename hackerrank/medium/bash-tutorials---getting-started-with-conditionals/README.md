# Getting started with conditionals

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Read in one character from STDIN.  
If the character is 'Y' or 'y' display "YES".  
If the character is 'N' or 'n' display "NO".  
No other character will be provided as input.    



    

**Input Format**

One character 


**Constraints**

The character will be from the set $\{yYnN\}$.

**Output Format**

echo `YES` or `NO` to STDOUT.

## Solution

**Language:** Bash  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-24T07:43:16.436Z  

```sh
read -p 'Enter one character' ch

if [ "$ch" = "y" ] || [ "$ch" = "Y" ]
then
echo 'YES'
elif [ "$ch" = "n" ] || [ "$ch" = "N" ]
then
echo 'NO'
else
echo 'Envild character enter'
fi

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/bash-tutorials---getting-started-with-conditionals/problem)