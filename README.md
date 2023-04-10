# latent-axis
Latent Axis is a library that makes it simple to run an "Axial Probe" using an LLM. An Axial Probe is a chain of prompts that makes the knowledge contained in Large Language Models more visible and accessible.

## What is an Axis
An axis is similar to a "dimension" or "parameter" in LLM parlance, but is human readable. For example: fruits vary in sweetness. We can organise fruits along an axis, or spectrum of sweetness like so:

![image](./axis.svg)


### Example Usage:
```js

axis(probe("fruit"), "sweetness")
