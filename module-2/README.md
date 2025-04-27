# Module 2: Transformer Architecture and Modern LLM Training

## Building on Module 1 Foundations

In Module 1, you explored the foundations of language modeling through a progressive journey:

- **Session 1.1** introduced next-word prediction as the core mechanism powering language models, showing how this simple capability enables complex behaviors
- **Session 1.2** explored n-gram models as the simplest approach to predicting text, and uncovered their fundamental limitations with sparse data
- **Session 1.3** revealed how neural representations address these limitations through dense vector embeddings that capture meaning
- **Session 1.4** examined how neural language models make predictions and learn from data, showing how they overcome n-gram limitations
- **Session 1.5** investigated specialized embedding techniques like Word2Vec and their semantic properties, while highlighting the limitations of static embeddings

This progression established the conceptual foundations for understanding language models: representation, prediction, and training. However, the models we've explored so far—n-grams and early neural approaches—fall far short of modern capabilities.

Module 2 bridges the gap between these foundational concepts and the architecture powering today's Large Language Models.

## Learning Objectives

By the end of this module, you should be able to:
- Understand how transformers process tokenized text rather than words
- Explain how position information is preserved in transformers
- Recognize how feed-forward networks store factual knowledge
- Comprehend attention mechanisms and their role in finding relevant context
- Describe how transformer blocks are structured and stacked
- Understand how residual connections enable deeper architectures
- Explain the modern LLM training process from pre-training to instruction tuning

## Sessions

### [Session 2.1: Tokens, Positions, and Feed-Forward Networks](./s2.1-prompt.md)
Explore why modern LLMs operate on tokens instead of words, how position information is encoded, and how feed-forward networks act as knowledge storage within transformers.

### [Session 2.2: Attention Mechanisms and Transformer Blocks](./s2.2-prompt.md)
Discover how attention mechanisms find relevant information across the context window and how transformer blocks combine attention with feed-forward networks.

### [Session 2.3: Scaling and Training Modern LLMs](./s2.3-prompt.md)
Learn how residual connections enable deeper networks, and explore the complete training pipeline from pre-training on raw text to instruction tuning.

## Key Concepts

- **Tokenization vs words**: Why subword tokens handle long-tail distributions better
- **Position embeddings**: Preserving sequential information in transformers
- **Feed-forward networks**: How factual knowledge is stored within the model
- **Attention mechanisms**: Finding relevant information across the context
- **Transformer blocks**: The fundamental computational unit of modern LLMs
- **Residual connections**: The optimization technique enabling deeper architectures
- **Pre-training and instruction tuning**: The two-phase approach to modern LLM training

## Connection to Module 1

Module 2 builds directly on the foundations established in Module 1:

1. The **next-token prediction** objective (Session 1.1) remains the central training mechanism, but enables more complex emergent capabilities at scale

2. While traditional **n-gram approaches** (Session 1.2) were limited by the sparsity problem, transformers use attention to dynamically access relevant context

3. The **word embedding** concept (Session 1.3) evolves into tokenized representations that handle the long tail of language more efficiently

4. The **neural language model architecture** (Session 1.4) expands into transformer blocks with specialized components for different aspects of language processing

5. The limitations of **static embeddings** (Session 1.5) are addressed by contextual representations through self-attention

This module reveals how the transformer architecture combines and extends these foundational concepts to create significantly more powerful language models.

## Progression to Module 3

After completing this module, you'll understand the core architecture and training process behind modern LLMs. Module 3 will build on this knowledge to explore how these models develop reasoning capabilities and how they're aligned with human values through techniques like RLHF (Reinforcement Learning from Human Feedback).
