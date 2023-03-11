---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1> Are you burning money on your language AI feature?</h1>

## TLDR

[60-80% of AI projects are failing](https://www.forbes.com/sites/cognitiveworld/2022/08/14/the-one-practice-that-is-separating-the-ai-successes-from-the-failures/?sh=2db4b23117cb).


1. The sooner your can map your customer's language mental model to the data, the sooner you can make a prototype.
2. The sooner you make a prototype, the faster you can get feedback and progress.


## Gemba

- You can't track your language feature's AI performance without a valid test set.
- You can't build a valid test set without translating the nuanced concepts behind your customer's mental language model.
- You can't validate your generalization of customer's mental language model without their feedback on your prototype's predictions.

A key principle in Toyota's Lean manufacturing is Go See or Gemba, which means
"go see with your own eyes, rather than sit behind desks or believe that the
truth can be learned only from reports or numbers". For your language AI feature
its means getting a prototype in front of customers and watching their reaction
to see if you are on the right track. 
Some one must get down and dirty with the data, and document the mental model of your customer (or subject matter expert). 
Eric Evan coined a term for this, Knowledge Crunching. 


## The CTO's four point pre-flight safety check in making a prototype

1. Knowledge Crunching: Do you continuously update a high-level design document (Rosetta Stone) as you reach consensus on translating the mental model of your subject matter experts?
2. Scope: Do you continuously narrow the scope when you find edge cases that are too expensive to solve using AI, at the moment, or can be solved with cheap expert rules?
3. Labeling as last resort: Prior to investing in a human labeling service, did you experiment with GPT chain prompting, vector indexing, and fine-tuning with programmatic labeling? 
4. Custom model as last resort: Prior to investing in rolling your own language model, did you do a cost benefit analysis on using a hosted language model or a hybrid approach? 


Before investing lots of money checkout some shortcuts.

- Can you start giving your customer value and getting their feedback simply with expert rules instead of AI?
- Can you start with a hosted service such as GPT to avoid the costs of MLOps and neural network experts?

## Table: Mapping different types of language prediction models to costs

| Prediction model type                         | Knowledge crunching    | Labeling costs | MLOps costs | Neural Network R&D costs |
| --------------------------------------------- | ---------------------- | -------------- | ----------- | ------------------------ |
| expert rules                                  | $                      | None           | None        | None                     |
| GPT with prompt engineering                   | $                      | None           | None        | None                     |
| GPT with fine-tuning w/ programmatic labeling | $                      | $              | None        | None                     |
| GPT with fine-tuning w/ human labeling        | $                      | $$$            | None        | None                     |
| GPT and roll your own model hybrid            | $                      | $$$            | $$$         | $$$                      |
| Roll your own model                           | $                      | $$$            | $$$         | $$$                      |

## What's new?

- On March 1, OpenAI announced the release of API access to ChatGPT, a hosted language model.
- The cost to develop a language based prediction service has dropped by orders of magnitude, if you restructure. 

## About

- [Boris Dev](https://www.linkedin.com/in/boris-dev/)
- [Shawn Larson](https://www.linkedin.com/in/shawn-larson-ai/)
- [Robert McKee](https://www.linkedin.com/in/robertcmckee/)

Contact: contact@tunegpt.ai
