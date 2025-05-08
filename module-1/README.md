## Module 1: Foundations of Word Prediction and Embeddings

**In this module**, you'll discover the foundational concepts that power modern AI language systems. We'll explore how these systems learn to recognize patterns in language and use them to predict what comes next - a seemingly simple capability that enables much more complex behaviors.

### What You'll Discover

- **The Power of Pattern Recognition**: How AI learns to identify and leverage patterns in text - the fundamental building block of all deep learning approaches
- **Prediction as a Foundation**: How learning to predict the next word creates a necessary (though not sufficient) building block for advanced AI behaviors we'll explore further in Module 3
- **From Symbols to Meaning**: How representing words as mathematical points allows AI to capture relationships and meanings without explicit programming
- **Meaning Through Context**: How words get their meaning from the company they keep, and how AI learns to map these relationships
- **Mathematical Maps of Language**: How embedding words in a "meaning space" allows AI to discover connections between concepts like "king-queen" or "France-Paris"

### Technical Objectives (for CS+ students)

By the end of this module, you should be able to:
- Understand how next-word prediction serves as the foundation for LLMs
- Experience how this simple concept enables complex capabilities like instruction following
- Build a simple n-gram predictor and understand its limitations
- Recognize why more sophisticated approaches like word embeddings are necessary
- Differentiate between supervised and unsupervised approaches to language modeling
- Understand how word embeddings capture semantic relationships

## Three-Tier Learning Structure

This module, like all others in the curriculum, follows a three-tier approach that accommodates learners with different backgrounds:

### Core Concepts (For Everyone)
- Accessible explanations using analogies and visualizations
- No programming or mathematical background required
- Focus on intuitive understanding of fundamental principles
- Suitable for all learners regardless of technical background

### Hands-On Implementation (For CS Students)
- Practical code examples using PyTorch
- Implementation details and programming exercises
- Requires basic programming knowledge
- Best for those with computer science background

### Advanced Theory (For the Curious)
- Mathematical foundations and theoretical details
- Connections to broader information theory and research
- Formal definitions and derivations
- Appropriate for those interested in deeper theoretical understanding

You can freely navigate between these tiers based on your interests and background. All learners should engage with the Core Concepts tier, while the other tiers are optional based on your background and learning goals.

## Sessions

### [Session 1.1: Understanding Next-Word Prediction](./s1.1-prompt.md)
Explore how prediction serves as the foundational mechanism behind language models, and how this simple concept enables complex capabilities like answering questions and following instructions.

### [Session 1.2: Building Your First N-gram Predictor](./s1.2-prompt.md)
Experience firsthand the process of building a simple statistical language model, and discover through hands-on coding why more sophisticated approaches are needed.

### [Session 1.3: From N-grams to Neural Representations](./s1.3-prompt.md)
Discover how neural approaches can represent words as vectors in a continuous space, addressing fundamental limitations of discrete n-gram representations.

### [Session 1.4: Neural Language Model Prediction and Training](./s1.4-prompt.md)
Explore how neural language models make predictions and learn from data, understanding the complete architecture from input to prediction and how models are evaluated using perplexity.

### [Session 1.5: Advanced Word Embeddings and Applications](./s1.5-prompt.md)
Investigate specialized embedding techniques like Word2Vec, explore the fascinating semantic properties of word vectors, and understand the trade-offs between supervised and unsupervised approaches.

## Key Concepts

- **Next-token prediction**: The core predictive task that underlies all language models
- **Instruction following**: How prediction enables AI to follow complex instructions
- **N-gram models**: Simple statistical approaches based on token frequency
- **Tokenization**: How text is broken into processable units
- **Neural language models**: Using neural networks to predict words based on context
- **Word embeddings**: Dense vector representations that capture word meaning
- **Supervised vs. unsupervised learning**: Different approaches to training language models
- **Training vs. inference**: How models learn patterns and make predictions
- **Semantic properties**: How embeddings capture relationships between words
- **Perplexity**: Measuring the quality and predictive power of language models
- **Limitations of static embeddings**: Why we need more sophisticated approaches

## Session Progression

This module follows a logical progression:

1. **Session 1.1**: Introduces the fundamental concept of next-word prediction and how it enables complex capabilities
2. **Session 1.2**: Explores the simplest approach (n-gram models) and their limitations
3. **Session 1.3**: Introduces neural representations as a solution to n-gram limitations
4. **Session 1.4**: Examines how neural language models are trained and make predictions
5. **Session 1.5**: Investigates advanced embedding techniques and bridges to modern approaches

Each session builds directly on concepts from previous sessions, creating a foundation for understanding modern language models in Module 2.

## Visualization Tools

Throughout this module, you'll explore several interactive tools to visualize language model concepts:

- **TensorFlow Embedding Projector**: https://projector.tensorflow.org/ - Explore word vectors in 3D space
- **TensorFlow Playground**: https://playground.tensorflow.org/ - Experiment with neural networks
- **Interactive Word2Vec**: https://ronxin.github.io/wevi/ - Visualize the Word2Vec training process
- **The Illustrated Word2Vec**: https://jalammar.github.io/illustrated-word2vec/ - Visual explanations of embedding concepts

## Key Research Papers

This module references several foundational papers in language modeling:

- Bengio, Y., et al. (2003). "A Neural Probabilistic Language Model." Journal of Machine Learning Research, 3, 1137-1155. https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf
- Mikolov, T., et al. (2013). "Efficient Estimation of Word Representations in Vector Space." ICLR Workshop. https://arxiv.org/abs/1301.3781
- Mikolov, T., et al. (2013). "Distributed Representations of Words and Phrases and their Compositionality." NeurIPS.
- Pennington, J., et al. (2014). "GloVe: Global Vectors for Word Representation." EMNLP. https://nlp.stanford.edu/pubs/glove.pdf

These papers established the foundations upon which modern language models are built.

## Connection to Module 2

Module 1 establishes the foundational concepts of word representation and prediction. In Module 2, we'll build on these concepts to explore the transformer architecture that powers modern large language models, with a focus on how attention mechanisms provide contextual understanding and how supervised learning enables instruction following capabilities.
