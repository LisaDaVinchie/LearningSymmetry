# LearningSymmetry

## Deep Learning assignment #1

In this first assignment of the *Deep Learning course*, you will be challenged to reproduce some experiments from the seminal paper that (probably) gave rise to the entire field of *Deep Learning*. Even though the experiments are definitely simple for today’s standards, their setup and execution may kickstart unexpectedly *deep* considerations about the subject.

The list that follow should provide you with essential guidance on how the assignment should be carried on.

1.   Read carefully the paper [*“Learning representations by back-propagating errors” (Rumelhart et al., 1986)*](https://www.nature.com/articles/323533a0). Read it in its entirety, but focus specifically on the experiment outlined in *Fig. 1* (learning mirror symmetries in 6-digits numbers).

2.   Reproduce in `PyTorch` (or any other *DL* library you are confident using) such experiment. Try to be as close as possible to the original protocol, with respect to network architecture, activation functions, learning algorithm and parameter initialization.

3.   Assess model accuracy, and inspect the weights of the trained network. Do they provide a solution to the problem?

4.   Compare the solution to the one reported in the original paper. Comment.
5.   **Optional:** you are warmly encouraged to explore and discuss additional variations to the experimental details and the results they produce on final accuracy and weights of the network. Some of such changes may include (but are not limited to):
     -   changing the activation functions of the network;
     -   changing the optimizer and/or its hyperparameters;
     -   adding a learning rate scheduler, *etc.*

Write a short report (approx. 1 page long) about your experimentation and reproduction results, and what such experience had made you learn. The final document should be a `jupyter` notebook containing both the report and the code cells necessary to reproduce your experiments. Please, also comment any nontrivial parts of your code.

**N.B.:** The very goal of this assignment is **not** that of exactly reproducing the results of the original paper. There are no *correct* or *incorrect* choices, as long as they are reasonable, convincing, and justified. Approach the problem with an open mind, and – most importantly – enjoy the journey!
