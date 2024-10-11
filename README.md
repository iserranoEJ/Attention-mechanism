# Attention Mechanism Notebooks

## Introduction

This repository contains a collection of Jupyter notebooks designed to explain and illustrate various attention mechanisms used in modern natural language processing and machine learning. The notebooks are intended for educational purposes, providing step-by-step implementations and visualizations of different attention techniques. These notebooks do not provide optimized implementations of any of these techniques.

## Contents

1. **Self Attention**: Basics of the self-attention mechanism.
2. **Masked Self Attention**: Implementation of masked self-attention used in decoder architectures.
3. **Multi-Headed Attention**: Exploration of multi-headed attention as used in transformer models.
4. **Linformer**: Implementation of the Linformer attention mechanism for efficient transformers.
5. **Longformer**: Implementation of the Longformer efficient attention mechanism designed to handle very long sequences.
6. **Performer**: Demonstration of the Performer attention mechanism using random feature approximation.
7. **Sparse Attention**: Implementation of sparse attention patterns for efficient computation.
8. **Attention Visualization**: Advanced visualization techniques for various attention mechanisms, including animated attention patterns and word-to-word attention visualization.

## Purpose

The primary goal of these notebooks is to provide a clear, visual understanding of how different attention mechanisms work. Each notebook includes:

- Theoretical explanations of the attention mechanism
- Step-by-step implementation in PyTorch
- Visualizations of intermediate steps and outputs
- Comparisons with standard attention where applicable

## Important Note

These implementations are for educational purposes only and are not optimized for production use. For real-world applications, it's recommended to use well-optimized implementations provided by libraries such as Hugging Face Transformers, PyTorch, or TensorFlow.

## Key Resources

1. **"Attention Is All You Need"** by Vaswani et al. (2017) - The original transformer paper that introduced the self-attention mechanism.
   [https://arxiv.org/abs/1706.03762](https://arxiv.org/abs/1706.03762)

2. **"The Illustrated Transformer"** by Jay Alammar - An excellent visual guide to transformers and attention mechanisms. Many of the images used in the self-attention notebook are from this blog post.
   [http://jalammar.github.io/illustrated-transformer/](http://jalammar.github.io/illustrated-transformer/)

3. **"Linformer: Self-Attention with Linear Complexity"** by Wang et al. (2020) - Introduces the Linformer mechanism for efficient attention computation.
   [https://arxiv.org/abs/2006.04768](https://arxiv.org/abs/2006.04768)

4. **"Rethinking Attention with Performers"** by Choromanski et al. (2020) - Presents the Performer attention mechanism using random feature approximation.
   [https://arxiv.org/abs/2009.14794](https://arxiv.org/abs/2009.14794)

5. **"Generating Long Sequences with Sparse Transformers"** by Child et al. (2019) - Introduces sparse attention patterns for efficient computation in transformers.
   [https://arxiv.org/abs/1904.10509](https://arxiv.org/abs/1904.10509)

## Additional Reading

- "Efficient Transformers: A Survey" by Tay et al. (2020) - A comprehensive overview of various efficient transformer architectures.
  [https://arxiv.org/abs/2009.06732](https://arxiv.org/abs/2009.06732)

- "A Survey of Long-Term Context in Transformers" by Peng et al. (2022) - Discusses various techniques for extending the context length in transformer models.
  [https://arxiv.org/abs/2307.03170](https://arxiv.org/abs/2307.03170)

## Potential Additional Notebooks

1. **Big Bird**: Exploration of the Big Bird attention pattern for efficient processing of long sequences.
2. **Reformer**: Implementation of the Reformer architecture using locality-sensitive hashing for efficient attention.
3. **Sliding Window Attention**: Demonstration of the sliding window attention pattern for local context modeling.

## Contributing

Contributions to improve the notebooks or add new attention mechanisms are welcome. Please feel free to submit pull requests or open issues for discussion.

## Acknowledgments

- Jay Alammar for his excellent visualizations (which I use in [self attention notebook](basics/self_attention.ipynb)) and explanations in "The Illustrated Transformer"
