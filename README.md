# C-Day-69-Count-Divisible-by-3-and-5
# C Day 69 - Count Numbers Divisible by 3 and 5

## Description

This program takes multiple numbers from the user and counts how many numbers are divisible by both 3 and 5.

## Example

```text id="c69example"
Enter how many numbers: 6
Enter number 1: 10
Enter number 2: 15
Enter number 3: 20
Enter number 4: 30
Enter number 5: 7
Enter number 6: 12

Numbers divisible by both 3 and 5 = 2
```

## Concepts Used

* `for` loop
* `if` statement
* Modulus operator `%`
* Logical AND operator `&&`
* `count++`
* `scanf()`
* Variables

## How It Works

1. The user enters how many numbers they want to check.
2. The program takes each number using a `for` loop.
3. `%` checks whether the number is divisible by 3 and 5.
4. The `&&` operator checks that both conditions are true.
5. If both conditions are true, `count` is increased by 1.
6. Finally, the program displays the total count.

## Important Condition

```c id="c69condition"
if (number % 3 == 0 && number % 5 == 0)
```

The number must be divisible by **both 3 and 5**.

## File Name

`count_divisible_by_3_and_5.c`

## Goal

The goal of this program is to practice loops, conditions, modulus, logical AND, and counting values based on a condition.
