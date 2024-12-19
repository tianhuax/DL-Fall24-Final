This is the repository of Fall 2024 Deep Learning final project from Team Tianhua Xia and Haiyu Wang.

DL_Fall24_Final.ipynb includes the codes for our experiment. 

we do the experiments for quantizing KV vectors and LLM models using the framework from QUAROT (https://github.com/spcl/QuaRot/tree/main).

We do some modification to the Quarot repository and store our version here: https://github.com/tianhua2/my_quarot.git

We also edit the llama code in huggingface to add KV vector quantization and eviction codes. We store it as our own package here: https://github.com/tianhua2/my_huggingface.git The KV vector eviction codes is based on H2O (https://github.com/FMInference/H2O) with some modification.
