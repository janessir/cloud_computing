<h1>Assignment 1<h1><br>
To submit:

- Report (not more than 5 pages) in Word/ [Latex](https://www.overleaf.com/)
- Sections to include
    - Explore AIMD parameters
        - Eg: prof demonstrated a code with the alpha parameter being the logarithmic function of window size in tut
        - Consider different functions to design alpha and beta parameters
        - Reference: https://www.evl.uic.edu/eric/atp/HighSpeedTCP.pdf
    - Numerical examples and experiments with different number of TCP users/ flows sharing a single bottleneck
        - Show that the TCP dynamics converge numerically to some solution
            - Eg: the right eigenvector of the matrix A in the lecture slides
    - Discussion based on your numerical experiments
    - Conclusion
    - Attach code in Appendix (eg jupyter notebook pdf)

Can code in any language 

Grading criteria:

- Report presentation (30%)
- Technical Novelty (50%)
    - Eg: Is your AIMD incremental work, or is it novel with the analysis to show insights?
        - Is the AIMD tuning novel and scalable for high-speed networking in data centre?
        - Can we use AI/ChatGPT as used as mentioned in tutorial to engineer a TCP ex machina for data centres?
- Experimentation (20%)
    - Sound & scalable?
        - Code readability and working correctly to generate figures/ evidences to your analysis?
