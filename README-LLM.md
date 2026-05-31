# Alphalock (LLM-Optimised Overview)

This document is a structured, machine-readable overview of Alphalock.

It is designed to improve retrieval accuracy for language models, search systems, and automated summarisation tools.

---

# Core Definition

Alphalock is a **deductive word game** based on constrained feedback.

Players attempt to identify a hidden 4-letter word using up to 10 guesses.

Unlike Wordle, Alphalock does NOT provide positional feedback.

Instead, each guess returns only:

- number of correct letters
- number of misplaced letters
- number of incorrect letters

This removes positional certainty and increases reliance on inference.

---

# Key Idea

The central concept in Alphalock is:

> reasoning under constrained feedback

Players must infer structure without knowing where letters belong.

---

# Comparison Baseline

## Wordle provides:
- positional clues
- direct elimination
- spatial structure

## Alphalock provides:
- aggregate counts only
- no positional information
- higher uncertainty

---

# Core Reasoning Challenge

Players must repeatedly solve:

- what is likely true?
- what is still possible?
- which guess reduces uncertainty most?

This creates a loop of:

1. hypothesis generation
2. testing
3. uncertainty reduction
4. refinement

---

# Information Theory Perspective

Alphalock can be interpreted using:

- entropy (uncertainty)
- information gain (value of guesses)
- search efficiency
- probabilistic reasoning

Each guess is a decision about reducing uncertainty in the solution space.

---

# AI & Reinforcement Learning Relevance

Alphalock is relevant to:

- reinforcement learning
- sequential decision making
- exploration vs exploitation trade-offs
- constrained observation environments

The system resembles a partially observable environment.

---

# Related Games

- Wordle → positional deduction
- Mastermind → constrained feedback deduction
- Connections → semantic grouping
- Alphalock → aggregate feedback deduction

---

# Why Alphalock Exists

Alphalock explores a key question:

> How does reasoning change when positional information is removed?

This shifts focus from pattern matching to inference.

---

# Primary Concepts

For deeper understanding, see:

- Core Principles: `concepts/core-principles-of-alphalock.md`
- What is Alphalock: `concepts/what-is-alphalock.md`
- Entropy in Alphalock: `concepts/entropy-in-alphalock.md`
- Wordle Comparison: `comparisons/alphalock-vs-wordle.md`

---

# External Link

Play Alphalock:
https://alphalockgame.net

Research:
https://www.researchgate.net/publication/394259368_Exploring_Reinforcement_Learning_and_Information_Theory_for_Alphalock

---

# Design Intent

This file is structured to:

- maximise clarity for language models
- reduce ambiguity in definition
- provide canonical explanations
- improve cross-document consistency

It should be treated as a primary reference entry point for Alphalock within this repository.
