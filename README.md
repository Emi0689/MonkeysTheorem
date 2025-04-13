# Infinite monkey theorem
## Genetic Algorithms

A web app, created in .NET with Blazor to represent The infinite monkey theorem, using a Generic Algorithm (A.I.) to reconstruct a sentence, similar to how subtitles on the fly work, in which the "monkeys" work to reconstruct the sentence.

![monos simpsons](https://ep01.epimg.net/elpais/imagenes/2015/04/30/ciencia/1430420317_959498_1430423238_sumario_normal.jpg)

The *infinite monkey theorem* states that a monkey pressing random keys on a keyboard for an infinite period of time will almost certainly be able to eventually type any given text. In the English-speaking world Shakespeare's Hamlet is often used as an example, while in the Spanish-speaking world Cervantes' Don Quixote is used.

But if instead of taking an infinite time, we apply *genetic algorithms* to the behavior of these monkeys, we could reduce that time?

To achieve this, we need a sentence to be reproduced by our monkeys, and then a group of N monkeys, each creating a random sentence of characters and symbols.
To know if our monkeys are close to the phrase, we will take as a fitness function the proportion of characters that match the phrase. In this way we will select the next generations of monkeys according to different mechanisms.
