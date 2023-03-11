---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Are you burning money and getting no where with your AI?</h1>

[60-80% of AI projects are failing](https://www.forbes.com/sites/cognitiveworld/2022/08/14/the-one-practice-that-is-separating-the-ai-successes-from-the-failures/?sh=2db4b23117cb).

A root cause of language AI project failure is that no one owns getting down and
dirty with the data. In other words, someone needs to understand and document
the nuanced concepts behind the language your are trying to predict. Eric Evan's
in his book Domain Driven Design coined a term for this, **Knowledge Crunching**.

**The four point pre-flight safety check for your CTO**

1. Knowledge Crunching: Do you continuously update a high-level design document (Rosetta Stone) as you reach consensus on translating the mental model of your subject matter experts?
2. Scope: Do you continuously narrow the scope when you find edge cases that are too expensive to solve using AI, at the moment, or can be solved with cheap expert rules?
3. Labeling as last resort: Prior to investing in a human labeling service, did you experiment with GPT chain prompting, vector indexing, and fine-tuning with programmatic labeling? 
4. Custom model as last resort: Prior to investing in rolling your own language model, did you do a cost benefit analysis on using a hosted language model or a hybrid approach? 


If your AI feature is based on a text classification model, before investing
lots of money checkout some shortcuts.

- Can you start giving your customer value and getting their feedback simply with expert rules instead of AI?
- Can you start with a hosted service such as GPT to avoid the costs of MLOps and neural network experts?

**Table: Mapping different types of language prediction models to costs**

| Prediction model type                         | Knowledge crunching    | Labeling costs | MLOps costs | Neural Network R&D costs |
| --------------------------------------------- | ---------------------- | -------------- | ----------- | ------------------------ |
| expert rules                                  | $                      | None           | None        | None                     |
| GPT with prompt engineering                   | $                      | None           | None        | None                     |
| GPT with fine-tuning and programmtic labeling | $                      | $              | None        | None                     |
| GPT with fine-tuning and human labeling       | $                      | $$             | None        | None                     |
| GPT and roll your own model hybrid            | $                      | $$$            | $$$         | $$$                      |
| Roll your own model                           | $                      | $$$            | $$$         | $$$                      |

**What's changed?**

- On March 1, OpenAI announced the release of API access to ChatGPT.

**What's does this mean for your company?**

The cost to develop a language based prediction service has dropped by orders of magnitude. 

- What information gathering toil is suddenly feasible for you to automate?
- How can fine-tuning GPT jump start your current ML language classifier project?

**We can do the following for you.**

- We will make you a language classifier prototype at a fraction of the cost of your expenditures to date.

## About

- [Boris Dev](https://www.linkedin.com/in/boris-dev/)
- [Shawn Larson](https://www.linkedin.com/in/shawn-larson-ai/)
- [Robert McKee](https://www.linkedin.com/in/robertcmckee/)

Contact: contact@tunegpt.ai
