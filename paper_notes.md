### Efficient Transformers: A Survey

Google, 2020-09-16

#### 摘要

一个Transformers的综述文章，提到了很多基于Transformer的改进模型，差不多17个，这里就不列了。

有几个关于Transformer的描述可以借鉴下：

1. The self-attention mechanism is a key defining characteristic of Transformer models.
2. A well-known concern with self-attention is the quadratic time and memory complexity.
3. Transformer blocks are characterized by a multi-head self-attention mechanism, a position-wise feed-forward network, layer normalization modules and residual connectors.
4. Positional encodings can take the form of a sinusoidal input or be trainable embeddings.
5. It is important to note the differences in the mode of usage of the Transformer block. Transformers can primarily be used in three ways, namely: (1)encoder-only, e.g. for classification; (2)decoder-only, e.g. for language modeling; (3)encoder-decoder, e.g. for machine translation.

文章对这17个模型改进做了分类，大致可分为五大类。这里也不列举了，具体还是看了论文再补充吧。

最后，比较重要的结论是

> It's a still a mystery to which fundamental efficient Transformer block one should consider using.

没错，到底谁好谁不好，文章表示不同的模型彼此之间的评测标准不一样，有些还涉及到了预训练，所以，孰优孰劣无法得出结论。这让我觉得这篇文章也是在灌水。

### ELECTRA

Stanford University & Google

