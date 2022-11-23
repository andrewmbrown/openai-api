# OpenAI API Notes # 
## Introduction ##

We can use the OpenAI API to interact with OpenAI moels for generating natural language or code. This is a quick note on how to use the API.

### Completions ### 
The main ideal we give to the API is a completion task. Given a prompt, we want to generate a completion following a pattern of some sort.
#### Prompt Design ####
TODO


### Tokens ###
The API will take inputted text and break the words into tokens. Usually sub-word tokenization. The number of tokens processed in a given API request depends both on the lengths of inputs and outputs. OpenAI suggests that roughly 1 token is approximately 4 characters or 0.75 words for English text. We also must consider that the prompt + completion text must be no more than the model's maximum context length (usually 2048 tokens or about 1500 words). OpenAI provides a [tokenizer tool](https://beta.openai.com/tokenizer) to learn more about how text translates to tokens.

### Models ###
Most models OpenAI allows for inference and fine-tuning are transformer-based generative encoder models.

GPT-3 models 
- Davinci
- Curie
- Babbage
- Ada


