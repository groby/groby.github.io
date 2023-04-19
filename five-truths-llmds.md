5 things I believe to be true about LLMs
-----------------------------------------

### 1) We are witnessing an inflection point. Likely for large parts of the economy, but *definitely* in the realm of software engineering.

LLMs are changing the way we approach programming, as we can now use them to generate code and improve code understanding based on natural language descriptions. This is a massive productivity accelerator for developers, and it pushes the complexity frontier for what people can tackle as one-off efforts.

### 2) It is vulnerable both on input and output. 

Main input vulnerability is prompt injection, which precludes many general-purpose uses. Main output vulnerability is hallucination

### 3) These are first and foremost powertools for skilled practicioners in well-defined domains. 

Given hallucinations are a key problem, we should assume LLMs lie. Using them successfully requires the ability to verify the truth of their output. This is not an approach the general public will choose.

At the same time, verification and prompt writing will be a crucial toolkit for software engineers. (And other industries that find sufficient fit)

We cannot confuse access to the tool with having an understanding. 

As a corollary, if you are looking for widely accessible use cases, success will likely lie in semi-structured data in, structured data out, with a careful interpretation layer. Anything else is asking for things to go horribly awry.


### 4) On-device/On-Prem/private cloud matters.

The data handed to LLMs, especially in a commercial context, is often sensitive. Keeping access strictly controlled and ideally not sharing with third parties will be a key part of the value proposition of early successful LLM companies. "Let me pipe what you said to ChatGPT" is not a business model. 

This sensitivity also means that anything the model has access to, prompt injection has access to. This is one more reason to carefully ring-fence access.


### 5) Custom fine tuning matters

LLMs are pre-trained on massive amounts of data, but fine-tuning on custom data often significantly improves their performance for specific applications. It is a way to improve accuracy, filter bias, and adopt to specific needs. 

But this requires significant compute effort - this means there needs to be high-value payoff. (And of course, overfitting looms)
