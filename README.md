# IBM Quantum Challenge exercises

> Original versions of the exercises


## What's in this repository?

If you're reading this I hope it it because you already know about the
[IBM Quantum Challenge](https://quantum-computing.ibm.com/challenges). In this repository you will
find a copy of the exercises, some useful hints and a live FAQ we will fill-in as the challenge unfolds.

## How can I solve the exercises?

Take a look at the [`hints.md`](https://github.com/qiskit-community/may4_challenge_exercises/blob/master/hints.md) file to
receive some advice on how to solve the challenges.

## I'm having problems running the exercises, what can I do?

If you are experiencing problems when validating the exercises, try to:

**Do a backup of whatever code you want to save since these steps will restore you exercises to their initial state.**

1. Create a new Qiskit Notebook.
2. Add a new code cell and copy and paste this:

```
%pip install -I git+https://github.com/qiskit-community/may4_challenge.git@0.4.30
!git clone https://github.com/qiskit-community/may4_challenge_exercises.git ~/may4_challenge_exercises
!mkdir -p ~/may4-challenge
!cp -r ~/may4_challenge_exercises/* ~/may4-challenge
```

3. Run it.
4. Reload the exercises you had open and try if they work now.

## Where is the conversation happening?

<!-- Talk about the official channels in the Qiskit public slack -->
