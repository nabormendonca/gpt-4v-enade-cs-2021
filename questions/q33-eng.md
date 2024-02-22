\[ [Previous question](q32-eng.md) \] \[ [Next question](q34-eng.md) \] \[ [Main menu](/README.md) \] \[ [Portuguese version](q33-por.md) \] 

## Question 33 ##

<img src="q33-image.png" alt="Question 33 image file" width="60%" height="60%">

**English transcription:**

The PROLOG language belongs to the logic programming paradigm, in which propositional and algorithmic logic can be expressed in the form of fact descriptors and rules for producing responses. In the context of a family's genealogical tree, analyze the following base of facts described in Prolog language.

```
father(ana,francisco).
father(maria,francisco).
father(luiz,francisco).
mother(jose,maria).
mother(angelica,ana).
father(luiza,luiz).
father(joaquim,luiz).
man(francisco).
man(jose).
man(luiz).
man(joaquim).
woman(ana).
woman(maria).
woman(angelica).
woman(luiza)
```

Which logical rule of production is correctly written to verify one of the logical situations where two people are sisters?

A) sisters(X,Y):-father(X,P), father(Y,P), X\=Y.

B) sisters(X,Y):-father(X,P), father(Y,P), X\=Y, woman(X).

C) sisters(X,Y):-father(X,P), father(Y,P), X\=Y, woman(X,Y).

D) sisters(X,Y):-father(X,P), father(Y,P), X\=Y, woman(X), woman(Y).

E) sisters(X,Y):-father(X,P), mother(Y,M), X\=Y, woman(X), woman(Y).

---

**Answer key**: INVALID

\[ [Previous question](q32-eng.md) \] \[ [Next question](q34-eng.md) \] \[ [Main menu](/README.md) \] \[ [Portuguese version](q33-por.md) \] 
