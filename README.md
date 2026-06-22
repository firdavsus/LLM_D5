This is a Dense model 470M model trained on multilingual dataset with XSA Attention with custom tokenizer specialized on Englsih, Russian and Uzbek langauges.

# General Info
|Dataset info|Value|
|----|-----|
|Dataset size|100B|
|lr|3-e4|  
|batch size|1M|
|block size|2048|


|Model info|Value|
|----|-----|
|model dim|1024|
|ffn dim|2736|  
|layes|32| 
|head dim|128|
|embedings|65K|
|Attention type|XSA|
|FFN type|SwiGLU gated|
|Position embs|RoPE|

# Benchmarks
|Test|Value|
|----|-----|
|Hellaswag|50%|


# References
XSA->https://arxiv.org/pdf/2603.09078
SwiGLU gated->https://medium.com/@saeed.mehrang/swiglu-the-activation-function-powering-modern-llms-70ea5cfdeafe
RoPE->https://arxiv.org/pdf/2104.09864
