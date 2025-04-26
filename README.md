# LLM Fundamentals: A Progressive Learning Series

This repository contains materials for a flipped classroom discussion series on Large Language Models (LLMs), designed for non-CS/AI students, researchers, and professors. The goal is to build a fundamental understanding of LLMs through guided exploration and structured discussions.

## What You'll Learn

By engaging with this learning series, you will:
- Understand how language models work from first principles
- Experience the evolution of language modeling techniques hands-on
- Develop a conceptual framework for understanding modern LLMs
- Build practical skills to interact with, evaluate, and apply LLMs
- Gain insight into the capabilities and limitations of AI language systems

Unlike traditional courses that start with technical jargon and mathematical complexity, this series begins with intuitive concepts and progressively introduces more sophisticated ideas as your understanding develops.

## Course Philosophy

This series takes a unique approach:
- **Principle-focused**: Understanding the core concepts behind LLM behavior without diving into technical details
- **Progressive learning**: Questions build systematically on previous concepts
- **Flipped classroom**: Self-directed exploration before group discussions
- **Accessible**: Designed specifically for those without CS/AI backgrounds

## Learning Structure

This course follows a structured learning progression designed to build understanding systematically:

### Overall Flow

1. Progress through **modules** in sequential order (Module 1 → Module 2 → Module 3)
2. Within each module, complete **sessions** in numerical order (Session 1.1 → Session 1.2 → etc.)
3. Each session follows a consistent three-part structure:
   
### Session Structure

1. **Pre-prompt Phase** ([pre-prompt.md](./pre-prompt.md))
   - Sets the learning framework for self-directed exploration
   - Defines student responsibilities and evaluation criteria
   - Establishes knowledge scaffolding approach
   - **Must be loaded first** before beginning any session

2. **Session Prompt Phase** (e.g., `module-1/s1.1-prompt.md`)
   - Contains the primary question and learning activities for the session
   - Provides step-by-step exploration paths
   - Includes hands-on exercises, discussion prompts, and checkpoints
   - Builds on concepts from previous sessions

3. **Post-prompt Phase** ([post-prompt.md](./post-prompt.md))
   - Evaluates learning progress across five dimensions
   - Identifies strengths and areas for improvement
   - Provides scores and specific examples from the conversation
   - Suggests next steps for continued learning

### Learning Process

1. Begin by loading the pre-prompt to understand the framework
2. Select the appropriate session prompt based on your progress
3. Work through session activities sequentially
4. Complete the post-prompt evaluation before moving to the next session
5. Connect concepts across sessions to build comprehensive understanding

## Module Overview

### Module 1: Foundations of Word Prediction and Embeddings
This module introduces the core concepts of language modeling through the lens of next-word prediction, starting with simple n-gram models and progressing to neural word embeddings.

**Key Concepts:**
- Next-token prediction as the foundational mechanism
- N-gram models and their limitations
- Supervised learning approaches (Bengio's neural language model)
- Unsupervised learning with Word2Vec
- Tokens vs. words in language processing
- Embeddings and their role in representing meaning

### Module 2: Transformer Architecture and LLM Training
This module examines the transformer architecture that powers modern LLMs, focusing on how these models are pre-trained and fine-tuned to follow instructions.

**Key Concepts:**
- Attention mechanisms and self-attention
- Feed-forward networks as computational engines
- Transformer architecture components
- Pre-training objectives and techniques
- Instruction following and prompt engineering
- Scaling properties of transformer models

### Module 3: Reasoning and Alignment in Large Models
This module explores advanced capabilities of modern LLMs, particularly their reasoning abilities and how they're aligned with human values and intentions.

**Key Concepts:**
- Fundamentals of Reinforcement Learning
- Reinforcement Learning from Human Feedback (RLHF)
- Value alignment techniques
- Policy gradient methods for improving reasoning
- Chain-of-thought and step-by-step reasoning
- Test-time computation and dynamic reasoning strategies

## Getting Started

### Preparation
1. Clone this repository to access all learning materials
2. Review the README to understand the course structure and philosophy
3. Familiarize yourself with the evaluation framework

### First Session
1. Start with Module 1, Session 1.1
2. Follow this sequence for each session:
   ```
   # First, load the pre-prompt
   1. Open and review pre-prompt.md
   
   # Next, load the session-specific prompt
   2. Open module-1/s1.1-prompt.md
   
   # Complete all activities in the session prompt
   3. Work through each part sequentially
   
   # Finally, evaluate your learning
   4. Open post-prompt.md for assessment
   ```

### Materials
Each module contains:
- README with learning objectives
- Session prompt files with guided activities
- Code templates and examples where applicable
- Suggested resources and references

### Tools
- Access to an LLM (preferably one that supports conversational interactions)
- Jupyter Notebook or similar environment for coding exercises
- Note-taking system to track your learning progression

## Evaluation Framework

Student understanding is evaluated across five dimensions:
1. Question Decomposition
2. Critical Thinking
3. Connection-Making
4. Conceptual Understanding
5. Reflection Quality

## Future Improvements

### Streamlined Session Loading
The current learning process requires users to manually load multiple files (pre-prompt, session prompt, post-prompt) in the correct sequence, which can be cumbersome. We're looking to improve this experience with:

- **Automated Session Manager**: A tool that would load all prerequisite knowledge points when starting a new session
- **Consolidated Prompt Files**: Single files that include all required context for each session
- **Progress Tracking**: A system to maintain student progress through the curriculum

If you're interested in contributing to these improvements, please see the Contributing section below or open an issue to discuss implementation approaches.

## Contributing

This is an educational project designed to evolve with our understanding of LLMs. Contributions, suggestions, and feedback are welcome.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-improvement`)
3. Commit your changes (`git commit -am 'Add some amazing improvement'`)
4. Push to the branch (`git push origin feature/amazing-improvement`)
5. Create a new Pull Request

### Types of Contributions Welcome
- Additional learning sessions
- Improvements to existing content
- Clarifications or corrections
- Additional code examples
- Visual aids and diagrams
- References to relevant papers and resources

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Acknowledgments

- Contributors and reviewers who have helped shape this educational series
- The research community advancing our understanding of large language models
- Students whose questions and feedback continue to improve these materials
