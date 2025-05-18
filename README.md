# LLM4LLM: A Progressive Learning Series

This repository contains materials for a flipped classroom discussion series on Large Language Models (LLMs), designed for non-CS/AI students, researchers, and professors. The goal is to build a fundamental understanding of LLMs through guided exploration and structured discussions.

## Why LLM4LLM?

Large Language Models have evolved at a breathtaking pace, making it challenging for educators and learners to keep up. This project offers a direct path to understanding these complex systems without getting lost in technical minutiae.

The content is structured in three tiers:
- **Core Concepts**: Explained through analogies and visualizations for everyone
- **Hands-On Implementation**: Practical code examples for CS students
- **Advanced Theory**: Mathematical foundations for those interested in deeper understanding

Learners can engage with whichever tier matches their background and interests, diving deeper in areas they find most relevant.

## The Science Behind the Series

This curriculum is structured around three fundamental principles that parallel both machine learning development and human cognition:

1. **Information as Distributed Representation**: Knowledge exists not as discrete facts but as distributed patterns across neural networks. Module 1 explores how information is encoded in these representations.

2. **Attention and Pattern Retrieval**: Learning involves developing mechanisms to identify relevant patterns within vast inputs. Module 2 examines how models sift through potentially very long inputs to find the relevant "keys" to retrieve stored patterns.

3. **Goal-Directed Learning**: Beyond simple imitation, true learning is driven by rewards oriented toward specific goals. Module 3 investigates how reinforcement mechanisms guide models toward aligned behaviors.

These principles not only explain how modern LLMs function but also reflect fundamental aspects of human cognition, creating a bridge between artificial and natural intelligence.

## The Meta-Experiment: LLMs Explaining Themselves

This curriculum represents a recursive experiment: using LLMs to explain their own inner workings. As these models become more capable, the teaching materials can potentially improve in tandem - from creating more effective visualizations to incorporating new research insights about LLM mechanisms.

This creates a self-reflexive learning system that may evolve alongside the technology it teaches. See [self-evolve.md](./self-evolve.md) for our experimental prompt that guides LLMs in analyzing and enhancing these materials.

## Recommended Learning Approach

### Learning Paths

You can follow either of these learning paths:

1. **Standard Sequential Approach**:
   - Progress through **modules** in sequential order (Module 1 → Module 2 → Module 3)
   - Within each module, complete **sessions** in numerical order (Session 1.1 → Session 1.2 → etc.)

2. **Philosophical Bookend Approach** (Recommended):
   - Begin with [Session 3.4: Philosophical Perspectives on AI Understanding](./module-3/s3.4-prompt.md) (First Pass only)
   - Then progress through the technical curriculum in order (Module 1 → Module 2 → Module 3, Sessions 3.1-3.3)
   - Finally, return to Session 3.4 for the Second Pass reflection
   - This approach allows you to compare your before-and-after perspectives on fundamental AI questions

Choose the approach that best suits your learning style. The philosophical bookend approach provides a powerful frame of reference by capturing your initial intuitions and then revealing how technical knowledge transforms your understanding.

### Session Management

Each learning session is designed as a single learning unit that you can work through at your own pace. One of the advantages of learning with generative AI is the ability to save your progress and return to continue exactly where you left off.

#### Starting a New Session
1. Begin with the pre-prompt to establish the learning framework
2. Load the appropriate session prompt (e.g., module-1/s1.1-prompt.md)
3. Engage with the content through interactive dialogue

#### Continuing a Session
If you need to pause and resume a session:
1. Return to your previous conversation where you were working on the session
2. You can simply continue where you left off
3. If needed, you can navigate to specific Knowledge Points (KPs)
   - Example: "I'd like to continue with Knowledge Point 3"
   - Or: "Let's review Knowledge Point 2 before moving on"

#### Navigating Between Knowledge Points
Within a session, you can freely navigate between Knowledge Points (KPs):
- Ask "What Knowledge Points are in this session?" to get an overview
- Say "Go to Knowledge Point X" to jump to a specific KP
- Say "Review Knowledge Point X" to revisit a previously completed KP
- Ask "What's my current progress?" to see which KPs you've completed
- Request a summary of previously covered concepts
- Ask clarifying questions about material from earlier in the session

#### Completing a Session
When you finish a session:
1. Load the post-prompt for evaluation
2. Review your learning assessment before moving to the next session
3. Begin the next session in a new conversation

This approach offers several benefits:
- Creates a searchable archive of your learning journey
- Makes it easy to continue where you left off
- Allows focused exploration of specific concepts
- Ensures each session can be completed at your own pace

### Session Structure

Each session follows a consistent three-part structure:

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

### Navigating Content Tiers

Use these commands to navigate between content tiers:
- Say "core concepts" to focus on fundamental ideas accessible to everyone
- Say "implementation" to explore hands-on code examples (for CS students)
- Say "theory" to dive into mathematical foundations and advanced concepts
- Say "all tiers" to see content from all three tiers for the current knowledge point

## Three-Tier Learning Structure

This curriculum accommodates learners with different backgrounds through three tiers of content:

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

## What You'll Learn

By engaging with this learning series, you will:
- Understand how language models work from first principles
- Experience the evolution of language modeling techniques hands-on
- Develop a conceptual framework for understanding modern LLMs
- Build practical skills to interact with, evaluate, and apply LLMs
- Gain insight into the capabilities and limitations of AI language systems

Unlike traditional courses that start with technical jargon and mathematical complexity, this series begins with intuitive concepts and progressively introduces more sophisticated ideas as your understanding develops.

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
- Philosophical perspectives on AI understanding

## Getting Started

### Preparation
1. Clone this repository to access all learning materials
2. Review the README to understand the course structure and philosophy
3. Familiarize yourself with the evaluation framework

### First Session
1. Start with Module 1, Session 1.1 (or consider beginning with the philosophical questions in Session 3.4 as suggested in the Philosophical Bookend Approach)
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

## Multi-language Learning

One unique feature of LLM4LLM is the ability to learn about language models in your preferred language. Simply type a request in the target language to have the content delivered in that language:

* To learn in Chinese: type "请用中文教授这个课程"
* To learn in German: type "Bitte unterrichte diesen Kurs auf Deutsch"
* To learn in Greek: type "Παρακαλώ διδάξτε αυτό το μάθημα στα Ελληνικά"
* To learn in Spanish: type "Por favor enseña este curso en español"
* To learn in French: type "Veuillez enseigner ce cours en français"

The LLM will automatically adapt and provide all explanations, examples, and interactions in your requested language, making this learning experience accessible across language barriers.
