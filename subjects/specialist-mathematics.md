# Specialist Mathematics

## Unit 1

### Multiplication and Addition Principle - 6A

And = Multiply  
Or = Add

### Permutation - 6B/C/D/J

Total permutations of $n$ elements. Order matters.

$$
n!
$$

Pick $r$ items from $n$. Order matters. No repetition.

$$
^nP_{r} = \frac{n!}{(n-r)!}
$$

Total permutations of $n$ elements. Order matters. With duplicates.  
$a$, $b$, $c$ etc. = number of repeated elements

$$
\frac{n!}{a!b!c!\dots}
$$

Example - ABBCCCD (2 As, 3 Cs):

$$
\frac{7!}{2!3!}
$$

### Combinations - 6E/F/J

Pick $r$ items from $n$. Order does not matter

$$
^nP_{r} = \frac{n!}{r!(n-r)!}
$$

### Inclusion Exclusion Principle - 6I

$\cap$ = intersection  
$\cup$ = union  
$A'$ = not  
$\emptyset$ = empty  
$\subseteq$ = subset or equal  
$|A|$ = number of elements  
$A \cup B$ = $A + B - A \cap B$

### Proof
#### Direct Proof - 7A

Symbols  
$\forall$ = For all  
$\in$ = Is an element of

Sets  
$\mathbb{Z}$ = Integers  
$Q$ = Rational numbers  
$R$ = Real numbers

#### Proof by Contrapositive

If *a* implies *b*, not *b* implies not *a*.

Example: if $x$ is even, $x^2+1$ is odd.  
Contrapositive: if $x^2+1$ is even, $x$ is odd.

#### Proof by Contradiction

Assume the opposite is true then show that that is nonsense.

Example: if $x$ is even, $x^2+1$ is odd.  
Contradiction: if $x$ is even, $x^2+1$ is even.  
Prove that this is wrong.

### Vectors

$\hat{i}$ = right vector  
$\hat{j}$ = up vector

$|x\hat{i}+y\hat{j}|$ = length of vector = $\sqrt{ x^2+y^2 }$  
$\hat{\underset{\sim}{a}}$ = unit vector (length 1) = $\frac{\underset{\sim}{a}}{|\underset{\sim}{a}|}$  

#### Dot Product

How much the vectors are pointing in the same direction.

$$
(a\hat{i}+b\hat{j})\cdot(c\hat{i}+d\hat{j})=ac+bd
$$

$$
\underset{\sim}{a}\cdot\underset{\sim}{b}=|\underset{\sim}{a}||\underset{\sim}{b}|\cos(\theta)
$$

$$
\underset{\sim}{a}\cdot\underset{\sim}{a}=|\underset{\sim}{a}|^2
$$

