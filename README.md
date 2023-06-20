# llama.cpp_testing
Documentation for Testing of Vicuna models through llama.cpp
  
### Outside Resources  
Used ggerganov llama.cpp from [here](https://github.com/ggerganov/llama.cpp/releases/tag/master-f647ce0).  
Download Vicuna 13B from [here](https://huggingface.co/eachadea/legacy-ggml-vicuna-13b-4bit/tree/main).  
Download Vicuna 7B from [here](https://huggingface.co/eachadea/legacy-ggml-vicuna-7b-4bit/tree/main).  
### Testing Information  
Models tested were Vicuna 13B and Vicuna 7B both 4 bit quantized version. Please note that these are considered **legacy** versions of their respecitve models. Both Vicuna models only contain knowledge up to September 2021 and are unaware of events or new information created after. These models are capable of retaining context from a prior inquiry and using the new information to formulate a response in the future. There are still issues with hallucinations as the models will often create information and in essence lie when asked for information it is either not knowledgable about or unsure of.  
![Screenshot 2023-06-19 202452](https://github.com/Cusith/llama.cpp_testing/assets/35042304/dccd76ec-6521-4b34-a72c-b2002b15b27f)
Here it is unaware that Queen of Elizabeth II has passed and that her successor was Prince Charles. It still hallucinated the incorrect date of death for the Queen even after being fed new information. Albeit it correctly updated the response now that it knows that the Queen had passed and her son was her successor.  

### Testing Environment/Equipment  
#### Testing Equipment  
Processor	Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz   2.59 GHz  
Installed RAM	24.0 GB (23.9 GB usable)  
System type	64-bit operating system, x64-based processor  
System Model	ROG Strix G531GT_G531GT  
Graphics Processor NVIDIA GeForce GTX 1650 4GB VRAM  
#### Testing Environment  

### Setup  
