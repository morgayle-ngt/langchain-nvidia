# 🦜️🔗 LangChain NVIDIA

This repository contains two packages with NVIDIA integrations with LangChain:
- [langchain-nvidia-ai-endpoints](https://pypi.org/project/langchain-nvidia-ai-endpoints/) integrates [NVIDIA AI Foundation Models and Endpoints](https://www.nvidia.com/en-us/ai-data-science/foundation-models/).
- [langchain-nvidia-trt](https://pypi.org/project/langchain-nvidia-trt/) implements integrations of NVIDIA [TensorRT](https://developer.nvidia.com/tensorrt) models.
- Python Interpretor 3.10.12 is desired to the Jupyter Kernel to run without issues 
- PIP should also be upgraded to resolve dependency issues: 'python3.10 -m pip install --upgrade pip'

## There are many ways that an LLM can control an application 

- An LLM can route between two potential paths
- An LLM can decide which of many tools to call
- An LLM can decide whether the generated answer is sufficient or more work is needed

![LLM-Control](./images/agent_types.png)

## Tool calling are useful whenever you want an agent to interact with external systems.

![Tool-Calling](./images/tool_call.png)

## Examples of Cognitive Architectures
![Cognitive-Architectures](./images/Cognitive-Architectures.png)