# GPT2

**Status:** 🧱 Out of Scope

**Last meanigful update:** [2025-04-08]

### Context
I wanted to recreate GPT2.

### How it works
Decoder only transformer model to predict the next token, much smaller in size than the actual GPT2.

### Archival reason
While the loss and output showed that the model certainly did start learning, I calculated that for the smallest model that would in theory actually learn would still take a month of 24/7 training on my hardware to achieve the same level of training as a usable LLM, not to forget all the correct data parsing needed.

### Hindsight lessons
- Slightly better understanding of transformers
- How much training it actually takes for big models
