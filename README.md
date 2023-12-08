# prusha.- 
def bisection_method(func, a, b, tol=1e-6, max_iter=100):
    """
    Bisection method for finding the root of a function.

    
# Example usage:
def example_function(x):
    return x**2 - 4

initial_interval = (0, 4)
root, iterations = bisection_method(example_function, *initial_interval)

print(f"Approximate root: {root}")
print(f"Number of iterations: {iterations}")
