# | NLP | LLM | LangChain | Multi-stage Reasoning |

## Natural Language Processing (NLP) and Large Language Models (LLM) with LangChain and Building Multi-stage Reasoning Systems

![Learning](https://t3.ftcdn.net/jpg/06/14/01/52/360_F_614015247_EWZHvC6AAOsaIOepakhyJvMqUu5tpLfY.jpg)


# <b>1 <span style='color:#78D118'>|</span> Overview</b>

In this notebook we're going to create AI systems:
- Named `CommentatorMoodModeratorAI` will be a prototype AI self-commenting-and-moderating tool that will create new reaction comments to a piece of text with one LLM and use another LLM to critique those comments and flag them if they are negative. To build this we will walk through the steps needed to construct prompts and chains, as well as multiple LLM Chains that take multiple inputs, both from the previous LLM and external. 

## Learning Objectives

By the end of this notebook, you will be able to:
1. Build prompt template and create new prompts with different inputs
2. Create basic LLM chains to connect prompts and LLMs.
3. Construct sequential chains of multiple `LLMChains` to perform multi-stage reasoning analysis. 
4. Use langchain agents to build semi-automated systems with an LLM-centric agent.


<img src="https://deepsense.ai/wp-content/uploads/2023/10/LangChain-announces-partnership-with-deepsense.jpeg" alt="Learning" width="50%">



