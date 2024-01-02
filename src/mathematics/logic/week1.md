- http://intrologic.stanford.edu/chapters/chapter_01.html
- https://gowers.wordpress.com/2011/09/25/basic-logic-connectives-and-and-or/
- https://www.coursera.org/learn/logic-introduction/supplement/TbjH8/chapter-1-introduction
- https://web.stanford.edu/class/archive/cs/cs103/cs103.1184/

- [ ] Connectives: And, Or, Not, Implies
- [ ] Quantifiers: "for all" "there exists"
- [ ] Relationships: negation, converse, contrapositive

# Logic

# and

In english, "and" is a logical connective between objects. Sam and Mar.
In maths, "and" is a logical connective between statements, each statement is asserted true or false on its own.
A statement is a declaration, conveys info or claims about something, i.e. is true or false; objects are nouns.
English: Sam and Mar (connecting objects) will eat dinner
Maths: sam will eat dinner (true or false) and mar will eat dinner (true or false). (connecting statements)
English: n is 2 and prime
Maths: n is 2 and n is prime

# or

It's inclusive or rather than exclusive.
English: sam or mar will pick you up. Either one will pick you up.
Maths: sam or mar will pick you up. sam will pick you up, or mar will pick you up, or sam and mar will pick you up.

# proofs

## theorem: $p$ is a prime number, let $a$ and $b$ be positive integers. Suppose $p$ is a factor of $ab$. Then either $p$ is a factor of $a$ or $p$ is a factor of $b$.

- initial thought is to prove $p$ is a factor of $a$. But... we don't know anything about $p$, $a$, $b$.

1. Assume $p$ is not a factor of $a$
2. Draw a consequence of the assumption. Use it to prove $p$ is a factor of $b$.
   e.g. "if $p$ is not a factor of a, then the highest common factor of a is 1"...

# Associativity

- P or (Q or R)” is the same as “(P or Q) or R
- P and (Q and R)” is the same as “(P and Q) and R

# Proof Writing

- Checklist https://web.stanford.edu/class/archive/cs/cs103/cs103.1184/handouts/120%20Proofwriting%20Checklist.pdf
