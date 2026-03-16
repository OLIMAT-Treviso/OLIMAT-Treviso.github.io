---
title: "Combinatorics and Probability"
meta_title: ""
description: ""
draft: false
---

Combinatorics and probability are often considered among the most fascinating areas of olympiad mathematics.  
One reason is that they **do not require extensive prior knowledge**: many problems can initially be approached simply by reasoning.

Naturally, when problems become more complex, it is useful to know some typical techniques and tools.  
Over time one learns to recognize recurring structures and increasingly effective counting strategies.

Below are some of the most important topics to know.

---

### Fundamental topics

{{< tabs >}}

{{< tab "Counting" >}}

#### Factorials

The factorial of a natural number $n$, denoted $n!$, is the product of all positive integers from 1 to $n$.  
It frequently appears in counting problems and in formulas for permutations and combinations.

#### How to count

Many combinatorial problems reduce to **correctly counting the possible objects**.  
Learning how to organize counting, avoid duplicates, and divide the problem into cases is one of the most important skills in combinatorics.

#### Binomial coefficients

The binomial coefficients

$$
\binom{n}{k} = \frac{n!}{k!(n-k)!}
$$

represent the number of ways to choose $k$ elements from a set of $n$ elements.  
They appear in many counting problems and are related to the expansion of the **binomial theorem**.

{{< /tab >}}

{{< tab "Permutations and combinations" >}}

#### Permutations

Permutations count the possible ways of **ordering all elements of a set**.  
For example, the number of ways to arrange $n$ distinct objects is $n!$.

#### Circular permutations

When the order is arranged **on a circle**, some permutations become equivalent because they can be obtained by rotating the configuration.

#### Anagrams

Anagrams are permutations of the letters of a word.  
They become particularly interesting when some letters are repeated, because identical configurations must not be counted multiple times.

#### Arrangements

Arrangements count the ways to **choose and order** some elements of a set.  

They can be:

- **without repetition**, if elements cannot repeat  
- **with repetition**, if the same element may be used multiple times

#### Combinations

Combinations count the ways to choose elements **without considering order** (unlike arrangements).

They can be:

- **without repetition**  
- **with repetition**

They are among the most frequently used tools in combinatorics.

{{< /tab >}}

{{< tab "Probability" >}}

#### Sample space

When studying a random phenomenon, one defines the **sample space of possible outcomes**.  
The probability of an event is often calculated as

$$
\frac{\text{favorable outcomes}}{\text{possible outcomes}}
$$

when all outcomes are equally likely.

#### Types of events

In exercises it is important to recognize the relationship between events:

- **disjoint events**
- **independent events**
- **dependent events**

This allows the correct application of probability rules.

#### Conditional probability

Conditional probability measures the probability that an event occurs **given that another event has already occurred**.

#### Bayes’ theorem

Bayes’ theorem allows one to update a probability in light of new information and is a fundamental tool in many modern applications.

{{< /tab >}}

{{< /tabs >}}

---

### Where to start preparing

The prerequisites of combinatorics (factorials, permutations, combinations, arrangements, anagrams, …) and of probability based on counting favorable outcomes are normally covered in fourth-year mathematics textbooks in Italian scientific high schools.

However, it is not necessary to start from a school textbook. Below are some particularly useful resources.

#### Recommended online course

An excellent starting point is the online course by **Prof. Emanuele Callegari** (University of Rome Tor Vergata).  
We especially recommend starting with **lessons 1, 2, and 3**.

🎬 https://www.problemisvolti.it/CorsoBaseOlimpiadiMatematica.html

Further information can be found on the dedicated page [here](/en/materiali/corso-callegari).

#### Lecture notes with exercises

We also recommend the very comprehensive combinatorics lecture notes by **Prof. Luciano Mezzini**, emeritus mathematics teacher at the "Leonardo da Vinci" Scientific High School in Treviso and coach of the school teams that won the Italian national team competition in 2009 and 2011.

{{< button label="📑 Combinatorics (Mezzini)" link="../pdf/Calcolo_combinatorio_2015_Luciano_Mezzini.pdf" style="solid" >}}

#### Recommended books

For further study, several volumes from the **U Math** series are very useful:

- **Combinatorics** ▸ Maurizio Trombetta  
  ISBN: 978-88-96973-68-4  
  https://scienzaexpress.it/catalogo/calcolo-combinatorio/

- **Probability** ▸ Luigi Amedeo Bianchi  
  ISBN: 979-12-800-6809-5  
  https://scienzaexpress.it/catalogo/probabilita/

- **Problem-Based Combinatorics** ▸ Emanuele Callegari  
  ISBN: 979-12-800-6811-8  
  https://scienzaexpress.it/catalogo/combinatoria-per-problemi/

In the [**Resources**](/en/risorse/collana-u-math) section of the website you can find further information about the **U Math** series and other useful materials for training.