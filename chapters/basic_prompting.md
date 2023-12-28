# Basic Prompting: Writing Effective Prompts

## Contents

- Anatomy of a Good Prompt
- Best Practices for Writing Efficient Prompts
- How not to write a prompt? Some wrong examples
- Prompting Techniques
- Zero-shot Prompting
- Few-Shot Prompting
- Chain-of-Thought (CoT) Prompting

## Anatomy of a Good Prompt

- Instruction
  - Task to be performed
- Context
  - Contextual information about the task to drive the model towards better results
  - May contain some demonstrations
- Input Data
  - Input for the current question
- Output Indicator
  - Type of response desired from the model

**Note:** Not all the components are required for a prompt and the format depends on the task

![anatomy](../static/anatomy.jpg)

## Best Practices for Writing Efficient Prompts

- Giving simple and specific tasks
- Try to give examples whenever possible
- Using a clear separator like "###" to separate the instruction and context

![best_practices](../static/bestPractices.jpg)

## How not to write a prompt?

- Avoid confusing prompts without examples
- Avoid giving misleading examples

![How Not ](../static/howNot1.png)

![How Not ](../static/howNot2.png)
