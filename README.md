# Machine Translation Using Transformers

Machine translation (MT) is a subfield of computational linguistics that focuses on using software to translate text or speech from one language to another. Basic MT performs simple word substitution, but this alone is often not enough to produce a good translation, as recognition of whole phrases and their equivalent counterparts in the target language is needed. The field of MT is rapidly growing and using statistical and neural techniques to overcome language differences and produce better translations. Current MT software allows for customization to specific domains or professions, leading to improved output. This technique is particularly effective for formal or formulaic language, such as in government and legal documents, but is less effective for less standardized text like conversation.


## Transformer

A transformer is a deep learning model that uses self-attention to determine the significance of each part of the input data. This model is widely used in natural language processing (NLP) and computer vision (CV). Unlike recurrent neural networks (RNNs), transformers process the entire input sequence at once and use the attention mechanism to provide context for every position in the input. This results in reduced training times as compared to RNNs, as more parallelization is possible.

Transformers were introduced in 2017 by Google Brain and have quickly become the preferred model for NLP tasks, replacing older RNN models such as long short-term memory (LSTM). The ability to train on larger datasets due to the additional parallelization led to the development of pre-trained systems such as BERT and GPT. These models were trained on large language datasets, like the Wikipedia Corpus and Common Crawl, and can be fine-tuned for specific tasks.

![image](https://user-images.githubusercontent.com/38975177/217238503-47b09e7e-d6ff-4e7d-98d7-7d49ee4f2deb.png)

## Transofmer Architecture

Transformers are deep learning models that are primarily used for natural language processing (NLP) and computer vision (CV). They differ from other models like recurrent neural networks (RNNs) in that they process the entire input sequence all at once, rather than processing one element at a time. This allows for more parallelization, which reduces training times. Additionally, transformers use a self-attention mechanism to determine the significance of each part of the input data, providing context for every position in the input.

Transformers were introduced in 2017 by a team at Google Brain and have since become the preferred model for NLP tasks, surpassing older models such as long short-term memory (LSTM) RNNs. The ability to train on larger datasets due to the additional parallelization has led to the development of pre-trained systems like BERT and GPT, which were trained on large language datasets like the Wikipedia Corpus and Common Crawl. These pre-trained systems can be fine-tuned for specific tasks, making transformers a versatile and flexible tool for NLP and CV applications.

In summary, transformers are deep learning models that process input sequences all at once and use a self-attention mechanism to determine the significance of each part of the input data. They have become the preferred model for NLP tasks due to their ability to train on larger datasets and their versatility in being fine-tuned for specific tasks.
