# Expanding Strings in brackets
In this exercise you are going to decompress a compressed string.

your input is a compresswd string of any of the formats or combined
- number[string]
- [number[string]]
- [string]
- or all combined

the decompressed output should completely be a string of letters only

the input - output form is as follows:
For example

# input
3[abc]4[ab]c

# output
abcabcabcababababc

# OTHER RULES
- numbers can have more than one digit.
For example

# input
10a or 10[a]

# output
aaaaaaaaaa

- a bracket can exist inside another bracket
For example

# input
2[2[a]c]

# output
aacaac

- only letters, square brackets and digits are allowed. No other character is permitted or allowed

- square brackets only enclose letters or digits or both
