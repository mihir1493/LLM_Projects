# RAG Pipeline with Tensorflow and Open Source Hugging Face Model 


![alt text](https://github.com/mihir1493/LLM_Projects/blob/main/Pipeline.png)

## Outline Steps:
* Open a PDF Document
* Format the Text of PDF to be fit for Embedding Model
* Embed all chunks of the text and turn them into numerical representation
* Build a retreival model that uses vector search to find relevant piece of chunks based on user query
* Create a prompt that has the retreived piece of text
* Generate a answer based on the returned output

## Used Libaries, Models and Packages 
* Embedding Model: all-mpnet-base-v2
* Pytorch
* LLM Model: google/gemma-2b-it (IT: Instruction Tuned)
* CUDA

### Reference: 
Augment our prompt with context items
* https://www.promptingguide.ai/
* https://github.com/brexhq/prompt-engineering
* https://arxiv.org/abs/2401.14423

## Setup
Note: Tested in Python 3.11, running on Windows 10 with a NVIDIA RTX 1080TI with CUDA 12.1.

### Create environment
```
python -m venv venv
```
### Activate environment
Linux/macOS:
```
source venv/bin/activate
```
Windows: 
```
.\venv\Scripts\activate
```




