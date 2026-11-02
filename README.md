# Check if Palindrome

**Category:** Text

## Problem

Checks if the string entered by the user is a palindrome. That is that it reads the same forwards as backwards like "racecar".

## Solution

Normalizes the input by lower-casing and stripping everything that is not a letter or digit, then compares the result with its reverse. This makes phrases like "A man, a plan, a canal: Panama" count as palindromes.

## How to run

Requires Python 3.8+ and no third-party packages.

```bash
python3 main.py "A man, a plan, a canal: Panama"
python3 main.py --demo
```

## Example

```text
True  racecar
 True  A man, a plan, a canal: Panama
 True  No 'x' in Nixon
False  hello world
 True  Was it a car or a cat I saw?
```

## Attribution

The problem statement is from [karan/Projects](https://github.com/karan/Projects), a list of practical projects that anyone can solve in any programming language (MIT License, Copyright (c) 2013 Karan Goel). The Python solution in this repository was implemented by [bspreston-esq](https://github.com/bspreston-esq).

This repository is part of the [Projects-Python-All](https://github.com/bspreston-esq/Projects-Python-All) collection.
