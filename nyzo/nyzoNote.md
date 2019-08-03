# Notation on Proof of Diversity

## Introduction
Nyzo is a new subtle blockchain, which uses a new consensus algorithm called Proof of Diversity, other than poS or poW.
The following part of this article is about to analysis the technics Nyzo used,
mainly about how Proof of Diversity works,
and how we can design a similar system with different parameter.

## Technics Review
The technics Nyzo used could be basically divided into 3 parts:
1. Core poD block generation.
  Blocks creators will verify and freeze the later blocks in a certain manner based on score calculated.
  And rules of verification cycle and scoring intended to make verifier stable,
  which means new verifiers won't join clusterly, and majority of current verifiers won't be ignored.
2. Storage reduction by rentention and Trailing edge.
  Only the recent 4 cycles of blocks are stored, previous blocks are archieved by rentention block.
3. Incentive system which encourage verifiers behave properly.
  Distribute transaction fees to verifiers, and decrease non-zero addresses by maintenance fees.

Via 3 
## Retention and Trailing

frozen edge
trailling edge
retention edge

## Verification cycle
verification cycle rule
poD rule 1
poD rule 2

scoring
0 + 4 * (l1 - l2)
active verifier?

-6 + 4 * p

mesh (verification cycle size?)

## Incentive system & economic rational

References
1. [nyzo whitepaper](https://nyzo.co/whitePaper)
2. https://medium.com/@nyzoco/the-nyzo-mesh-time-and-diversity-as-a-currency-85c676631516
3. https://medium.com/@nyzoco/nyzo-addressing-arguments-against-proof-of-diversity-and-early-entrants-fa7cd4822012
4. https://medium.com/@facewithtearsofjoyemoji/nyzo-node-deployment-guide-b0251ee69ca9
5. [nyzo design document v0.3](https://docs.google.com/presentation/d/1hrXX6jgtcQYgl7qja94qnNQrFnUslKfy0V3Bed7f1QQ)
