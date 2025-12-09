# Enzyme_Evo
This repository contains the prototype engine for Banbx. ot utilizes Large Language Models (LLMs) trained on evolutionary scale data (ESM -2) to predict stability-emhancing mutations in lignin-degrading enzymes (Laccases).
# The Problem
Traditional directed evolution (Phaage Display) requires billions of variants, which is slow and expensive.
# Our Solution
We use an _in silico_ pre-screening layer. by using this AI model to predict structural viability, we reduce the wet-lab search space by 99%, focusing only on high-probability candidates.
# Technical Stack
Model: Meta ESM-2 (Evolutionary Scale Modeling)
Architecture: Masked Language Modeling (MLM) for zero-shot mutation prediction
Target: Bamboo-degrading Laccase enzymes.
# Usage
This code inputs a wild-type gene sequence, tokenizes it, and queries the Transformer model to identify amino acid substitutions that maintain folding stability while altering catalytic properties.
