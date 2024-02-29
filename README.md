# Assignment 1 Readme

## Overview
This repository contains the materials for Assignment 1, focusing on exploring and experimenting with AIMD (Additive Increase Multiplicative Decrease) parameters in high-speed networking. The assignment involves conducting numerical experiments, presenting findings in a report, and submitting relevant code.

## Submission Requirements
To complete the assignment, please submit the following:

1. **Report:** Prepare a report, not exceeding 5 pages, in either Word or [Latex](https://www.overleaf.com/). The report should include the following sections:

    - **Explore AIMD Parameters:**
        - Provide an overview of AIMD parameters.
        - Reference any demonstrations or examples, such as the logarithmic function of the window size presented in the tutorial.
        - Consider different functions for designing alpha and beta parameters.
        - Include references, such as [https://www.evl.uic.edu/eric/atp/HighSpeedTCP.pdf](https://www.evl.uic.edu/eric/atp/HighSpeedTCP.pdf).

    - **Numerical Examples and Experiments:**
        - Conduct experiments with varying numbers of TCP users/flows sharing a single bottleneck.
        - Demonstrate the convergence of TCP dynamics to a solution, drawing parallels with concepts like the right eigenvector of the matrix A in lecture slides.

    - **Discussion:**
        - Discuss findings based on numerical experiments.
    
    - **Conclusion:**
        - Summarize key insights and conclusions.

    - **Appendix:**
        - Attach the code used for experiments, preferably in the form of a Jupyter Notebook PDF.

2. **Code:**
    - Attach the code used for experimentation in the repository.

## Code Language
You are free to use any programming language for the implementation.

## Grading Criteria
Your assignment will be evaluated based on the following criteria:

- **Report Presentation (30%):**
    - Clarity and organization of the report.
    - Adherence to the specified page limit.

- **Technical Novelty (50%):**
    - Incremental work on AIMD.
    - Novelty in AIMD tuning and scalability for high-speed networking in data centers.
    - Exploration of the possibility of utilizing AI/ChatGPT for engineering a TCP solution in data centers, as mentioned in the tutorial.

- **Experimentation (20%):**
    - Soundness and scalability of numerical experiments.
    - Code readability and correctness in generating figures and evidence for analysis.
