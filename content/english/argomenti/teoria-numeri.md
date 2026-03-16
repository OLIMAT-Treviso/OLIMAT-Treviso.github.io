---
title: "Number Theory"
meta_title: ""
description: ""
draft: false
---

Number theory is one of the most classical areas of olympiad mathematics.  
It mainly deals with **properties of integers**, prime numbers, and arithmetic relationships between numbers.

Unlike combinatorics, many number theory problems require **specific techniques**.  
However, once the fundamental tools are learned, it becomes possible to tackle very different problems using common ideas such as divisibility, congruences, and factorizations.

Many results in number theory also form the basis of modern applications, for example in **cryptographic systems** used in computer security.

Below are some of the most important topics to know.

---

### Fundamental topics

{{< tabs >}}

{{< tab "Divisibility" >}}

#### Prime numbers and factorization

A **prime number** is an integer greater than 1 whose only divisors are 1 and itself.

Every natural number can be written uniquely (up to the order of the factors) as a product of prime numbers: this property is known as the **Fundamental Theorem of Arithmetic**.

Prime factorization is one of the most frequently used tools in number theory problems.

#### Greatest common divisor and least common multiple

The **greatest common divisor** (gcd) of two numbers is the largest integer that divides both of them.  
The **least common multiple** (lcm) is the smallest positive number that is a multiple of both.

They are often computed using the **Euclidean algorithm**, a very efficient procedure based on division with remainder.

#### Bézout’s identity

For two integers $a$ and $b$ there always exist integers $x$ and $y$ such that

$$
ax + by = \gcd(a,b)
$$

This relation is known as **Bézout’s identity** and is fundamental in the study of Diophantine equations and congruences.

{{< /tab >}}

{{< tab "Congruences" >}}

#### Modular arithmetic

Two integers $a$ and $b$ are **congruent modulo $n$** if they have the same remainder when divided by $n$.

This is written as

$$
a \equiv b \pmod{n}
$$

Modular arithmetic allows us to work with remainders of divisions and simplifies many arithmetic problems.

#### Congruence classes

Integers can be divided into **congruence classes** modulo $n$, each represented by one of the possible remainders.

This viewpoint is very useful for studying properties of numbers and solving modular equations.

#### Linear congruences

A linear congruence has the form

$$
ax \equiv b \pmod{n}
$$

Its solvability depends on the relationship between $a$, $b$, and $n$, in particular on the **greatest common divisor** of $a$ and $n$.

{{< /tab >}}

{{< tab "Theorems and applications" >}}

#### Fermat’s little theorem

If $p$ is a prime number and $a$ is not a multiple of $p$, then

$$
a^{p-1} \equiv 1 \pmod{p}
$$

This result is one of the most frequently used tools in olympiad problems involving powers modulo a prime number.

#### Euler’s totient function

The **Euler totient function** $\varphi(n)$ counts how many integers between $1$ and $n$ are coprime with $n$.

It has an important property: it is **multiplicative**, meaning that if $a$ and $b$ are coprime then

$$
\varphi(ab) = \varphi(a)\varphi(b)
$$

From this function follows **Euler’s theorem**, a generalization of Fermat’s little theorem.

#### Systems of congruences

In some problems it is necessary to solve several congruences simultaneously.  
The fundamental result in this context is the **Chinese remainder theorem**, which allows solutions to be found when the moduli are coprime.

#### Diophantine equations

**Diophantine equations** are equations that require integer solutions.

The simplest case is the linear equation

$$
ax + by = c
$$

which can be solved using the Euclidean algorithm or Bézout’s identity.

{{< /tab >}}

{{< /tabs >}}

---

### Where to start preparing

Number theory **does not appear extensively in standard school curricula**.  
Some basic topics (such as factorization, gcd, and lcm) are covered in mathematics textbooks, but most olympiad techniques require specific materials.

Below are some particularly useful resources that we recommend following in order.

---

#### 1. Online course by Prof. Callegari

An excellent starting point is the online course by **Prof. Emanuele Callegari** (University of Rome Tor Vergata).  
For number theory we especially recommend starting with **lessons 4, 5, 6, and 7**.

🎬 https://www.problemisvolti.it/CorsoBaseOlimpiadiMatematica.html

Further information can be found on the dedicated page [here](/en/materiali/corso-callegari).

---

#### 2. Notes by Prof. Archetti

After watching the introductory lessons from Callegari’s course, you can study further using lecture notes from the **Treviso Territorial Olympiad Training Camps**, prepared by **Prof. Maria Archetti**.

These notes cover several important topics in olympiad number theory. All the materials can be found on the dedicated page:

📄 [Materials by Prof. Archetti](/en/materiali/materiale_archetti)

---

#### Recommended books

For further study, several volumes from the **U Math** series are very useful:

- **Modular Arithmetic** ▸ Salvatore Damantino, Emanuele Campeotto  
  ISBN: 978-88-96973-87-5  
  https://scienzaexpress.it/catalogo/aritmetica-modulare/

- **Number Theory** ▸ Salvatore Damantino  
  ISBN: 978-88-96973-70-7  
  https://scienzaexpress.it/catalogo/teoria-dei-numeri/

In the [**Resources**](/en/risorse/collana-u-math) section of the website you can find further information about the **U Math** series and other useful materials for training.

Other recommended texts:

- **Algebra and Discrete Mathematics** ▸ Andrea Facchini  
  ISBN: 978-8808097392  
  https://www.zanichelli.it/ricerca/prodotti/algebra-e-matematica-discreta

- **Elements of Algebra** ▸ Franciosi, De Giovanni  
  ISBN: 978-88-7999-024-0  
  https://www.aracne-editrice.it/index.php/pubblicazione.html?item=9788879990240