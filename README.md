# Efficient-LLMAgent-Survey
_**We are currently writing a survey on Efficient LLM Agent Serving and welcome everyone to provide comments on the  list!**_

This repository maintains a curated list of papers related to Large Language Model Based Agents (LLM Agents), especially focusing on efficient serving methods for LLM Agents.

This paper list covers several main aspects of efficient serving methods for LLM Agents. 
Table of content:

- [Efficient-LLMAgent-Survey](#efficient-llmagent-survey)
  - [What is LLM Agent](#what-is-llm-agent)
  - [Efficient Serving LLM Agent](#efficient-serving-llm-agent)
    - [LLM Serving](#llm-serving)
    - [Planning](#planning)
    - [Tool and Action](#tool-and-action)
      - [Serverless](#serverless)
    - [Memory](#memory)
  - [Component Collaboration and Agent Framework](#component-collaboration-and-agent-framework)
  - [Device-Edge-Cloud Collaboration](#device-edge-cloud-collaboration)
  - [LLM and  Agent Framework](#llm-and--agent-framework)
    - [LLM Framework](#llm-framework)
    - [GenAI Develop Engine](#genai-develop-engine)
    - [Agent Framework](#agent-framework)
  - [Benchmark, Trace, and Dataset](#benchmark-trace-and-dataset)
  - [LLM and Agent on Mobile Platform](#llm-and-agent-on-mobile-platform)
  - [Survey Papers](#survey-papers)
  - [Others](#others)



## What is LLM Agent
- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)

## Efficient Serving LLM Agent

### LLM Serving
- [RelayAttention for Efficient Large Language Model Serving with Long System Prompts](https://arxiv.org/abs/2402.14808)
- [ALISA: Accelerating Large Language Model Inference via Sparsity-Aware KV Caching]
- [Splitwise: Efficient generative LLM inference using phase splitting](https://arxiv.org/abs/2311.18677)|ISCA'24
- [MECLA: Memory-Compute-Efficient LLM Accelerator with Scaling Sub-matrix Partition]
- [A Hardware Evaluation Framework for Large Language Model Inference](https://arxiv.org/abs/2312.03134)|ISCA'24
- [Efficient LLM Inference with Kcache](https://arxiv.org/abs/2404.18057)
- [HeteGen](https://arxiv.org/abs/2403.01164) HeteGen: Heterogeneous Parallel Inference for Large Language Models on Resource-Constrained Devices | MLSys'24
- [CacheGen: KV Cache Compression and Streaming for Fast Language Model Serving](https://arxiv.org/abs/2310.07240)|SIGCOMM '24
- [Chatterbox: Robust Transport for LLM Token Streaming under Unstable Network](https://arxiv.org/abs/2401.12961)
- [dLoRA: Dynamically Orchestrating Requests and Adapters for LoRA LLM Serving]| OSDI '24
- [NetLLM: Adapting Large Language Models for Networking] | SIGCOMM '24
- [DistLLM: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving]| OSDI '24
- [Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs](https://arxiv.org/abs/2310.01801)
- [Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems](https://arxiv.org/abs/2312.15234v1)
- [POLCA](https://www.microsoft.com/en-us/research/uploads/prodnew/2024/03/GPU_Power_ASPLOS_24.pdf)Characterizing Power Management Opportunities for LLMs in the Cloud | ASPLOS'24
- [ScaleLLM: Unlocking Llama2-13B LLM Inference on Consumer GPU RTX 4090, powered by FEDML Nexus AI](https://blog.fedml.ai/scalellm-unlocking-llama2-13b-llm-inference-on-consumer-gpu-rtx-4090-powered-by-fedml-nexus-ai/)
- [Efficient Interactive LLM Serving with Proxy Model-based Sequence Length Prediction](https://arxiv.org/abs/2404.08509v1)
- [SpotServe: Serving Generative Large Language Models on Preemptible Instances](https://arxiv.org/abs/2311.15566) | ASPLOS 2024
### Planning
- [PreAct](https://arxiv.org/abs/2402.11534)PreAct: Predicting Future in ReAct Enhances Agent's Planning Ability
- [An LLM Compiler for Parallel Function Calling](https://arxiv.org/abs/2312.04511)
- [Dynamic Planning with a LLM](https://arxiv.org/abs/2308.06391)
### Tool and Action
- [Automatic and Efficient Customization of Neural Networks for ML Applications](https://arxiv.org/abs/2310.04685)|OSDI ' 24
- [ToolChain^*](https://arxiv.org/abs/2310.13227)ToolChain^*: Efficient Action Space Navigation in Large Language Models with A* Search | ICLR'24
- [Middleware for LLMs: Tools Are Instrumental for Language Agents in Complex Environments](https://arxiv.org/abs/2402.14672)
- [Efficient Tool Use with Chain-of-Abstraction Reasoning](https://arxiv.org/abs/2401.17464)
- [ToolNet: Connecting Large Language Models with Massive Tools via Tool Graph](https://arxiv.org/abs/2403.00839)
- [Budget-Constrained Tool Learning with Planning](https://arxiv.org/abs/2402.15960)
#### Serverless
- [Serverless LLM](https://arxiv.org/abs/2401.14351) ServerlessLLM: Locality-Enhanced Serverless Inference for Large Language Models | OSDI'24
- [FaaSMem: Improving Memory Efficiency of Serverless Computing with Memory Pool Architecture](https://dl.acm.org/doi/abs/10.1145/3620666.3651355) | ASPLOS'24
  
### Memory
- [Retrieval-Augmented Generation with Knowledge Graphs for Customer Service Question Answering](https://arxiv.org/abs/2404.17723)
- [RET-LLM: Towards a General Read-Write Memory for Large Language Models](https://arxiv.org/abs/2305.14322)
- [Controlling the Extraction of Memorized Data from Large Language Models via Prompt-Tuning](https://arxiv.org/abs/2305.11759) | ACL'23
- [Memory Sandbox: Transparent and Interactive Memory Management for Conversational Agents](https://arxiv.org/abs/2308.01542)
- [RAGCache: Efficient Knowledge Caching for Retrieval-Augmented Generation](https://arxiv.org/abs/2404.12457)
  



## Component Collaboration and Agent Framework
focus on improving the efficiency of data exchange and data transmission within AI agents: ---hongqiu
- [LLM Multi-Agent Systems: Challenges and Open Problems](https://arxiv.org/abs/2402.03578)
- [Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents](https://arxiv.org/abs/2306.03314)
- [Dynamic LLM-Agent Network: An LLM-agent Collaboration Framework with Agent Team Optimization](https://arxiv.org/abs/2310.02170)
- [AIOS: LLM Agent Operating System](https://arxiv.org/abs/2403.16971)
- [AgentLite: A Lightweight Library for Building and Advancing Task-Oriented LLM Agent System](https://arxiv.org/abs/2402.15538)
- [Enabling Intelligent Interactions between an Agent and an LLM: A Reinforcement Learning Approach](https://arxiv.org/abs/2306.03604)
- [Gorilla: Large Language Model Connected with Massive APIs](https://gorilla.cs.berkeley.edu/)
- [Small LLMs Are Weak Tool Learners: A Multi-LLM Agent](https://arxiv.org/abs/2401.07324)
- [AgentLite: A Lightweight Library for Building and Advancing Task-Oriented LLM Agent System](https://arxiv.org/abs/2402.15538)
- [A Unified Debugging Approach via LLM-Based Multi-Agent Synergy](https://arxiv.org/abs/2404.17153)

## Device-Edge-Cloud Collaboration
- [Hybrid LLM](https://openreview.net/forum?id=02f3mUtqnM) Hybrid LLM: Cost-Efficient and Quality-Aware Query Routing | ICLR'24
- [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752)
- [Optimal Caching and Model Multiplexing for Large Model Inference](https://arxiv.org/abs/2306.02003) | NeurIPS'23
- [Optimising Calls to Large Language Models with Uncertainty Based Two-Tier Selection](https://arxiv.org/abs/2405.02134)
- [Octopus: On-device language model for function calling of software APIs](https://arxiv.org/abs/2404.01549)
- [Octopus v2: On-device language model for super agent ](https://arxiv.org/abs/2404.01744v5)| Stanford 
- [Octopus v3: Technical Report for On-device Sub-billion Multimodal AI Agent](https://arxiv.org/abs/2404.11459)| Stanford 
- [Octopus v4: Graph of language models](https://arxiv.org/abs/2404.19296)
## LLM and  Agent Framework
### LLM Framework
from [here](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey)
<div align="center">

|                                                    | Efficient Training | Efficient Inference | Efficient Fine-Tuning    |
| :-------------------------------------------------------------------- | :------------------: | :--------------------: | :--: |
| DeepSpeed [[Code](https://github.com/microsoft/DeepSpeed)]            | ✅                   | ✅                     | ✅   |
| Megatron [[Code](https://github.com/NVIDIA/Megatron-LM)]              | ✅                   | ✅                     | ✅   |
| Alpa [[Code](https://github.com/alpa-projects/alpa)]                  | ✅                   | ✅                     | ✅   |
| ColossalAI [[Code](https://github.com/hpcaitech/ColossalAI)]          | ✅                   | ✅                     | ✅   |
| FairScale [[Code](https://github.com/facebookresearch/fairscale)]     | ✅                   | ✅                     | ✅   |
| Pax [[Code](https://github.com/google/paxml/)]                        | ✅                   | ✅                     | ✅   |
| Composer [[Code](https://github.com/mosaicml/composer)]               | ✅                   | ✅                     | ✅   |
| vLLM [[Code](https://github.com/vllm-project/vllm)]                   | ❌                   | ✅                     | ❌   |
| TensorRT-LLM [[Code](https://github.com/NVIDIA/TensorRT-LLM)]         | ❌                   | ✅                     | ❌   |
| LightLLM [[Code](https://github.com/ModelTC/lightllm)]                | ❌                   | ✅                     | ❌   |
| OpenLLM [[Code](https://github.com/bentoml/OpenLLM)]                  | ❌                   | ✅                     | ✅   |
| Ray-LLM [[Code](https://github.com/ray-project/ray-llm)]              | ❌                   | ✅                     | ❌   |
| MLC-LLM [[Code](https://github.com/mlc-ai/mlc-llm)]                   | ❌                   | ✅                     | ❌   |
| Sax [[Code](https://github.com/google/saxml)]                         | ❌                   | ✅                     | ❌   |
| Mosec [[Code](https://github.com/mosecorg/mosec)]                     | ❌                   | ✅                     | ❌   |
| LLM-Foundry [[Code](https://github.com/mosaicml/llm-foundry)]         | ✅                   | ✅                     | ❌   |

</div>

### GenAI Develop Engine

- [dify](https://dify.ai/)
- [fedml](https://www.fedml.ai/)

### Agent Framework
- [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT)
- [LangChain](https://github.com/langchain-ai/langchain)
- [AutoGen](https://github.com/microsoft/autogen)
- [Camel](https://www.camel-ai.org/home)
- [HuggingGPT](https://huggingface.co/spaces/microsoft/HuggingGPT)
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer)
- [BabyAGI](https://github.com/yoheinakajima/babyagi)
- [Al Town](https://github.com/a16z-infra/ai-town)
- [GPTeam](https://github.com/101dotxyz/GPTeam)
- [ChatArena](https://github.com/chatarena/chatarena)
- [AgentVerse](https://github.com/OpenBMB/AgentVerse)

## Benchmark, Trace, and Dataset
- [BurstGPT](https://arxiv.org/abs/2401.17644)Towards Efficient and Reliable LLM Serving: A Real-World Workload Study

## LLM and Agent on Mobile Platform

- [Mobile LLM](https://arxiv.org/abs/2402.14905) MobileLLM: Optimizing Sub-billion Parameter Language Models for On-Device Use Cases | Meta

- [BBox-Adapter: Lightweight Adapting for Black-Box Large Language Models](https://arxiv.org/abs/2402.08219)
- [LLM as a System Service on Mobile Devices]()https://arxiv.org/abs/2403.11805

## Survey Papers
- [A Survey on Effective Invocation Methods of Massive LLM Services](https://arxiv.org/abs/2402.03408)
- [Personal llm agents: Insights and survey about the capability, efficiency and security](https://arxiv.org/abs/2401.05459)
- [LLM-Based Multi-Agent Systems for Software Engineering: Vision and the Road Ahead](https://arxiv.org/abs/2404.04834)
- [CASIT: Collective Intelligent Agent System for Internet of Things](https://ieeexplore.ieee.org/abstract/document/10439991)
- [Understanding the Weakness of Large Language Model Agents within a Complex Android Environment](https://arxiv.org/abs/2402.06596)
- [**The Landscape of Emerging AI Agent Architectures for Reasoning, Planning, and Tool Calling: A Survey**](https://arxiv.org/abs/2404.11584)
- [Awesome MobileLLM](https://github.com/stevelaskaridis/awesome-mobile-llm)
- [Understanding the planning of LLM agents: A survey](https://arxiv.org/abs/2402.02716)
- [**Awesome-LLM-Inference**](https://github.com/DefTruth/Awesome-LLM-Inference)
## Others
- [Berkeley Function-Calling Leaderboard](https://gorilla.cs.berkeley.edu/leaderboard.html)
- [A Primer on the Inner Workings of Transformer-based Language Models](https://arxiv.org/abs/2405.00208)