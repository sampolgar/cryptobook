# Set Theory

Exercises taken from

- [Rareskills](https://www.rareskills.io/post/set-theory)
- [Math Sorcerer](https://www.udemy.com/course/how-to-write-proofs-in-set-theory-with-the-math-sorcerer)

**Exercise:** Assume you have a proper definition for integers. Create a well-defined set of rational numbers.

- integers are whole numbers including 0 and negative numbers, i.e. -1, 0, 1
- \\( \int x dx = \frac{x^2}{2} + C \\)
- - \\( \mathbb{Z} = \{ \ldots, -2, -1, 0, 1, 2, \ldots \} \\)
- \\(\ \mathbb{Z} = \{...,-2,-1,0,1,2,.. \}\ \\)
- integers are the set of whole numbers

**Exercise:** Define the subset relationship between integers, rational numbers, real numbers, and complex numbers.

**Exercise:** Define the relationship between the set of [transcendental numbers](https://en.wikipedia.org/wiki/Transcendental_number) and the set of complex numbers in terms of subsets. Is it a proper subset?

**Exercise:** Using the formal definition of equality, show that if two finite sets have different cardinality, they cannot be equal. (Demonstrating this for infinite sets is a little trickier, so we skip that).

**Exercise:** Compute the cartesian product of B × A using the definitions above.

**Exercise:** Compute the cartesian product of {1,2,3,4} and {3,6,9,12} (in that order). If you were to pick 4 particular ordered pairs from this, what arithmetic computation would that encode?

**Exercise:** Define a mapping (function) from integers n ∈ 1,2,3,4,5,6 to the set {even, odd}.

**Exercise:** Take the cartesian product of the set of integers 0,1,2,…,8 and the polygons triangle, square, pentagon, hexagon, heptagon, and octagon. Define a mapping such that the integer maps to the number of sides on the shape. For example, the ordered pair (4, □) should be in the subset, but (7,△) should not be in the subset of the cartesian product.

**Exercise:** Define a mapping between positive integers and positive rational numbers (not the whole thing, obviously). It is possible to perfectly map the integers to rational numbers. Hint: draw a table to construct rational numbers where the columns are the numerators and the rows are the denominators. Struggle with this for at least 15 minutes before looking up the answer.

**Exercise:** Let set A be {1,2,3} and set B be {x,y,z}. Define a function from A to B that is well-defined, but not surjective and not injective.

**Exercise:** Pick a subset of ordered pairs that defines a \* b mod 3.

**Exercise:** Demonstrate the above statement is correct by reasoning from ((a, b), c) and ((b, a), c) and the definition of injective.

**Exercise:** Define our set A to be the numbers 0,1,2,3,4 and our binary operator to be subtraction modulo 5. Define all the ordered pairs of A ⨉ A in a table, then map that set of ordered pairs to A.

**Exercise:** Work out for yourself that concatenating “foo”, “bar”, “baz” in that order is associative. Remember, associative means (A op B) op C = A op (B op C).

**Exercise:** Give an example of a magma and a semigroup. The magma must not be a semigroup. Don’t use the examples above.

**Exercise:** Let our binary operator be the function min(a,b) over integers. Is this a magma, semigroup, or monoid? What if we restrict the domain to be positive integers (zero or greater)? What about the binary operator max(a,b) over those two domains?

**Exercise:** Let our set be all 3 bit binary numbers (a set of cardinality 8). Let our possible binary operators be bit-wise and, bit-wise or, bit-wise xor, bit-wise nor, bit-wise xnor, and bit-wise nand. Clearly this is closed because the output is a 3 bit binary number. For each binary operator, determine if the set under that binary operator is a magma, semigroup, or monoid.

**Exercise:** Why can’t strings under concatenation be a group?

**Exercise:** Polynomials under addition satisfy the property of a group. Demonstrate this is the case by showing it matches all the properties that define a group.
