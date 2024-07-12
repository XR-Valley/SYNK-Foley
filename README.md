# SYNK-Foley

## experiment description
Automatically generate foley sounds for all (or all tagged) 3D assets in a Unity SYNK project using [AudioLDM](https://audioldm.github.io/audioldm2/) and a local LLM (several models tested) to create a meaningful audioLDM prompt from the metadata of a 3D asset.

The flow is as follows

![image](https://github.com/user-attachments/assets/c9aab333-a5e2-464a-8315-0ebb15fa6e28)


## technology used  
[AudioLDM](https://audioldm.github.io/audioldm2/) to generate AudioFiles  
[Guidance](https://github.com/guidance-ai/guidance) to guardrail the local LLM to return structured data only  
[LlamaCCP](https://llama-cpp-python.readthedocs.io/en/latest/) a localLLM inference implementation for prompt generation  
python to make an interactive CLI application and interact with the FTRACK data  
