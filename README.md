# LLM4LLM: A Progressive Learning Series

This repository contains materials for a flipped classroom discussion series on Large Language Models (LLMs), designed for non-CS/AI students, researchers, and professors. The goal is to build a fundamental understanding of LLMs through guided exploration and structured discussions.

## Why LLM4LLM?

Large Language Models have evolved at a breathtaking pace, making it challenging for educators and learners to keep up. This project offers a "fast track" approach - a direct, efficient path to understanding these complex systems without getting lost in technical minutiae.

LLM4LLM is also a meta-experiment: using LLMs to explain themselves. As these models become more capable, the teaching materials can potentially improve in tandem. While the current modules and knowledge scaffolding are designed manually based on our understanding of how LLMs can be explained effectively, we're exploring how much of this educational process could eventually be handled by the LLMs themselves. This creates a fascinating recursive learning system that may evolve alongside the technology it teaches. We've started designing a self-evolution framework to enable LLMs to review and suggest improvements to this curriculum. See [self-evolve.md](./self-evolve.md) for our experimental prompt that guides LLMs in analyzing and enhancing these materials.

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
- **Tiered content**: Materials cater to different backgrounds and technical abilities

## Interactive Learning Approach

This course is designed to be interactive and responsive to your curiosity. You're encouraged to:
- Ask questions whenever you encounter unfamiliar concepts
- Request deeper explanations of code examples
- Inquire about historical context or alternative approaches
- Challenge assumptions and seek clarification

The AI assistant is prepared to explain technical concepts (like PyTorch code), provide historical context, and discuss alternative approaches based on your interests and questions. Don't hesitate to ask for clarification about anything that seems unfamiliar or confusing.

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

1. Begin by opening your favorite generative AI chatbot (tested with ChatGPT, Claude, Gemini, DeepSeek, and others)
2. Copy and paste the pre-prompt into the chat to establish the learning framework
3. Copy and paste the appropriate session prompt (e.g., module-1/s1.1-prompt.md) into the chat
4. Work through the activities as guided by the LLM
5. Copy and paste the post-prompt evaluation into the chat before moving to the next session
6. Connect concepts across sessions to build comprehensive understanding

### Content for Different Backgrounds

Starting from Module 2, the content is structured in three tiers to accommodate different backgrounds:

- **Core Concepts (For Everyone)**: Accessible explanations using analogies and visual references
- **Hands-On Implementation (For CS Students)**: Practical code examples and implementations
- **Advanced Theory (For the Curious)**: Deeper mathematical foundations and connections

You can engage with whichever level best matches your background and interests. Feel free to ask the AI to explain code examples or provide more context for technical concepts.

### Multi-language Learning

One unique feature of LLM4LLM is the ability to learn about language models in your preferred language. Simply type a request in the target language to have the content delivered in that language:

* To learn in Chinese: type "请用中文教授这个课程"
* To learn in German: type "Bitte unterrichte diesen Kurs auf Deutsch"
* To learn in Greek: type "Παρακαλώ διδάξτε αυτό το μάθημα στα Ελληνικά"
* To learn in Spanish: type "Por favor enseña este curso en español"
* To learn in French: type "Veuillez enseigner ce cours en français"

The LLM will automatically adapt and provide all explanations, examples, and interactions in your requested language, making this learning experience accessible across language barriers.

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
- The alignment problem and why prediction isn't enough
- Reinforcement Learning from Human Feedback (RLHF)
- Value alignment techniques
- Chain-of-thought and step-by-step reasoning
- Test-time computation and dynamic reasoning strategies
- Balancing capabilities with alignment

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

## The Learning Journey

This curriculum guides you through a progressive journey:

**Module 1** establishes the fundamental mechanisms behind language modeling, showing how simple statistical techniques evolved into neural representations.

**Module 2** introduces the transformer architecture that revolutionized language processing, explaining how attention mechanisms and parallel processing unlock new capabilities.

**Module 3** explores how modern language models move beyond pattern matching to reasoning and alignment with human values, revealing the current frontiers of development.

Throughout this journey, you'll see how each advancement builds upon previous concepts and addresses specific limitations of earlier approaches.

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

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE](./LICENSE) file for details. This license allows for free use for research and educational purposes, but prohibits commercial use without permission.

## Acknowledgments

- Contributors and reviewers who have helped shape this educational series
- The research community advancing our understanding of large language models
- Students whose questions and feedback continue to improve these materials
