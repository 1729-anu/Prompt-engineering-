## Prompt Engineering

"Prompt engineering” refers to efforts to extract accurate, consistent, and fair outputs from large generative models, such text-to-image synthesizers or large language models (LLMs). LLMs are trained on large-scale bodies of text, so they encode a great deal of factual information about the world. But they’re trained to produce sequences of words that are probable in the general case — not accurate in the particular case.

What is a prompt?
- Text given to a pre-trained model for a prediction task

Components of Prompt
- Context
- Task (Instruction, question etc.)
- Image/Text
- Training samples 
- Generative Model

### Types of Prompt Engineering

1. Several types of prompt engineering include:
   1. Zero shot
   2. One shot and Few shot
   3. Chain of thought
4. Advanced concepts on prompt engineering
5. Adversarial Prompt engineering

#### 1. Zero Shot:
Zero-shot prompting enables a model to make predictions about previously unseen data without the need for any additional training. 

This is in contrast to traditional machine learning techniques, which require a large amount of labeled training data to make accurate predictions. 

In the context of prompt engineering, zero-shot learning can be used to generate natural language text without the need for explicit programming or pre-defined templates. 


#### 2. One Shot and Few Shot Prompting:

One-shot prompting is used to generate natural language text with a limited amount of input data such as a single example or template. 

One-shot prompting can be combined with other natural language processing techniques like dialogue management and context modeling to create more sophisticated and effective text generation systems. 

Few-shot prompting is a technique where the model is given a small number of examples, typically between two and five, in order to quickly adapt to new examples of previously seen objects. 

Few-shot learning can be used in the context of prompt engineering, to create natural language text with a limited amount of input data. Although it requires less data, this technique can allow for the creation of more versatile and adaptive text generation models.

By using advanced techniques such as few-shot prompting, it is possible to create natural language generation models that are more flexible, adaptable, and engaging for human users.

### Chain of thought prompting

Chain-of-thought (CoT) prompting improves the reasoning ability of LLMs by prompting them to generate a series of intermediate steps that lead to the final answer of a multi-step problem.


In this lab, we are going to uncover how to setup SageMaker Studio for prompt engineering utility and use cases with different types of prompt engineering techniques.
