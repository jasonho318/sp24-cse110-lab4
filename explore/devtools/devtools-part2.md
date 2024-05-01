# Part 2

1. The bug was that the values for num1 and num2 were being collected as strings and therefore the addition operation was concatenating them
2. I would fix this by ensuring that only integers can be inputted and throwing errors for otherwise, but quick patch is to parse num1 and num2 into integers before assigning result to their sum