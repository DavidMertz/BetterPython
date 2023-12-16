# Front Matter {intro/summary}
# About This Book {intro/summary}
# Looping Over the Wrong Things {intro/summary}
[X] looping|Generating a list for iteration
[X] looping|Looping over index rather than using `enumerate()`
[X] looping|Iterating over just `dict.keys()` when you want `dict.items()`
[X] looping|Mutating an object you are iterating over
[X] looping|Using `while` loops when `for` loops are more idiomatic
[X] looping|Not using the walrus operator for “loop-and-a-half” blocks
[X] looping|Not using `zip()` to simplify using multiple iterables
[X] looping|Not using `zip(strict=True)` and `itertools.zip_longest()`

# Confusing Equality with Identity {intro/summary}
[X] identity|Late binding of closures
[X] identity|Overchecking for boolean values
[X] identity|Comparing `x == None`
[X] identity|Misunderstanding mutable default arguments
[X] identity|Confusion of copies with references to mutable objects
[X] advanced|Confusing `is` with `==` (in the presence of interning)

# The Core Python Programming Language {intro/summary}

## Naming things
[X] core|Naming a file identically to a standard library module
[X] core|Using `import *` 
[X] core|Bare or overly generic `except` statements

## {Top-level}
[X] core|Quadratic behavior of naive string concatenation
[X] core|Opening a file without a context manager 
[X] core|Not using `dict.get()` for uncertain keys
[X] core|The `key` optional argument to `.sort()` and `sorted()`

# Advanced Python Usage {intro/summary}
[X] advanced|Comparing `type(x) == type(y)`

## Naming things
[X] advanced|Overriding names in builtins
[X] advanced|Directly accessing a "protected" attribute

## Keep less-used features in mind
[X] advanced|Not knowing about f-string debugging
[X] advanced|Overlooking the elegant magic of decorators
[X] advanced|Failing to utilize `itertools` sufficiently
[X] advanced|Failing to notice the `more-itertools` third-party library

## Type annotations are not runtime types
[X] advanced|Mistaking type annotations for runtime constraints
[X] advanced|Mistaking `typing.NewType()` for a runtime type

# Just Because You Can, It Doesn't Mean You Should... {intro/summary}
[X] philosophy|Using metaclasses when you don’t really need to
[X] philosophy|Monkeypatching when you don’t really need to
[X] philosophy|Using getters and setters in a class
[X] philosophy|It’s easier to ask for forgiveness than permission
[X] philosophy|Not using structural pattern matching
[X] philosophy|Regular expressions that encounter catastrophic backtracking

# Picking the Right Data Structure {intro/summary}
[X] datastruct|Forgetting about `collections.defaultdict`
[X] datastruct|Forgetting about `collections.Counter`
[X] datastruct|Forgetting about `collections.deque`
[X] datastruct|Forgetting about `collections.ChainMap`
[X] datastruct|Not using dataclasses or namedtuples
[X] datastruct|Efficient concrete sequences

# Misusing Data Structures {intro/summary}
[X] datastruct2|Quadratic behavior for repeated list search
[X] datastruct2|Deleting or adding elements to the middle of a list
[X] datastruct2|Forgetting that strings are iterables of strings
[X] datastruct2|Using CONSTANT where `enum` would be more clear
[X] datastruct2|Expecting JSON to round-trip cleanly in generic Python
[X] datastruct2|Forgetting less common dictionary methods
[X] datastruct2|Rolling your own data structures

# Security {intro/summary}

## Kinds of randomness
[X] security|Using `random` rather than `secrets` for cryptographic randomness
[X] security|Using `secrets` rather than `random` for reproducible random distributions

## {Top-level}
[X] security|Putting passwords or other secrets in "secure" source code
[X] security|"Rolling your own" security mechanisms
[X] security|Skipping SSL/TLS for microservices
[X] security|Not using the third-party `requests` library
[X] security|SQL injection attacks from not using DB-APIs
[X] security|Using `assert` to check safety assumptions

# Numeric Computation in Python {intro/summary}

## Understanding IEEE-754 Floating Point Numbers
[X] numeric|Comparing NaNs (and other floating point numbers)
[X] numeric|NaNs and `statistics.median()`
[X] numeric|Naive use of floating point numbers: associativity and distributivity
[X] numeric|Naive use of floating point numbers: granularity

## Numeric data types
[X] numeric|Using floating point numbers for financial calculations
[X] numeric|Assuming obvious behaviors of numeric datatype

