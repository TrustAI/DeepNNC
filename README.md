# DeepNNC: Reachability Analysis of Neural Network Control Systems (AAAI 2023)

##
Neural network controllers (NNCs) have shown great promise in autonomous and cyber-physical systems. Despite the various verification approaches for neural networks, the
safety analysis of NNCs remains an open problem. Existing verification approaches for neural network control systems (NNCSs) either can only work on a limited type of activation functions, or result in over-approximation errors with time evolving. This paper proposes a verification framework for NNCS based on Lipschitzian optimisation, called DeepNNC. We first prove the Lipschitz continuity of closed-loop NNCSs by unrolling and eliminating the loops. We then reveal the working principles of applying Lipschitzian optimisation on NNCS verification and illustrate it by verifying an adaptive cruise control model. Compared to state-of-the-art verification approaches, DeepNNC shows superior performance in terms of efficiency and accuracy over a wide range of NNCs. We also provide a case study to demonstrate the capability
of DeepNNC to handle a real-world, practical, and complex system.

##

### Note: This work is just accepted by the Thirty-Seventh AAAI Conference on Artificial Intelligence (AAAI 2023). Now we are preparing for the final version of this work. Our tool will be released soon via this repository.

-- Chi Zhang & Wenjie Ruan
