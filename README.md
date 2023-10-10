# Large Language Models and Topic Modelling for Textual Information Extraction and Analysis

This repository contains the code used for my submission for DrivenData's [Unsupervised Wisdom: Explore Medical Narratives on Older Adult Falls](https://www.drivendata.org/competitions/217/cdc-fall-narratives/) competition. The goal of the challenge was to identify effective methods of using unsupervised machine learning to extract insights about older adult falls from emergency department narratives.

My submission, titled "Large Language Models and Topic Modelling for Textual Information Extraction and Analysis" explored the usage of Text2Text Generation transformers with big narratives (a custom prompt in human-readable format that uses a combination of tabular data and the available narratives). The big narratives provide the transformers with a more complete understanding of what happened. Meanwhile, the transformers receive the big narratives with a number of specific questions as prompts in order to automatically extract certain textual information present in the narratives, such as precipitating events, activity involved and a more thorough diagnosis of the event. Finally, I also employ topic modelling (with LDA) to create categories from the information that was extracted from the narratives, allowing for an easy way to explore the data and find correlations.

This repository is structured as follows:
- `main.ipynb`: Jupyter notebook file containing my complete analysis, thoroughly explained.
- `Summary_Marcos_Tidball.pdf`: an executive summary explaining my analysis and demonstrating how it can be applied.
- `data`: repository containing the datasets provided by the competition hosts.
