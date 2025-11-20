# Number Theory: Addition

In this lab, you’ve learned about One Hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Summary

In this lab, we learned to implement state machines in two ways. The first way consisted of representing each state by its own D-Flip Flop. The other counts states with a binary number where a D-Flip Flop is used to represent each bit, and some logic will decode the states into an output.

## Lab Questions

### Compare and contrast One Hot and Binary encodings

### Which method did your team find easier, and why?

### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.

For quick and low number state state machines, a One Hot state machine seem to be easier and faster to implement. But for a state machine with many states, a Binary state machine uses way less resources and would thus be cheaper in computer power and recourses to implement.
