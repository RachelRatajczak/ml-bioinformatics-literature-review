# Machine Learning in Bioinformatics: Literature Review

This repository contains a curated literature review on applications of machine learning in bioinformatics. It summarizes key studies, methodologies, datasets, and trends in computational biology research.

## Project Structure

papers/ # References and links to reviewed papers (references.md)
review/ # Literature review (ml-bioinformatics-literature-review.pdf)


## How to Use

1. Browse the `review/` folder for literature review summaries.  
2. Check `papers/references.md` for a list of references used.  
3. All citations in the literature review link directly to the references for easy navigation.

## Summary

This literature review explores the application of machine learning techniques to biological sequence data, including DNA, RNA, and protein sequences. The review traces the progression from traditional computational biology methods—such as sequence alignment and statistical modeling—to modern approaches that leverage embeddings and transformer-based language models.

Key highlights include:

- **Predicting Pathogen Evolution:** Machine learning techniques can anticipate viral mutations and support public health preparedness [1].
- **Transformer Models for Biological Sequences:** Self-attention mechanisms, as introduced in the Transformer architecture [2], enable models to capture long-range dependencies in sequences, analogous to natural language processing.
- **Embedding Techniques:** BioVec/ProtVec embeddings [3] convert sequences into meaningful vector representations, improving protein classification and feature extraction.
- **Transformer Protein Language Models:** PRoBERTa [4] combines embeddings with transformer architectures to predict protein families and interactions with high accuracy.
- **RNA Language Models:** RiNALMo [5] applies transformer-based models to RNA sequences, demonstrating the scalability and predictive power of modern sequence models.

Overall, the review shows that machine learning has significantly reshaped biological sequence analysis by enabling large-scale, interpretable, and accurate predictions. While challenges remain, such as model interpretability, data availability, and overfitting; these approaches are driving the next generation of computational biology research.


