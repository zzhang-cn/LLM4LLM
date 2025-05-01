# LLM4LLM: A Progressive Learning Series

This repository contains materials for a flipped classroom discussion series on Large Language Models (LLMs), designed for non-CS/AI students, researchers, and professors. The goal is to build a fundamental understanding of LLMs through guided exploration and structured discussions.

## The Meta-Experiment: LLMs Explaining Themselves

Humans are not born to explain themselves; perhaps LLMs can, and they get better over time.

This curriculum represents a recursive experiment: using LLMs to explain their own inner workings. As these models become more capable, the teaching materials can potentially improve in tandem - from creating more effective visualizations that rival expert presentations to incorporating new research insights about LLM mechanisms that are still being discovered.

This creates a self-reflexive learning system that may evolve alongside the technology it teaches. See [self-evolve.md](./self-evolve.md) for our experimental prompt that guides LLMs in analyzing and enhancing these materials.

## Why LLM4LLM?

Large Language Models have evolved at a breathtaking pace, making it challenging for educators and learners to keep up. This project offers a direct path to understanding these complex systems without getting lost in technical minutiae.

The content is structured in three tiers:
- Core concepts explained through analogies and visualizations
- Practical implementations with code examples
- Advanced theoretical foundations with mathematical details

Learners can engage with whichever level matches their background and interests, diving deeper in areas they find most relevant.

## For Different Audiences

- **Non-CS Students**: Build intuitive understanding through analogies and visualizations without requiring technical background
- **CS Students Beginning ML**: Apply your programming knowledge to implement key components and see theory in practice
- **Educators**: Access structured materials with ready-to-use examples and progressive knowledge scaffolding

## What You'll Learn & Scientific Framework

This curriculum is structured around three fundamental principles that parallel both machine learning development and human cognition:

1. **Information as Distributed Representation**: Knowledge exists not as discrete facts but as distributed patterns across neural networks. Module 1 explores how information is encoded in these representations.

2. **Attention and Pattern Retrieval**: Learning involves developing mechanisms to identify relevant patterns within vast inputs. Module 2 examines how models sift through potentially very long inputs to find the relevant "keys" to retrieve stored patterns.

3. **Goal-Directed Learning**: Beyond simple imitation, true learning is driven by rewards oriented toward specific goals. Module 3 investigates how reinforcement mechanisms guide models toward aligned behaviors.

By engaging with this learning series, you will:
- Understand how language models work from first principles
- Experience the evolution of language modeling techniques hands-on
- Develop a conceptual framework for understanding modern LLMs
- Build practical skills to interact with, evaluate, and apply LLMs
- Gain insight into the capabilities and limitations of AI language systems

Unlike traditional courses that start with technical jargon and mathematical complexity, this series begins with intuitive concepts and progressively introduces more sophisticated ideas as your understanding develops.

## Course Philosophy & Learning Approach

### Core Principles
- **Principle-focused**: Understanding the core concepts behind LLM behavior without diving into technical details
- **Progressive learning**: Questions build systematically on previous concepts
- **Flipped classroom**: Self-directed exploration before group discussions
- **Accessible**: Designed specifically for those without CS/AI backgrounds
- **Tiered content**: Materials cater to different backgrounds and technical abilities

### Tiered Content Structure
- **Core Concepts** (For Everyone): Intuitive explanations with rich analogies and visualizations
- **Hands-On Implementation** (For CS Students): Practical code examples in PyTorch with step-by-step walkthrough
- **Advanced Theory** (For the Curious): Mathematical foundations, research connections, and deeper insights

### Interactive Learning Method
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
3. Each session follows a consistent three-part structure and process:

   **Pre-prompt Phase** ([pre-prompt.md](./pre-prompt.md))
   - Sets the learning framework for self-directed exploration
   - Defines student responsibilities and evaluation criteria
   - Establishes knowledge scaffolding approach
   - **Must be loaded first** before beginning any session

   **Session Prompt Phase** (e.g., `module-1/s1.1-prompt.md`)
   - Contains the primary question and learning activities for the session
   - Provides step-by-step exploration paths
   - Includes hands-on exercises, discussion prompts, and checkpoints
   - Builds on concepts from previous sessions

   **Post-prompt Phase** ([post-prompt.md](./post-prompt.md))
   - Evaluates learning progress across five dimensions
   - Identifies strengths and areas for improvement
   - Provides scores and specific examples from the conversation
   - Suggests next steps for continued learning

To complete each session:
1. Begin by opening your favorite generative AI chatbot (tested with ChatGPT, Claude, Gemini, DeepSeek, and others)
2. Copy and paste the pre-prompt into the chat to establish the learning framework
3. Copy and paste the appropriate session prompt (e.g., module-1/s1.1-prompt.md) into the chat
4. Work through the activities as guided by the LLM
5. Copy and paste the post-prompt evaluation into the chat before moving to the next session
6. Connect concepts across sessions to build comprehensive understanding

