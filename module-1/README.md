# Module 1: Foundations of Word Prediction and Embeddings

This module introduces the core concepts of language modeling through the lens of next-word prediction, which serves as the fundamental mechanism behind language models like the one you're interacting with now.

## Learning Objectives

By the end of this module, you should be able to:
- Understand how next-word prediction serves as the foundation for LLMs
- Experience how this simple concept enables complex capabilities like instruction following
- Build a simple n-gram predictor and understand its limitations
- Recognize why more sophisticated approaches like word embeddings are necessary
- Differentiate between supervised and unsupervised approaches to language modeling
- Understand how word embeddings capture semantic relationships

## Sessions

### [Session 1.1: Understanding Next-Word Prediction](./s1.1-prompt.md)
Explore how prediction serves as the foundational mechanism behind language models, and how this simple concept enables complex capabilities like answering questions and following instructions.

### [Session 1.2: Building Your First N-gram Predictor](./s1.2-prompt.md)
Experience firsthand the process of building a simple statistical language model, and discover through hands-on coding why more sophisticated approaches are needed.

### [Session 1.3: From N-grams to Neural Representations](./s1.3-prompt.md)
Discover how neural approaches can represent words as vectors in a continuous space, addressing fundamental limitations of discrete n-gram representations.

### [Session 1.4: Neural Language Model Prediction and Training](./s1.4-prompt.md)
Explore how neural language models make predictions and learn from data, understanding the complete architecture from input to prediction.

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
- **Limitations of simple models**: Why we need more sophisticated approaches

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
