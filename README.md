# MyShoppingCartDiscount
Mutation Testing Sample Project


Testing pyramid
https://www.kaizenko.com/what-is-the-testing-pyramid/

Overview of Code coverage


# Have you tested your tests



Introduction to mutation testing:
https://en.wikipedia.org/wiki/Mutation_testing#Mutation_testing_overview


## Concepts: 
1. competent programmer hypothesis
2. coupling effect


# What is a mutant:
(Credit) https://www.guru99.com/mutation-testing.html
https://www.guru99.com/images/m2.png


# Mutant Survived Vs killed:

## Our test when run against:

## Original Program : True

1. Mutant Program 1 : out of memory/into infinite loop (Discard)
2. Mutant Program 2: False (mutant is killed) - Good to go
3. Mutant Program 3: True (mutant has survived) - Here we have a problem


# Simplistic execution flow:
1. Mutants are generated in-memory
2. Tests are selected which will run against these mutants
3. Tests are executed against these mutants and mutation score is computed.


Options: History of mutation testing
http://pitest.org/
https://github.com/hcoles/pitest


https://gradle-pitest-plugin.solidsoft.info/


# Things to consider
## Cost: At time it is everything


# Well how does it work internally
## We don't need access to the source code.
## Bytecode is injected to the using the instrumentation API and the mutants are generated in-memory using the ASM's APIs

