---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1> Are you burning money on your language AI feature?</h1>

## TLDR


[60-80% of AI projects are failing](https://www.forbes.com/sites/cognitiveworld/2022/08/14/the-one-practice-that-is-separating-the-ai-successes-from-the-failures/?sh=2db4b23117cb).

This essay is aimed at CTOs developing an AI feature aimed at prediction in a niche
business language domain, which requires special care. 

- Did you start with a living document of the mental language model of your customer?
- Did you start by putting a cheap prototype in front of your customer?

The sooner your can map your customer's language mental model to the data, the
sooner you can make a prototype. The sooner you make a prototype, the faster you
can get customer feedback. The sooner you get customer feedback the sooner you
can refine.

Crunching the knowledge of experts in a niche language domain is much more
ambiguous than crunching numbers. Its requires [cognitive
empathy](https://en.wikipedia.org/wiki/Empathy#Cognitive_empathy).


A few months ago, Sam Altman (CEO of OpenAI) said he expects that the next
unicorns will focus on fine-tuning models for various verticals
([interview](https://www.youtube.com/watch?v=WHoWGNQRXb0)). On March 1, [OpenAI
announced](https://openai.com/blog/introducing-chatgpt-and-whisper-apis) the
release of API access to ChatGPT, a hosted language model. The cost to develop a
language based prediction service has dropped by orders of magnitude, if you
restructure your development effort. 


## Why Gemba matters in niche language AI?

A key principle in Toyota's Lean manufacturing is Go See or Gemba, which means
"go see with your own eyes, rather than sit behind desks or believe that the
truth can be learned only from reports or numbers". Below is the rationale of
why Gemba is relevant for developing niche language AI? 

- You can't improve, if you can't accurately track performance. 
- You can't track performance, if you don't have a valid test set of examples. 
- Your test set of examples continually become invalid as you refine your model of your expert's domain language.
- You can't refine your model without your customer's feedback.

In summary, you Go See be getting a prototype in front of the customer (or expert), watch her reaction, and then iterate.

## The CTO's four point pre-flight safety check in making a prototype

1. [Domain model](https://martinfowler.com/bliki/DomainDrivenDesign.html): Do you continuously update a high-level design document (Rosetta Stone) as you reach consensus on conflicts in translating the mental model of your subject matter experts?
2. **Classifier scope:** Do you continuously narrow the scope of your classifier as you find edge cases that are too expensive to solve using AI, at the moment, or can be solved with cheap expert rules instead?
3. **Human labeling (annotation):** Prior to investing in a human labeling service, did you experiment with GPT chain prompting, vector indexing, and fine-tuning with programmatic labeling? 
4. **Hosting:** Prior to investing in rolling your own language model, did you do a cost benefit analysis on using a hosted language model or a hybrid approach instead? 


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

## About

- [Boris Dev](https://www.linkedin.com/in/boris-dev/)
- [Shawn Larson](https://www.linkedin.com/in/shawn-larson-ai/)
- [Robert McKee](https://www.linkedin.com/in/robertcmckee/)

Contact: contact@tunegpt.ai
