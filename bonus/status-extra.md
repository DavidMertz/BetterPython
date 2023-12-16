# Test Driven Development (or lack thereof)
[-] tests|Failing to use doctests
[ ] tests|Failing to include unit tests
[ ] tests|Using unittest rather than pytest 
[ ] tests|Failing to run tests in CI/CD pipelines
[ ] tests|Only testing static/canonical data
[ ] tests|Not including endpoint tests
[ ] tests|Testing quirks of an existing implementation
[ ] tests|Test your tests!

# Basic Concurrency Abstractions
[ ] concurrency|Forgetting about the Global Interpreter Lock
[ ] concurrency|Fearing the GIL more than is merited
[ ] concurrency|Using `threading` where `multiprocessing` would be a better choice
[ ] concurrency|Using `multiprocessing` where `threading` would be a better choice
[ ] concurrency|Using `threading` or `multiprocessing` where `async` would be a better choice
[ ] concurrency|Premature (or false) optimization of concurrency 

# Concurrency Pitfalls
[ ] concurrency2|Race conditions
[ ] concurrency2|Deadlocks
[ ] concurrency2|Excessive busy waiting
[ ] concurrency2|Concurrency safe and unsafe data structures
[ ] concurrency2|Async coroutines that perform large computations without yielding
[ ] concurrency2|Using locks without wrapping them as context managers
[ ] concurrency2|Using `time.sleep()` rather than a fine-tuned `.wait()` within threads

