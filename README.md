# 1_logged_exercise_decorators
Create a decorator called logged. It should return the name of the function that is being called and its parameters. It should also return the result of the execution of the function being called. See the examples for more clarification.
Test Code
Test Code
Output
you called func(4, 4, 4)
it returned 6

Test Code
@logged
def sum_func(a, b):
    return a + b
print(sum_func(1, 4))
Output
you called func(4, 4, 4)
it returned 6

