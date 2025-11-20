# Number Theory: Addition

In this lab, you’ve learned about one-hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Summary

In this lab, we learned to implement state machines in two ways. The first way consisted of representing each state by its own D-Flip Flop. The other count states with a binary number where a D-Flip Flop is used to represent each bit, and some logic will decode the states into an output.

## Lab Questions

### Compare and contrast One Hot and Binary encodings

One-hot encoding works by using a flip-flop for each state, so that only one flip-flop is in a "1" state. One-hot encoding, thus, is considered simple next-state logic and typically runs faster with higher performance.
Binary encoding will have the states encoded in log2(N) flip-flops, so this will only use as few bits as needed. Having fewer flip-flops will result in higher complexity, as the logic needed to operate the states would be more intensive, thus having a slower performance.

### Which method did your team find easier, and why?

We found one-hot encoding to be easier, as the logic of moving from one state to the next seemed easier to understand. This was also seen in the program, as we had fewer mistakes or corrections within the logic, compared to the multiple corrections and struggles we encountered with the binary encoding.

### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.

For quick and low-number state machines, a one-hot state machine seem to be easier and faster to implement. But for a state machine with many states, a Binary state machine uses way less resources and would thus be cheaper in computer power and resources to implement.