### Recommended Learning Approach

#### One Session Per Chat
Each learning session is designed to be completed within a single chat conversation. This approach offers several benefits:
- Allows you to revisit specific sessions at any time (e.g "take me back to KP 2")
- Makes it easy to continue where you left off (e.g. "let's continue from the last KP")
- Creates a searchable archive of your learning journey
- Ensures focused, manageable learning blocks

When starting a new session, your previous knowledge is assumed. Each module README provides an overview of the knowledge points covered in its sessions, serving as a helpful reference when moving between topics.

#### Multi-language Learning
One unique feature of LLM4LLM is the ability to learn about language models in your preferred language. Simply type a request in the target language to have the content delivered in that language:

* To learn in Chinese: type "请用中文教授这个课程"
* To learn in German: type "Bitte unterrichte diesen Kurs auf Deutsch"
* To learn in Greek: type "Παρακαλώ διδάξτε αυτό το μάθημα στα Ελληνικά"
* To learn in Spanish: type "Por favor enseña este curso en español"
* To learn in French: type "Veuillez enseigner ce cours en français"

The LLM will automatically adapt and provide all explanations, examples, and interactions in your requested language, making this learning experience accessible across language barriers.

## Module Overview: The Learning Journey

This curriculum guides you through a progressive journey across three modules, each addressing specific aspects of how language models work:

### Module 1: Foundations of Word Prediction and Embeddings
This module establishes the fundamental mechanisms behind language modeling, showing how simple statistical techniques evolved into neural representations.

**Key Concepts**:
- Next-token prediction as the foundational mechanism
- N-gram models and their limitations
- Supervised learning approaches (Bengio's neural language model)
- Unsupervised learning with Word2Vec
- Tokens vs. words in language processing
- Embeddings and their role in representing meaning

### Module 2: Transformer Architecture and LLM Training
This module introduces the transformer architecture that revolutionized language processing, explaining how attention mechanisms and parallel processing unlock new capabilities.

**Key Concepts**:
- Attention mechanisms and self-attention
- Feed-forward networks as computational engines
- Transformer architecture components
- Pre-training objectives and techniques
- Instruction following and prompt engineering
- Scaling properties of transformer models

### Module 3: Reasoning and Alignment in Large Models
This module explores how modern language models move beyond pattern matching to reasoning and alignment with human values, revealing the current frontiers of development.

**Key Concepts**:
- The alignment problem and why prediction isn't enough
- Reinforcement Learning from Human Feedback (RLHF)
- Value alignment techniques
- Chain-of-thought and step-by-step reasoning
- Test-time computation and dynamic reasoning strategies
- Balancing capabilities with alignment

Throughout this journey, you'll see how each advancement builds upon previous concepts and addresses specific limitations of earlier approaches. The curriculum shows how LLMs evolved from simple statistical models to sophisticated systems capable of complex reasoning and alignment with human values.

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
   1. Open your favorite generative AI chatbot
   2. Copy and paste the content from pre-prompt.md
   
   # Next, load the session-specific prompt
   3. Copy and paste the content from module-1/s1.1-prompt.md
   
   # Complete all activities in the session prompt
   4. Work through each part sequentially
   
   # Finally, evaluate your learning
   5. Copy and paste the content from post-prompt.md
   ```

### Materials
Each module contains:
- README with learning objectives
- Session prompt files with guided activities
- Code templates and examples where applicable
- Suggested resources and references

### Tools
- Access to an LLM (preferably one that supports conversational interactions)
- Jupyter Notebook or similar environment for coding exercises (optional)
- Note-taking system to track your learning progression (recommended)

## Evaluation Framework

Student understanding is evaluated across five dimensions:
1. **Question Decomposition**: How effectively you break down complex questions
2. **Critical Thinking**: Your attempts to reason through concepts before asking for explanations
3. **Connection-Making**: How well you connect new concepts to previously learned material
4. **Conceptual Understanding**: Demonstrating understanding beyond surface-level facts
5. **Reflection Quality**: The thoughtfulness of your summaries and reflections

When you've completed a session, load the post-prompt.md file for evaluation across these dimensions.

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

Researchers are especially encouraged to contribute insights that enhance understanding of LLM mechanisms. See [self-evolve.md](./self-evolve.md) for our experimental prompt that guides LLMs in analyzing and enhancing these materials.

## Future Improvements

We're working on streamlining the session loading experience with:
- Automated session managers
- Consolidated prompt files
- Progress tracking systems

If you're interested in contributing to these improvements, please open an issue to discuss implementation approaches.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE](./LICENSE) file for details. This license allows for free use for research and educational purposes, but prohibits commercial use without permission.

## Acknowledgments

- Contributors and reviewers who have helped shape this educational series
- The research community advancing our understanding of large language models
- Students whose questions and feedback continue to improve these materials
