---
tags:
  - probability
---
# Symbols 

# $\Omega$ - Space of events

## Subset 
A subset is when all element of a set are also an element of another set. 

$A\subset \Omega$

The case $A=\Omega$ is possible but the previous is a proper subset while this is less so. // unsure

$A\subseteq \Omega$

### Properties


## Superset
Of course the opposite is true when a set contains all the elements of another. It is then a superset.

The equation also becomes flipped

$\Omega \supset A$

# Rules

## Bayes Rule
$P(A\mid B)=\frac{P(B\mid A)P(A)}{P(B)}$


## Gaussian Distribution
$f(x)=\frac{1}{\sqrt{ 2\pi\mu\sigma^2}}\exp\left( -\frac{(x-\mu)^2}{2\sigma^2} \right)$


# Basic probability Properties

$P(\Omega) = 1$ // entire space

$P(x)=\alpha$// is the probability of x happening

$P(\phi)=0$ // not the entire space

$P(x \cup y) = P(x) + P(y)$ // or

$P(x \cap y) = p(x) \cdot P(y)$ // and


$P(E^{c})=P(\Omega-E)=1-P(E)$ // 
- $\Omega-E=E^c$
![[Pasted image 20250210170058.png]]

$P(E_{1}\cup E_{2})=P(E_{1})+P(E_{2})-P(E_{1}\cap E_{2})$
- $E_{1}\cup E_{2}=(E_{1}\cap E_{2})\cup(E_{1}\setminus E_{2})\cup(E_{2}\setminus E_{1})$
	- $D_{1}=E_{1}\cap E_{2}$
	- $D_{2}=$
	- $D_{3}=$
- $P(E_{1}\setminus E_{2})=P(E_{1})-P(E_{1}\cap E_{2})$
- $P(E_{2}\setminus E_{1})=P(E_{2})-P(E_{2}\cap E_{1})$
![[Pasted image 20250210171105.png]]

# Conditional Probability

$P(B\mid A)=\frac{P(B\cap A)}{P(A)}=\frac{P(A,B)}{P(A)}$

![[Pasted image 20250210174548.png]]


# Probability Examples

## PE1
$S=D_{1}+D_{2}$

what is the $P(S=k),k=2,\dots,12$

say $S=5$


## PE2
#conditional_probability_example


