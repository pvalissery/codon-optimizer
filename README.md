# codon-optimizer
A lightweight, zero-dependency, single-file web tool that optimizes amino acid sequences for heterologous expression across different host organisms. It balances host codon usage bias with structural heuristic penalties entirely on the client side.

Host-Specific Optimization: Supports codon usage tables for Escherichia coli, Saccharomyces cerevisiae (yeast), Homo sapiens (human), and Plasmodium falciparum (3D7).
Stochastic Monte Carlo Sampling: Allows users to tune the optimization entropy (temperature) to balance between strictly maximizing codon frequency and introducing sequence variation.
Structural Heuristic Penalties: Calculates and penalizes deviations from host-appropriate GC content windows, excessive homopolymer runs, and potential hairpin stem-loop structures.
Instant Metrics: Automatically computes the estimated Codon Adaptation Index (CAI), sequence GC percentage, structural flags, and outputs both mRNA (5′→3′) and coding DNA strands.
