## Some experimental custom nodes for [ComfyUI](https://github.com/comfyanonymous/ComfyUI)

Copy the .py files to your custom_nodes directory to use them.

They will show up in: custom_node_experiments/

sampler_tonemap.py contains ModelSamplerTonemapNoiseTest a node that makes the sampler use a simple tonemapping algorithm to tonemap the noise. It will let you use higher CFG without breaking the image. To using higher CFG lower the multiplier value.

sampler_rescalecfg.py contains an implementation of the Rescale Classifier-Free Guidance from: https://arxiv.org/pdf/2305.08891.pdf
