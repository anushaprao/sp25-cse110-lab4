1. Line 9 prints the value 20 (10 + 10) since the add variable is true. 
2. Line 13 prints the value 20.
3. You should avoid using var because regardless of where it is declared, it can be accessed anywhere in the function, resulting in scoping issues and bugs.
4. Line 9 prints the value 20 (10 + 10), since the add variable is true.
5. Line 13 returns an error. result is defined using let in the block above, meaning result is not able to be accessed outside of this block. Therefore, when it is accessed in line 13, there is no value associated with result.
6. Line 9 will return an error. Since const is the type of result, its value can not be changed, and the addition function will throw a type error.
7. Line 13 will also return an error, primarily because it can not access the value of result in the block, and also because the error in Line 9 will halt the execution of this script.