# Continuous Assessment 1

> ECM3422 - Computability and Complexity

This CA comprises 20% of the overall module assessment. 

This is an individual exercise, and your attention is drawn to the guidelines on collaboration and plagiarism in the College handbook.

## Multitape Non-Deterministic Turing Machine

### Task

Design a multitape non-deterministic Turing machine, in order to decide the following language:

> **L** = {A#B#W1# . . . #Wn|A, B, Wi ∈ {a, b} +, |A| > |B|, n = 2|A| + |B|, A ⊆ Wi if i is even, B ⊆ Wi if i is odd}

The **solution** should include:

1. A transition diagram for the machine.
2. A detailed state-by-state breakdown of the operation of the machine. This should include a description, for each state, of what the machine is doing while in that state.

The **marking** will be dependent on:

- Correctly deciding the language **L**.
- Mistakes in the design (i.e. how close is it to a working solution).
- The layout of the diagram (clear and legible).
- The completeness, clarity and agreement of the state-by-state breakdown.

Possible **penalties** include:

- The use of non-determinism, where determinism will receive a penalty of 40 marks.
- The use of the "guess and check" principle, where not using it receives a penalty of 20+ marks.
- The avoidance of off-by-one errors, where implementing one receives a penalty of 5 marks.
- The validation of language properties, where not checking is penalised proportionally.
- The non-excessive use of tapes, states or symbols, where excess is penalised by 5 marks.
