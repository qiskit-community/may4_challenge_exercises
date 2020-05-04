# IBM Quantum Challenge exercises

Original version of the exercises in the [IBM Quantum Challenge](http://ibm.co/quantumchallenge).

## What's in this repository?

In this repository you will find a copy of the exercises in the [IBM Quantum Challenge](http://ibm.co/quantumchallenge), some useful hints and a live FAQ that we will fill-in as the challenge unfolds.

## I'm stuck. How can I solve the exercises?

Take a look at the [`hints.md`](https://github.com/qiskit-community/may4_challenge_exercises/blob/master/hints.md) file for some advice on how to solve the challenges.

## I'm having problems validating my solutions to the exercises, what can I do?

If you are experiencing problems when validating the exercises, try the following. **Before you proceed, please keep a backup of your solutions since these steps will restore the exercises to their initial state and delete your progress.**

1. Create a new Qiskit Notebook.
2. Add a new code cell, and then copy-and-paste this:

```
%pip install -I git+https://github.com/qiskit-community/may4_challenge.git@0.4.30
!git clone https://github.com/qiskit-community/may4_challenge_exercises.git ~/may4_challenge_exercises
!mkdir -p ~/may4-challenge
!cp -r ~/may4_challenge_exercises/* ~/may4-challenge
```

3. Run the cell by pressing `Shift`+`Enter`.
4. Reload the exercises that you opened again.

## Where is the conversation happening?

There is a channel (`#ibm-quantum-challenge`) dedicated to the Challenge in [Qiskit Slack](http://qisk.it/slack). Join the conversation!
