# Ruby

1. Why in Ruby 24 * 0.1 ≠ 2.4?
2.4000000000000004

1. What is proc, lambda, block? And what are the differences between them?
Blocks are used for passing blocks of code to methods, and procs and lambda’s allow storing blocks of code in variables.
Blocks are used extensively in Ruby for passing bits of code to functions. By using the yield keyword, a block can be implicitly passed without having to convert it to a proc.
When using parameters prefixed with ampersands, passing a block to a method results in a proc in the method’s context. Procs behave like blocks, but they can be stored in a variable.
Lambdas are procs that behave like methods, meaning they enforce arity and return as methods instead of in their parent scope.