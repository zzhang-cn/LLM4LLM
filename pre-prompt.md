# LEARNING SESSION FRAMEWORK

<div style="position: relative; padding: 15px; background-color: #f6f8fa; border-radius: 6px; margin-bottom: 16px;">
  <button onclick="copyToClipboard()" style="position: absolute; top: 10px; right: 10px; padding: 6px 12px; background-color: #0366d6; color: white; border: none; border-radius: 3px; cursor: pointer;">Copy to Clipboard</button>
  <div id="copyContent">
  
## Purpose
This framework guides your self-directed exploration of Large Language Models (LLMs). Each session contains key knowledge points designed to be learned sequentially, building a foundation for understanding more complex concepts.

## How to Approach Each Session

### Student Role
As a learner, you should:
- Begin by stating which module and session you're exploring
- Try to decompose complex questions into manageable parts
- Think critically before asking for information directly
- Attempt to connect new concepts to previously learned material
- Summarize your understanding at key points
- Follow the scaffolding sequence rather than jumping ahead

While you can simply ask for explanations of concepts, you'll gain deeper understanding by:
- Formulating your own hypotheses before seeking answers
- Drawing analogies to concepts you already understand
- Asking clarifying questions when explanations aren't clear
- Reflecting on what you've learned before moving to the next concept

### Knowledge Scaffolding
Each session presents concepts in a deliberate sequence. Try to:
1. Master each concept before moving to the next
2. Revisit earlier concepts if you encounter confusion
3. Make explicit connections between related concepts
4. Test your understanding through examples or applications

### Session Evaluation
Your learning process will be evaluated across five dimensions:
1. **Question Decomposition**: How effectively you break down complex questions
2. **Critical Thinking**: Your attempts to reason through concepts before asking for explanations
3. **Connection-Making**: How well you connect new concepts to previously learned material
4. **Conceptual Understanding**: Demonstrating understanding beyond surface-level facts
5. **Reflection Quality**: The thoughtfulness of your summaries and reflections

## Getting Started
Begin by identifying which module and session you're exploring, then work through the concepts sequentially, building your understanding step by step.
  </div>
</div>

<script>
function copyToClipboard() {
  const text = document.getElementById('copyContent').innerText;
  navigator.clipboard.writeText(text).then(() => {
    const button = document.querySelector('button');
    const originalText = button.innerText;
    button.innerText = 'Copied!';
    setTimeout(() => {
      button.innerText = originalText;
    }, 2000);
  }).catch(err => {
    console.error('Failed to copy: ', err);
  });
}
</script>
