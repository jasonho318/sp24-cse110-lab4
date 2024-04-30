# Part 1

1. prints 'values added: ' followed by the value of result, which depends on the type of num and num2. This code would return an error if types cannot be coerced.
2. prints 'final result: ' followed by the value of result, which may or may not be declared. If the code returns an error, it is because result may not be defined if add is false.
3. prints 'values added: ' followed by the value of result, which depends on the type of num and num2. This code would return an error if types cannot be coerced.
4. This code will not print anything, since it will lwaysreturn an error. Since result has block-level scope, it dies after the condition statement block closes. If add is false, result will never have been defined, throwing another kind of error.
5. Code returns an error because result is a const variable and can't be changed, so line 7 causes an error for attemtping to change the value of the variable.
6. Code returns an error either because result is a const variable and can't be changed, so line 7 causes an error for attemtping to change the value of the variable, or because result is not defined.
