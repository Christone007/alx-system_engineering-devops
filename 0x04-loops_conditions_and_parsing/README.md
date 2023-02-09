## LOOPS, CONDITIONS AND PARSING

### Introduction
This directory holds projects that demonstrate the 
understanding of Loops and Conditions in Shell Scripts

### Learnings from doing the project
1. Bash scripts take spaces very serious. As such:
	* ```i=$(($i + 1))``` is not same as ```i=$(( $i + i ))```  

2. For ```while``` loops, the condition is surrounded by "[ ]"
3. Conditionals must end with terminating keyword e.g ```fi```, ```done```, ```esac```
4. ```if``` statements that require a simple condition can be put in "[[]]" but those requiring expressions are put in "(())" as demonstrated in (10-fizzbuzz)[./fizzbuzz]
