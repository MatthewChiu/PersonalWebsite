---
title: Sanderson Novels
tags:
  - oddLinks
---
My brother-in-law likes the Brandon Sanderson "Stormlight Archive" series. In our discord he posted about the increasing word count of each book (below), extrapolating to potential books (my mother-in law said *"ok, since I know you've done it, linear regression extrapolation to Stormlight 25?"*) 

![[sandersonStromlightLinear.png]]


Fantasy/sci-fi books usually have a lot of invented nouns/proper nouns. So then it got me thinking: how many of those words are _new_ within a book? In a series, even though the books get longer, there's probably some repetition of the words to immerse the reader in the universe, right? 

When we plot total word count against the percent of unique words in each, we see that the first book has the highest percent of unique words per word count! So, in a way, though it is the shortest, it is the most *informationally dense*... Hmmmm... "information."

![[sandersonStormlight.png]]

So that got me thinking about information and *entropy*: entropy is a quantification of the randomness of the outcomes. Its calculated as $H$ $$H=\sum_{x\in X}{p(x)log_2(x)}$$
The higher the entropy, the more chaotic the outcomes: for example, a coin flip or a dice roll is random, so they will have high entropy values.

![[sandersonAdditionalBooks.png]]



![[sandersonEntropy.png]]

[Here's some code.](https://colab.research.google.com/drive/1lV35RNSX99z_f5gWywJz4gBUri1VSFL6?usp=sharing)

(Oh yeah, I've never read these books...)