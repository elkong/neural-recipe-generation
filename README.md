# An Investigation into Techniques for Neural Recipe Generation

Recipe generation is a case study in globally coherent structured text generation. In order to produce usable recipes, a system must have the ability to maintain highly complex and arbitrarily long-range dependencies between its ingredient list and its instructions. In this work we examine various NLG model architectures, including RNN-based models (Cho et al., 2014), attention-based models such as the checklist model (Kiddon et al., 2016), and transformer-based models such as GPT-2 (Radford et al., 2019). We compare and evaluate their capacities to produce sensible recipes using a combination of task-agnostic automated metrics, recipe-specific metrics, and human evaluation, and find that transformer-based models excel in global coherence.

The source code for this project is available here at https://github.com/elkong/neural-recipe-generation.

## Source code

Source code files are found as annotated Jupyter Notebooks in `./ipynb`.

