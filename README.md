# PHP Parse Error: Incorrect Ternary Operator Syntax

This repository demonstrates a common PHP parsing error arising from an incorrectly used ternary operator. The error highlights a subtle syntax mistake that can be easily overlooked.

## Description
The `bug.php` file contains a PHP script with an incorrect ternary operator implementation.  The missing colon causes a parse error preventing execution. The correct syntax and solution are shown in `bugSolution.php`.

## How to Reproduce
1. Clone this repository.
2. Run `bug.php` using a PHP interpreter (e.g., `php bug.php`). You should observe a parse error.
3. Compare the code in `bug.php` with `bugSolution.php` to understand the correct syntax.

## Solution
The solution is in `bugSolution.php` and corrects the ternary operator's syntax by including the missing colon.