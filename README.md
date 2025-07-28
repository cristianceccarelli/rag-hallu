# rag-hallu

This repo contains the code developed for the paper _Knowledge-Grounded Detection of Factual Hallucinations in Large Language Models_. If the notebooks are not working, the code is also available at the following link: [rag-hallu]([https://website-name.com](https://drive.google.com/drive/folders/1tGiB0uGEBy_-uY5uGikPN5zpnn7VJzUG?usp=sharing)).

## Structure of the Repository
The repository is structured in the following way:

- **Results**: Results obtained during the experimental analysis. It is composed of:

  - *Few Shot:* Results obtained using few-shot prompting (both with and without knowledge integrated).
  - *SelfCheckGPT:* Results obtained using SelfCheckGPT (BERTScore, NLI, and LLM prompt, both with and without knowledge).
    
- **Source Code**: Code developed during the work. It is composed of:
  
  - *Few Shot:* Code developed for the few-shot prompting approaches.
  - *SelfCheckGPT:* Code developed to use SelfCheckGPT and its variants.
  - *Utils:* Code developed for knowledge retrieval.
    
- **data**: Data used for the experiments. It contains *FactBench* dataset and all the dataset with the retrieved knowledge.
