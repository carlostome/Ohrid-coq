# The Coq proof assistant for proving and programming

[In this course](http://robbertkrebbers.nl/typessummer2017/) you will learn how to use Coq to formalize a program logic for a small imperative programming language. Our program logic will be based on separation logic to aid proving properties about programs that use pointers.

The topics of the four lectures are as follows:

1. Basic data structures and tactics in Coq: you will learn how to use the basic faculties of Coq to do proofs about basic data structures.
  Suggestion for an exercise by Connor: try to define the type map as a dependent type in Agda, where you have an index that corresponds to the may_be_nil argument of my map_wf predicate.
2. Operational semantics: you will learn how to formalize the operational semantics of a simple imperative programming language.
3. Reasoning about finite maps: you will learn how to reason about finite maps; this will be needed to formalize a separation logic in the next lecture.
  (In the beginning of the lecture, I will start with the small step operational semantics of the material of lecture 2, which we skipped during class.)
4. Separation logic: you will learn how to formalize a separation logic for our imperative language in Coq.

Answers of the exercises are available on request (by contacting [Robbert Krebbers](http://robbertkrebbers.nl/#contact)).
