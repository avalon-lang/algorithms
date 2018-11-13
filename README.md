# Quantum algorithms

This folder contains a collection of quantum algorithms.
The explanation of each algorithm here can be found in the documentation.

## Algorithms

Here is the list of the algorithms currently implemented and a bit of a description about them.
After the name of the algorithm is the name of the folder where to find the relevant code.

If you are new to quantum computing, please go over each algorithm from top to bottom. 
They are ordered in terms of difficulty as in the top most algorithm requires the understanding 
of fewer concepts than the one at the bottom.

In the description of each algorithm, you will find a link to the documentation that explains 
the algorithm. The documentation tries not to be heavy on the math but gives you enough to 
make sense of the implementation. If you desire to know more, the documentation contains 
reference to the relevant literature. For instance, a better understanding of Deutsch's algorithm 
involves understanding phase kickback. But this is not even mentionned in the documentation.
So keep that in mind as you read the docs and the source.

### Deutsch's algorithm: deutsch

Deutsch's algorithm solves the following problem: given a binary function, find out if 
it is constant (returns the same output for all inputs) or balanced (returns different outputs on different inputs).  
The classical version requires calling the function twice while the quantum version calls the function only once.

[Documentation](https://avalon-lang.readthedocs.io/en/latest/algorithms/deutsch.html)

## What is Avalon

Avalon is a programming language that targets hybrid classical-quantum computers. These computers 
contain a classical processor that tells a quantum processor what to do.

Avalon has a syntax similar to that of Python so if you know Python, you should be at ease working with it.  
It is statically typed though hence a bit more strict with compile time errors. But it also features 
type inference so you don't need to provide the type unless necessary.

## Why Avalon

Quantum computing is progressing and it needs tools among which programming languages are going to play 
a vital role. Yes, there exists other programming languages that target hybrid classical-quantum computers 
but I have found them to be lacking in abstractions and many even exposing hardware primitives 
making them unfriendly to the novice developer.

## How is the implementation going

Slowly but okay. I will add new algorithms as I get the time.


## Can I contribute

Kindly do so. But you must also contribute the relevant entry to the documentation so
not to leave users with code they don't understand.

## License

MIT license it is. Please see the LICENSE file for the terms.

## Contact

You can reach me at <a href="mailto:nbashige@gmail.com">nbashige@gmail.com</a>

## Copyrights

I, Ntwali Bashige Toussaint, retain all copyrights to this work and derivatives.
