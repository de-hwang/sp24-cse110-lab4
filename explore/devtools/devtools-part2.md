1. The numbers were being read as strings, so the sum was the concatenation of the two number strings.
2. I would fix it by calling `parseInt` on `num1` and `num2` to have them be read as 